# Driver Linux Mint 18.2

Para Linux Mint 18.2 se necesita un driver especial para que el cable de integración funcione correctamente.

Para ello descargamos el archivo serial-4.4.tar.gz y corremos los siguientes comandos par instalarlo:

```sh
$ tar -zxvf serial-4.4.tar.gz
$ sudo apt install linux-headers-generic build-essential
$ cd  serial/
$ make -C /lib/modules/$(uname -r)/build M=$(pwd) modules	
$ sudo cp ch341.ko /lib/modules/$(uname -r)/kernel/drivers/usb/serial/ch341.ko
$ sudo rmmod ch341
$ sudo modprobe ch341
$ reboot
```
Una vez reiniciado el equipo el SDK debe poder comunicarse con el POS.
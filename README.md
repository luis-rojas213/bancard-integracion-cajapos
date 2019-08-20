# bancard-integracion-cajapos

Instrucciones de archivos

- Documentaciones:
	- “Configuraciones.pdf” es un explicativo de como configurar el archivo config.json y como correr el SDK en el equipo en el que estará conectado el POS.
	- “DocumentacionWebServices” es la documentación de los servicios disponibles en el SDK. (también se puede ver con un navegador una vez levantado el servicio en un puerto).
- En la carpeta Windows se encuentran los siguientes archivos:
	- El archivo llamado “DRIVER_USB_HI 340 XP W7.rar” es el driver del cable de integración para Windows, esto lo deberían instalar para que reconozca el POS como un puerto COM, este puerto COM lo deben configurar luego en el archivo config.json del SDK según como explica también la documentación de configuración.
	- sdk-backend-windows-x64: contiene el index.exe para correr el SDK con su archivo de configuración (Arquitectura x64).
	- cajapos-front-win32-x64: contiene el ejecutable del simulador para pruebas (Arquitectura x64).
	- sdk-backend-windows-x86: contiene el index.exe para correr el SDK con su archivo de configuración (Arquitectura x86).
	- cajapos-front-win32-x86: contiene el ejecutable del simulador para pruebas (Arquitectura x86).
- En la carpeta Linux se encuentran los siguientes archivos.
	- SDKComoServicioLinux.pdf: Muestra como agregar el ejecutable como un servicio de Linux para que se ejecute al arrancar el Sistema Operativo.
	- sdk-backend-linux-x64: Contiene el index para correr el SDK con su archivo de configuración (Arquitectura x64)
	- sdk-backend-linux-x86: Contiene el index para correr el SDK (Arquitectura x86)
	- cajapos-front-linux-ia32: Contiene el ejecutable del simulador para pruebas (Arquitectura x86).
	- cajapos-front-linux-x64: Contiene el ejecutable del simulador para pruebas (Arquitectura x64).


# Chatbot en Proceso (WIP)
[whatsapp-web.js](https://wwebjs.dev/guide/#installation)

## Descripción
Este es un proyecto en desarrollo de un chatbot que utiliza WhatsApp Web para interactuar con usuarios. A través de este README, te proporcionaremos las instrucciones necesarias para instalar y configurar el chatbot en tu sistema.

## Instalación
Asegúrate de tener Node.js instalado en tu sistema antes de comenzar. Puedes descargarlo desde [el sitio oficial de Node.js](https://nodejs.org/).

1. Clona este repositorio en tu sistema local o descárgalo como un archivo ZIP y descomprímelo.

2. Abre una terminal y navega hasta el directorio raíz del proyecto.

3. Instala las dependencias necesarias ejecutando los siguientes comandos:
   ```bash
   npm install qrcode-terminal
   npm install whatsapp-web.js
   ```

## Configuración (Linux)
Si estás utilizando Linux, sigue estos pasos adicionales para configurar el chatbot:

1. Otorga permisos de lectura, escritura y ejecución a las siguientes carpetas:
   - `.wwebjs_auth`
   - `.wwebjs_cache`

   Puedes hacerlo ejecutando el siguiente comando en la terminal:
   ```bash
   chmod -R 700 .wwebjs_auth .wwebjs_cache
   ```

## Uso
Una vez que hayas instalado las dependencias y configurado las carpetas en Linux, puedes ejecutar el chatbot utilizando el código proporcionado en el proyecto. Asegúrate de tener acceso a WhatsApp Web en tu dispositivo móvil y sigue las instrucciones para escanear el código QR que aparecerá en la terminal.

## Contribuciones
Este proyecto está en proceso y las contribuciones son bienvenidas. Si tienes ideas para mejorarlo o encuentras problemas, no dudes en abrir un problema o enviar una solicitud de extracción.

## Licencia
Este proyecto se distribuye bajo la licencia MIT. Consulta el archivo `LICENSE` para obtener más información.

¡Disfruta utilizando este chatbot en desarrollo!

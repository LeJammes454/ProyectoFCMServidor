# Servidor Notificaciones PUSH

Este proyecto es una aplicación de servidor Node.js simple que utiliza el SDK de Admin de Firebase para enviar notificaciones push a dispositivos Android.

## Requisitos

- Node.js
- npm
- Cuenta de Firebase y clave de servicio

## Instalación

1. Clona este repositorio o descarga el código fuente.

_bash_ 
```
git clone https://github.com/LeJammes454/ProyectoFCMServidor.git
```

2.  Navega a la carpeta del proyecto en la terminal o línea de comandos.


_bash_ 
```
cd <your-repo-name>
```



3.  Instala las dependencias del proyecto con npm.


_bash_
```
npm install
```

4.  Coloca el archivo JSON de la clave de servicio de Firebase en la carpeta del proyecto y actualiza la ruta en `app.js`:

_javascript_
```
const serviceAccount = require('./path/to/your-service-account-file.json');
```
## Uso

1.  Ejecuta la aplicación de servidor con el siguiente comando:

_bash_
```
node app.js
```

2.  Abre un navegador y ve a `http://localhost:3000` para acceder a la interfaz básica para enviar notificaciones push.
    
3.  Ingresa el token del dispositivo, el título y el cuerpo del mensaje, y haz clic en "Enviar Notificacion" para enviar la notificación push.
    

## Licencia

Este proyecto está bajo la licencia MIT.

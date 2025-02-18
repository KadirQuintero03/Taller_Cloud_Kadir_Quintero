# Taller_Cloud_Kadir_Quintero

Pasos para construir la imagen y ejecutar el contenedor dentro de las computadoras.

-> Paso 1. Iniciar sesion con Docker Hub por medio de la terminal usando su usario y contraseña para poder descargar la imagen.

-> Paso 2. Una vez iniciada la sesion escribimos el comando "docker pull keduardoquintero/keduardoquintero:latest" para descargar la imagen desde docker hub a nuestro dispositivo.

-> Paso 3. Una vez descargada la imagen debemos construir el contenedor con el siguiente comando "docker run -d --name nombrecontenedor -p puertohost:8000 imagen" y ejecutarlo

-> Paso 4. Ya montado el contenedor podemos probarlo desde la web usando "localhost:puertohost"

ACLARACION: Cabe aclarar que el "Puertohost" es el que usted como usuario haya designado, por ejemplo, si uso el 8080:8000 entonces seria "localhost:8080" 

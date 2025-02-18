# Como construir y ejecutar un Contenedor con Docker en base a una imagen / Taller Cloud

Por favor seguir el paso a paso sobre cómo descargar una imagen desde Docker Hub, crear un contenedor y ejecutarlo en su computadora.

1️⃣ Iniciar sesión en Docker Hub
-> Para descargar la imagen, es necesario iniciar sesión en Docker Hub, para ello acceda desde su terminal y ejecute el siguiente comando: <- 

```bash
docker login
```

> 📌 **Nota:** En caso de que no se logre loggearse satisfactoriamente por el metodo actual de docker, se puede utilizar el siguiente comando para loggearse:

```bash
docker login -u username -p password
```

2️⃣ Descargar la imagen desde Docker Hub

-> Una vez iniciada la sesion, ejecute el siguiente comando para descargar la imagen desde el repositorio en Docker Hub a su computadora: <-

```bash
docker pull keduardoquintero/keduardoquintero:latest 
```

3️⃣ Crear y ejecutar el contenedor

-> Ya descargada la imagen, debemos crear y ejecutar el contenedor. Para ello, utilizaremos el siguiente comando: <-

```bash
docker run -d --name nombrecontenedor -p PUERTO_HOST:8000 keduardoquintero/keduardoquintero:latest 
```

4️⃣ Acceder al contenedor desde el navegador

-> una vez que el contenedor está en ejecución, procedemos a probar su funcionalidad ingresando desde el navegador web a: localhost:PUERTO_HOST

⚠️ **Importante**: Cabe aclarar que el "PUERTO_HOST" es el que usted como usuario haya designado al ejecutar el contenedor, por ejemplo, si uso el "-p 8080:8000" entonces seria "localhost:8080" 

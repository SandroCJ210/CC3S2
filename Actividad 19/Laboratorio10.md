# Laboratorio 10

Nombres y Apellidos: Sandro Alfredo Carrillo Jordán

En este avance del laboratorio vamos a levantar una imagen docker, su contenedor y luego verificar que este está levantado por medio de un curl.

Primero comenzamos levantando la imagen con

```
docker build -t ejemplo-microserice:0.1.0 .
```

(me confundí y lo escribí mal al realizarlo)

Esto va a levantar la imagen y va a ponerle de nombre ejemplo-microserice:0.1.0. El "punto" ., sirve para indicar el contexto en el que queremos ejecutar esto, si el dockerfile estuviera en otra carpeta aparte de la raíz, tendríamos que usarla. Obviamente el Docker Desktop tiene que estar abierto antes.

![alt text](image.png)

Luego levantamos el contenedor, indicanto nombre y puerto

![alt text](image-1.png)

Por último hacemos una verificación mediante un get a la api del microservicio

![alt text](image-2.png)
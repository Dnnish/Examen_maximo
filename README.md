# Examen_maximo

ejercicio 1
Como el ejercio indica tenenmos que ejecutar el comando "docker pull ubuntu:18.04"
al ejecutarlo nos descargaremos una imagen, luego nos pide ejecutar el comando "docker run -it ubuntu:18.04 /bin/bash" lo que hara es acceder como root y si salimos del terminal el contenido se para. 
![image](https://user-images.githubusercontent.com/97433514/173293977-7323fb58-6f49-4614-b1d2-9dce8991a3d3.png)
Ejercicio 2
 Con el comando "docker run ubuntu:18.04 ls /" Creamos un contenedor y listamos el contenido de la carpeta,
 nos mostrara todo el contenido.
![image](https://user-images.githubusercontent.com/97433514/173301039-50e366c9-9044-47d6-bb1a-2218f49ab852.png)

ejercicio3
En este ejercicio crearemos un servidor apache 2.4, para ello tenemos que ejecutar el comando "docker run httpd" y luego nos mostrara el log.
![image](https://user-images.githubusercontent.com/97433514/173301205-23564895-7c40-4541-8617-fd4ccf01164c.png)

ejercico4
En este ejercicio empezaremos creando un contenedor de debian 9 y enseñara todo el contenido de la carpeta indicada con el parámetro -w
el comando es "docker run -it -w /etc debian:9 ls"
![image](https://user-images.githubusercontent.com/97433514/173301366-417c2749-f11e-4924-aa4c-45540d3e7b9a.png)
luego de crear el contenedor mostraremos el contenedor en ejecución con el comando "docker ps" y 
para motrar todos los contenedores acturales creados tanto ejecuntandoce como parados usamos el comando
"docker ps -a"
![image](https://user-images.githubusercontent.com/97433514/173301622-957a6872-cd06-4feb-b300-0f50d7a67547.png)

-------------------------------------------------------------------------------------------
Apartado 2


para empezar creando la imagen tenemos que hacer un pull del tomcat
luego tenemos que crear un repositorio y luego crear un vi , en el vi ponemos todo lo que nos indica la pagina
![image](https://user-images.githubusercontent.com/97433514/173311957-a943961e-f2d8-440a-82b0-2efef65310ea.png)
luego creamos la imagen con el comando de buid de la imagen
![image](https://user-images.githubusercontent.com/97433514/173314401-39ad2e33-a2d7-4f48-953b-47121f7213be.png)

luego le ponemos la etiqueta en mi caso le puse d3nnis1234/tomcat
![image](https://user-images.githubusercontent.com/97433514/173315380-4158015c-24d3-484b-bab0-c82c7746c7ef.png)
luego lo subimo a hub con el comando siguiente
![image](https://user-images.githubusercontent.com/97433514/173319272-e60524a3-67f3-48a5-99be-4dd5aa95940e.png)




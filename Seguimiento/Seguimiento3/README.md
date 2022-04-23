# Explicacion Taller No_3

## 1) Primero creamos dos grupos uno llamado estudiante y otro profesor con el comando (groupadd) asi:

<img src="../../Imagenes/taller3.1.png" alt="imagen de comando groupadd">

## 2) Segundo creamos tres usuarios uno llamados diana, laura y claudia  con el comando (adduser) asi:

<img src="../../Imagenes/taller3.2.png" alt="imagen de comando adduser">

## 3) Tercero asignamos clases a los usuarios creados, diana sera profesora, laura estudiante y claudia profesora y estudiante con el comando (usermod -a -G nombre_grupo nombre_usuario) asi:

<img src="../../Imagenes/taller3.3.png" alt="imagen de comando usermod -a -G nombre_grupo nombre_usuario">

## 4) Creamos dos carpetas una llamada profesores y otra estudiantes con el comando (mkdir nombre_carpeta) luego damos permisos en las carpetas con el comando (chgrp nombre_grupo nombre_carpeta) y validamos que sea correcto asi:

<img src="../../Imagenes/taller3.4A.png" alt="imagen de comando usermod -a -G nombre_grupo nombre_usuario">
<img src="../../Imagenes/taller3.4B.png" alt="imagen de comando usermod -a -G nombre_grupo nombre_usuario">

## 5) Probamos con los diferentes usuarios y estos permisos son correcots asi:

<img src="../../Imagenes/taller3.5A.png" alt="imagen de comando usermod -a -G nombre_grupo nombre_usuario">
<img src="../../Imagenes/taller3.5B.png" alt="imagen de comando usermod -a -G nombre_grupo nombre_usuario">
<img src="../../Imagenes/taller3.5C.png" alt="imagen de comando usermod -a -G nombre_grupo nombre_usuario">
<img src="../../Imagenes/taller3.5D.png" alt="imagen de comando usermod -a -G nombre_grupo nombre_usuario">
<img src="../../Imagenes/taller3.5E.png" alt="imagen de comando usermod -a -G nombre_grupo nombre_usuario">

## 6) Creamos archivos en los respectivos directorios con el comando touch asi:

<img src="../../Imagenes/taller3.6A.png" alt="imagen de comando usermod -a -G nombre_grupo nombre_usuario">
<img src="../../Imagenes/taller3.6B.png" alt="imagen de comando usermod -a -G nombre_grupo nombre_usuario">
<img src="../../Imagenes/taller3.6C.png" alt="imagen de comando usermod -a -G nombre_grupo nombre_usuario">
<img src="../../Imagenes/taller3.6D.png" alt="imagen de comando usermod -a -G nombre_grupo nombre_usuario">

## 7) Cambiamos los dueños de estos archivos con el comando (chown nombre_usuario nombre_archivo) asi:

<img src="../../Imagenes/taller3.7A.png" alt="imagen de comando usermod -a -G nombre_grupo nombre_usuario">
<img src="../../Imagenes/taller3.7B.png" alt="imagen de comando usermod -a -G nombre_grupo nombre_usuario">

## 8) Intentamos entrar en el usuario laura colocando mal su clave de para que se guarde el numero de accesos fallidos asi:

<img src="../../Imagenes/taller3.9.png" alt="imagen de comando usermod -a -G nombre_grupo nombre_usuario">

## 9) Ahora si accedemos a el usuario laura de forma correcta para ver el numero de intentos fallidos asi:

<img src="../../Imagenes/taller3.10.png" alt="imagen de comando usermod -a -G nombre_grupo nombre_usuario">

## 10) Despues comprimimos el contenido de los directorios de los profesores en profesore.tgz y el contenido del directorio de los directorio de los estudiantes de un archivo estudiantes.zip con el comando (tar -cvf nombre_nuevo_archivo nombre_archivo_comprimir) asi:

<img src="../../Imagenes/taller3.11.png" alt="imagen de comando usermod -a -G nombre_grupo nombre_usuario">

















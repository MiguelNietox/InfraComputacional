# Seguimiento 3


En este documento realizaremos el taller numero 3 relacionado a grupos,usuarios y permisos.

##Punto1 crear grupos
Para este punto vamos a crear dos grupos (profesor y estudiante) para esto vamosa utilizar el comando sudo groupadd seguido del nombre del grupo asi:

../../Imagenes/taller3.1.png


##Punto2 crear usuarios
Para este punto vamos a crear tres usuarios (diana,laura,claudia) para esto vamos a utilizar el comando sudo adduser nombre del usuario asi:

../../Imagenes/taller3.2.png

##Punto3 asignar los usuarios a respectivos grupos
Para este punto vamos a asignar los usuarios a sus respectivos grupos a el usuario diana lo asignaremos al grupo profesor, a el usuario laura a el grupo estudiante y al usuario claudia lo asignaremos a los dos grupos con el comando sudo usermod -a -G nombre_grupo nombre_usuario  asi:

../../Imagenes/taller3.3.png


##Punto4 asignar permisos de los grupos a las carpetas 
Para este punto luego de crear dos carpetas (estudiantes y profesores) a el grupo estudiante le asignaremos permisos wrx y a el grupo profesor le asignaremos permisos wrx con el comando chown :nombre_grupo nombre_directorio asi:

../../Imagenes/taller3.4.png

##Punto5


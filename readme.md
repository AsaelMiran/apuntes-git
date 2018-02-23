##Curso de git desde cero
Sistema de control de versiones para el mantenimiento eficiente y confiable de archiivos 

##Zonas de git

1.- Directorio de trabajo
2.- Area de preparacion 
3.- Directorio de git

##Flujo de trabajo basico en git 
1.- Modificar una serie de archivos eb tu directorio de trabajo.
2.- Prepara los archivos, añadiendolos a tu area de preparacion.
3.- Confirma los cambios, lo que toma los archivos tal y como estan en el area de preparacion y almacena esa copia instantanea de manera permanente en tu directorio de git.

##Configurando git por primera vez 
```git config --global user.name "John Doe"
git config --global user.email roster@gmail.com
git config --global core.editor subl
git config --list
```


##git commit -a  -m  "Saltando el area de preparacion";
##git commit -am "equivalente a git commit -a -m "memsaje commit" "

   agrega los al chivos que ya estamos ratreando en el repocitorio de git 


##git commit 
   permite hacer un comit desde el editor de texto predeterminado

##git rm
Elimina  un archivo

##git checkout -- archivo
recupera el archivo 

##git mv 
git mv file_from file_to
Renombrar archivos
Equivalente a los siguientes pasos
```
1.-Renombrar el archivo manualmente
2.- git rm eliminar el archivo con git
3.- git add para agregar el archivo con el nuevo nombre
```
##git log 
Muesta el historial de confirmaciones

entre las opciones del comando podemos encontrar 

##git log Caracteristicas

--oneline:nos muestra el historial 
--graph:añade un pequeño grafico  ASCII mostrando el historial de ramificaciones y uniones.

git log --decorate --graph --oneline --all


git log -2 --oneline --graph
muestra los dos ultimos commit ademas de los parametros oneline y graph

git log --pretty=format:"%h - %an, %ar : %s"
muestra un log con el formato indicado con una serie de parametros como el autor del commit la hora  
%ar = fecha
%s:mensaje del commit
%an:autor del commit

git log --after="2018-02-16"
muestra el historial apartir del 16 de febrero del 2018

git log --before="2018-02-16"
Muestra el historial antes del 2018-02-16

git log --before="2018-02-16 00:00"

Muestra el historial antes del 2018-02-16 y antes de las 00:00 del mismo dia 

git log --after="2018-02-15 23:59:59" --before="2018-02-16 19:00:00"

muestra el historial filtrando apartir y antes de una fecha

git log --decorate --oneline 

##git commit --amend (rehace la confirmacion)

Este comando utiliza el area de preparacion para la confirmancion.

Al final terminaras con una sola confirmacion 

- la segunda confirmacion  reemplaza el resultado de la primera
ejemplo:se subio un archivo al directorio git pero con el comando git commit --amed se puede editar el ultimo commit realizado y si hay mas archivos en el area de preparacion los mete en ese commit 

##git reset Head.md (Deshace la preparacion)

El archivo o los archivos salen del area de preparacion

## git clone
git clone https://github.com/escueladigital/EDgrid.git

clona un directorio de git en el ejemplo clonamos el directorio de EDGRID

git clone https://github.com/escueladigital/EDgrid.git Miproyecto;

Clona EDGRID pero ahora dentro de la capeta miproyecto


##git diff df0a8ee ce028f8

Muestra la diferencias entre 2 commits

##ir en el tiempo 

git checkout "commit"

##regresar al presente
git checkout master

##crear una rama en git 
git branch --help

git log --decorate --oneline --all  

cambiar a otra rama 
git checkout testing

#HEAD apunta siempre a donde nos encontremos  la rama que apunte a head se muve con forme el proyecto avanze las demas se quedan en el pasado o dende se hayan movido














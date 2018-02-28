
##crear una rama en git 
git branch --help

una rama en git es simplemente un apuntador movil apuntado a uno de los commit

git log --decorate --oneline --all  

cambiar a otra rama 
git checkout testing

#HEAD apunta siempre a donde nos encontremos  la rama que apunte a head se muve con forme el proyecto avanze las demas se quedan en el pasado o dende se hayan movido

<<<<<<< HEAD

##git branch 
<<<<<<< HEAD
muestra todas las ramas y en cual de ella nos econtramos

=======
muestra todas las ramas y en cual de ella nos econtramos
>>>>>>> universo3
=======
puedo crear todas las ramas que quiera o necesite
Las ramas nuevas que se crean apuntan al commit actual

>>>>>>> testing

## git branch -d nombreRama
Elimina nombreRama si ya ha sido fucionada con la rama actual 

##git branch -D nombre rama 

Elimina nombreRama esté o no este fusionada con la rama actual.

Se fuerza el borrado, se pierden los cambis.

##git branch --no--merged 
permite saber que ramas no se han fucionado a un a la rama actual.

##git branch --merged
no permite saber que ramas ya han sido fucionadas a la rama actual



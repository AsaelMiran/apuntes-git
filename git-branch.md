
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

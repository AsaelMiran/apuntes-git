## git remote add origin https://github.com/AsaelMiran/apuntes-git.git

Con este comando vinculamos nuestro repositorio local con github

## git push origin master

permite subir los commit actuales a git en la nube  origin en la rama oculta de git y master es la rama local que queremos subir

## Pasos para haportar a otro repositorio
1.-hacer un fork en git hub
2.- clonar el repositorio desde mi cuenta de git hub
3.- crear una rama local.
4.- realizar mis cambios en mi nueva rama local.
5.- confirmar los cambios realizados en local.
hacer push de mis cambios (enviar los commit locales a GitHub) `git push origin nombre_rama`

7.- Crear un pull request con la nueva rama de mi repositorio en Github.

8.- Esperar a que el administrador del repositorio acepte mis cambios.

## git fetch origin master
para traer los cambios realizados en el directorio remoto de github

##git remote rename origin github
Permite renombrar el repositorio remoto

##push -u bitbucket master
permite subir un repositorio, en este caso se esta subiendo a bitbucket se recomienda usar la bandera -u cuando es la primera vez que se esta subiendo el proyecto y estamos empujando la rama master 

##git remote remove bitbucket
Eliminar una rama remota con remove nombre de la rama


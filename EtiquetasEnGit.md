# git tag
Muestra todas las etiquetas en el proyecto git 

# Etiquetas ligeras 
git tag mi-etiqueta
usar cuando queremos marcar algun punto en la historia, para marcar pequenñas funcionalidades para una funcion en desarrollo etc

Una etiqueta ligera no es mas que un checksum de un commit guardado en un archivo, no incluye mas informacion. Para crear una etiqueta ligera, no pasamos la opcion ( -a, -s , -m )

## Etiquetas onotadas 

Se guardan en la base de datos de git como objetos enteros. Tienen un checksum; contienen el nombre del etiquetados, correo electronico y fecha; y tienen un mensaje asociado.

Ejemplo de una etiqueta onotada:
git tag -a v1.0 -m "version 1.0 del sistema informatico
> Notas de las primeras clases del curso git desde cero
> Probando las etiquetas onotadas. 

## Ver la etiqueta git show
git show mi-etiqueta

## Crear una etiqueta corta en un pundo de la historia 

git tag Elimiar.md e276c80

donde el segundo parametro es el punto de la istoria donde de quiere realizar el tag ( e276c80 )

## Buscar etiquetas con ciertos parametros

git tag -l "v1.*"
lista las etiquetas que tengan v1.* * = lo que sea 
v1.Lo que sea

```
Lista las etiquetas que coincidan con el patron especificado
´´´	





El sticky bit su funcion principal es proteger los archivos dentro de ese directorio para que solo el propietario del archivo o root pueda interactuar con ellos.
Se utiliza de la siguiente manera:
`chmod +t "directorio"`.
El sticky bit se muestra al final de los permisos del directortio con una t.
Solo reestringe el eliminar o renombrar archivos.
#### Si tenemos un archivo con sticky bit dentro de una carpeta en la cual tenemos permisos, si intentamos borrar la carpeta no podremos hacerlo debido al sticky bit.
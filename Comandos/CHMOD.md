#### Con CHMOD podemos dar permisos a un archivo o una carpeta
Se utiliza con notacion octal.
Para dar [[Permisos]], recordemos que tenemos 3 tipos:
|Propietario|Grupo|Otros|
Entonces tenemos que pensarlo como binario con 3 bits, si queremos que tengan todos los permisos tendriamos
|rwx|rwx|rwx|
|111|111|111| = 777
Se pondria de la siguiente manera:
`chmod 777 "archivo"`
Si queremos que el grupo y propietario tengas permisos pero los otros no seria:
|rwx|rwx|rwx|
|111|111|000| = 770
Se pondria de la siguiente manera:
`chmod 770 "archivo"`

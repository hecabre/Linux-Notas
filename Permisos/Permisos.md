Los permisos que tenemos tienen cierta prioridad, por ejemplo si tenemos una carpeta con permiso de escritura, lectura. Pero en un archivo dentro de esa carpeta ponemos que no hay escritura, ni lectura, los permisos no funcionara, ya que la carpeta esta configurada con los otros permisos y tinen mas prioridad. Si queremos que esto funcione tendremos que usar el [[Sticky Bit]], el cual es un [[Permisos Especiales]].
Los permisos son 3:
- Lectura: r (read)
- Escritura: w (write)
- Ejecucion: x 
Tenemos 3 tipos de permisos en orden:
- Propietario: quien lo creo.
- Grupo: puede ser un grupo "Alumnos".
- Otros: Los demas que no esten en un grupo.
Normalmente aparecen de la siguiente manera:
|Propietario|Grupo|Otros|


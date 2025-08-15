Nos permite buscar binarios que tengan ciertos criterios que queramos.
Parametros:
- "/" Es la ruta desde donde queremos buscar, en este caso desde la raiz del sistema.
- -type Nos dice que queremos encontrar, "directorios = d" o "archivos = f".
- -perm Que tengan cierto privilegio.
- -group Podemos buscar por un [[Grupo]].
- -name Por nombre.
- -user Por usuario.
- -ls Podemos hacer que nos de los permisos.
- -executable Buscamos ejecutables.
Ejemplo de uso:
`find / -type f -perm -4000`.
Ejemplo mas complejo:
`find / -user root -perm -u=w 2>/dev/null`
Ejemplo de uso:
`find / -user root -executable -type f 2>/dev/null`
BUSQUEDA DE COINCSIDENCIAS:
`find / -name "lo que queremos"\*`
BUSQUEDA DE COINCSIDENCIAS 2:
`find / -name "lo que queremos"\*."extension"`
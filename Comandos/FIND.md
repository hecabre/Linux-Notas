Nos permite buscar binarios que tengan ciertos criterios que queramos.
Parametros:
- "/" Es la ruta desde donde queremos buscar, en este caso desde la raiz del sistema.
- -type Nos dice que queremos encontrar, "directorios = d" o "archivos = f".
- -perm Que tengan cierto privilegio.
Ejemplo de uso:
`find / -type f -perm -4000`.
Nos permite cambiar atributos especiales del sistema de archivos.
Tiene de parámetros:El comando `chattr` nos permite cambiar **atributos especiales** de archivos y directorios en sistemas de archivos compatibles como `ext2`, `ext3` y `ext4`.  
Estos atributos no son los permisos típicos de lectura/escritura/ejecución, sino propiedades adicionales que afectan cómo se comporta el archivo o directorio.
### Parámetros comunes

| Parámetro | Significado                                                                                         |
|-----------|---------------------------------------------------------------------------------------------------|
| `+`       | Agrega un atributo.                                                                                |
| `-`       | Quita un atributo.                                                                                 |
| `=`       | Establece el atributo exactamente a lo indicado.                                                   |
| `a`       | Append only — el archivo solo puede abrirse en modo de agregar.                                    |
| `i`       | Immutable — el archivo no puede modificarse, borrarse ni renombrarse.                              |
| `s`       | Secure deletion — el contenido se sobrescribe con ceros al borrar (en ciertos sistemas).           |
| `S`       | Sincronización — las escrituras al archivo se sincronizan inmediatamente en disco.                 |
| `u`       | Undeletable — permite recuperar el contenido tras un borrado.                                      |
| `d`       | No dump — excluye el archivo de backups con `dump`.                                                 |
| `A`       | No atime — no actualiza la marca de tiempo de último acceso.                                        |
| `g`       | Grupo heredado — en directorios, los nuevos archivos heredan el grupo del directorio (similar a SGID). |
| `t`       | No tail merge — desactiva la fusión de colas en archivos pequeños (optimización en ext2/ext3).     |

---

## Ejemplos de uso

Hacer un archivo **inmutable** y mostrar el proceso:
Ejemplo de uso:
`chattr +i -V "directorio`.
Ejemplo de uso de "s":
`chattr g+s`.

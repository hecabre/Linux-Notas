#### Que son:
Son [[Permisos Especiales]] que usa Linux para dividir los privilegios que tiene root en partes mas chicas.
#### Para que sirven:
- Las capabilities permiten dividir esos permisos de root en unos mas chicos y especificicos
- Un programa puede tener las capabilities para funcionar sin ser root.
#### Ver [[UID-GID Real]] Y [[UID-GID Efectivo]] para entender el usuario efectivo y grupo efectivo

#### Tipos:
| Capability           | Descripción                                       |     |
| -------------------- | ------------------------------------------------- | --- |
| CAP_CHOWN            | Sirve para cambiar el owner y grupo de archivos.  |     |
| CAP_DAC_OVERRIDE     | Ignora los permisos normales de los archivos.     |     |
| CAP_DAC_READ_SEARCH  | Ignora las restricciones de lectura y busqueda.   |     |
| CAP_FOWNER           | Cambiar el propietario de archivos y directorios. |     |
| CAP_FSETID           | Permite que archivos mantengan IDs de grupo.      |     |
| CAP_KILL             | Enviar signals a procesos o matar procesos.       |     |
| CAP_SETGID           | Cambiar el grupo efectivo de un proceso.          |     |
| CAP_NET_BIND_SERVICE | Abrir puertos por debajo del 1024.                |     |
| CAP_NET_ADMIN        | Configurar interfaces de red.                     |     |
| CAP_SYS_TIME         | Cambiar la fecha y hora del sistema.              |     |
| CAP_SYS_MODULE       | Cargar y descargar módulos del kernel.            |     |
| CAP_SYS_ADMIN        | Muchos privilegios administrativos generales.     |     |
| CAP_AUDIT_WRITE      | Escribir en el sistema de auditoria.              |     |
| CAP_MKNOD            | Crear nodos especiales del sistema.               |     |
| CAP_SYS_CHROOT       | Usar chroot para cambiar raiz del sistema.        |     |
| CAP_SETUID           | Cambiar el usuario efectivo de un proceso.        |     |


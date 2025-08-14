Crea una copia de seguridad de un archivo o directorio que nosotros le digamos.
Antes de hacer el comando debemos de entender que es el nivel.
El nivel basicamente cuando hiciste una backup, el nivel 0 es el primer nivel o lo mas elevado, es un respaldo completo, el primero.
Pero como vayan aumentando los numeros significa que hara un backup desde el anterior nivel, supongamos que tenemos un backup 1 del martes, y hacemos un backup 2 el jueves, solo copiara los cambios de ese inter del martes - jueves.
Se utiliza de la siguiente manera:
`sudo dump -0u -f /backup/sistema.bak /dev/sdKN`

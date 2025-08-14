Nos permite ver las [[Capabilities]] que tienen los archivos.
Ejemplo:
`getcap / -r 2>/dev/null`
Esto listaría las [[Capabilities]] empezando desde la raíz del sistema de forma re cursiva y los errores los manda al dev null.
Usar:
`getcap !$`
	El !$ es un atajo de historial que usa el ultimo argumento del comando anterior
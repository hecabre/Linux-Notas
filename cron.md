Nos permite ejecutar tareas automaticamente cada cierto tiempo especifico que nosotros definamos.
Puntos clave:
- Se ejecutan en segundo plano.
- Se configura mediante crontab, cada usuario puede tener su propio archivo crontab donde se define los comandos que se ejecutan
- Esta formada por 6 astericos, cada uno representa algo.
Si ponemos un `*/` significa que ejecutara cada cierto tiempo:
`*/20***` se ejecutaria cada 20 minutos.
Si tenemos `*2***` se ejecutaria cada minuto dentro de 2 AM A 2:59 PM
Si tenemos un 22*** se ejecutara a las 02:20 AM
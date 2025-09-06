Podemos usar nmap para escanear una red.
Los diferentes tipos de escaneos pueden hacer que los firewalls nos bloquee, entonces podemos usar ciertas tecnicas para evitar hacer un escaneo muy agresivo.
1. Podemos utilizar una plantilla con `-T(1 - 5)`, siendo 5 el mas agresivo.
2. Podemos mandar paquetes fragmentados con el parametro `-f`.
3. Podemos utilizar `-D`. Decoy, agrega una ip decoy junto a la que manda el paquete, de modo que los registros del objetivo solo aparezcan varias ips y no se sepa cual es la real.
Cuando enviamos paquetes, normalemnte se abre un puerto aleatorio para poder tramitar la comunicacion. Puede tener una lista blanca de los puertos que se tienen contemplados, no te deja saber si esta abierto el puerto, esto es porque asi estan configurados. Pero se puede cambiar el puerto de salida, para que por ejemplo, permite el puerto 22, mandemos la solicitud por el puerto 22.
Tambien se pueden modificar direcciones [[MAC]] con `--spoof-mac `
Self scan 
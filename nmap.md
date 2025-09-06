Podemos usar nmap para escanear una red.
Los diferentes tipos de escaneos pueden hacer que los firewalls nos bloquee, entonces podemos usar ciertas tecnicas para evitar hacer un escaneo muy agresivo.
1. Podemos utilizar una plantilla con `-T(1 - 5)`, siendo 5 el mas agresivo.
2. Podemos mandar paquetes fragmentados con el parametro `-f`.
3. Podemos utilizar `-D`. Decoy, agrega una ip decoy junto a la que manda el paquete, de modo que los registros del objetivo solo aparezcan varias ips y no se sepa cual es la real
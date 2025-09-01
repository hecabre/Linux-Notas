Tenemos una ip con 192.168.1.0/26 notacion [[CIDR]].
Significa que tiene /26 bits para la red y 6 para los hosts, deben de sumar 32.
Por ende la mascara de red seria 255.255.255.192.
El 192, sale de que tiene 8 bits el ultimo octal, tiene 6 para hosts, lo que significa que estan en 0 y otros 2 en 1, entonces eso en binario es 11000000, en decimal el numero seria 192, de ahi sale.
Para sacar los hosts tenemos que usar `2^6 = 64` pero debemos de restar 2, el Network Id y el Broadcast, entonces tendriamos 62 hosts.
Cuando tenemos un /26 el tamaño de cada subred se calcula asi: 256 - 192 = 64, en este caso es 192 por lo que sacamos de arriba de la submascara de red.
Ahora vamos con los saltos de las subredes, un salto de subred significa que abarca cierta cantidad de direcciones en el ultimo octeto, en este caso es 64, por el `2^6 = 64`
Entonces las direcciones ip validas serian:
1. 192.168.1.0 La direccion de la red o network id
2. 192.168.1.63 La direccion de broadcast.
3. 192.168.1.64
4. 192.168.1.127
5. 192.168.1.128
6. 192.168.1.191
7. 192.168.1.192
8. 192.168.1.255
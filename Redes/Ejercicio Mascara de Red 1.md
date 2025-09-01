Tenemos la ip 10.10.1.15/23.
Lo que significa que tenemos 23 para la red y 9 para hosts.
Calculemos los hosts seria `2^9 = 512`, pero debemos de quitar el [[Broadcast Address]] y el Network Id, entonces tenemos 510 hosts.
La mascara estaria en la [[Clase B]], lo que nos da una mascara de red 255.255.x.0, tenemos que sacar la mascara, en este caso llegaria hasta el 3 octal, entonces tendiramos en binario `11111111.11111111.11111110.00000000`, transformando a binario el 3 octal tendriamos que seria 254.
Ahora tendiramos 255.255.254.0.
Para el salto de subred usamos 256 - 254 = 2. Daremos saltos de 2 en dos en la red.
Entonces nos quedaria lo siguiente Network Id: 10.10.0.0 y 10.10.1.255.
Esto se puede ver en binario tendriamos  que la IP 10.10.1.15 en binario es `00001010.00001010.00000001.00001111` y la mascara es 255.255.254.0 en binario es `11111111.11111111.11111110.00000000`. Al hacer una compuerta AND tendriamos que: `00001010.00001010.00000000.00000000` en decimal 10.10.0.0, por eso el NETWORK ID es 10.10.0.0
Para el [[Broadcast Address]] se obtiene al poner todos los bits de hosts en 1.
Mascara de hosts la invertimos los 0 a 1. `00000000.00000000.00000001.11111111` Sumamos eso al Network ID y nos daria el [[Broadcast Address]], que en este caso seria 10.10.1.255.
Es un metodo de asignacion de direcciones IP que permite dividir una direccion IP en una parte que identifica la red y otra que identifica el host. Esto se hace por medio de una mascara de red, que se representa en notacion CIDR como una direccion IP base seguida de un numero que indica la cantidad de bits que corresponden a la red.
Con CIDR, se pueden asignar direcciones IP de forma mas precisa, lo que reduce la cantidad de direcciones IP desperdiciadas y facilita la administracion de la red.
El numero que sigue despues de la direccion IP base en la notacion CIDR se llama prefijo o longitud de prefijo, y representa el numero de bits en la mascara de red que estan 1.
Ejemplo:
Una direccion IP con un prefijo de /24 indica que los primeros 24 bits de la direccion IP corresponden a la red, mientras que los 8 bits restantes son los bits.
### Como calcularlo
Para calcular la cantidad de hosts disponibles en una red CIDR, se deben de contar el numero de bits en 0 en la mascara de red y elevar a la 2 ese numero. Esto se debe a que cada bit 0 en la mascara de red representa un bit.
Ejemplo: Una mascara de red 255.255.255.0 /24 tiene 8 bits en 0, lo que significa que hay 2^8 = 256 direcciones IP disponibles para los hosts de esa red.
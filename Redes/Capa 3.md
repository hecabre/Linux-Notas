Su funcion principal es encaminar los datos desde el origen hasta el destino, incluso si estan en redes diferentes.
Aqui es donde entran las direcciones logicas IP y los routers.
	1. Direccionamiento Logico: Cada dispositivo de la red necesita una IP unica en la red ([[IPV4]]/[[IPV6]]).
	2. Encaminamiento: Decide porque camino deben de viajar los paquetes para llegar a su destino. Lo hacen los routers.
	3. Fragmentacion y reensamblado: Si un paquete es demasiado grande para la red por donde pasa, la capa 3 lo divide en fragmentos y el receptor los vuelve a unir.
	4. Control de congestion / errores minimos: La capa 3 se asegura de que los paquetes puedan moverse correctamente, aunque no es tan confiable como TCP que esta en la capa 4.
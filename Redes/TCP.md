## Que es
Transmission Control Protocol.
Se usa sobre IP.
Funciona en la capa de transporte del modelo OSI.
Su trabajo es que los paquetes viajen de manera confiable y ordenada entre 2 computadoras.
### Como funciona
- Divide los datos en segmentos si es muy grande el paquete TCP lo divide en partes mas chicas.
- Enumera los segmentos cada pedazo lleva un numero para saber en que orden va.
- Si un segmento se pierde en el camino, el receptor avisa y el emisor lo reenvia.
- Regula la velocidad de envio para no saturar al receptor.
- Cada segmento tiene un checksum para identificar si fue danado.
#### 3-way handshake
Antes de enviar los datos, TCP establece una conexion confiable.
Se le llama 3-way handshake.
1. SYN -> el cliente le dice al servidor algo.
2. SYN-ACK -> el servidor responde.
3. ACK -> el cliente confirma
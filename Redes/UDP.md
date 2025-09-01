### User Datagram Protocol
Existen 65535 puertos. 
Es un protocolo de TRANSPORTE, como [[TCP]] y tambien se usa sobre IP.
Su caracteristica principal es que no garantiza la confibalidad ni orden.
Los envia tal cual sin preocuparse si llegan o no ni en que orden.
#### Caracteristicas principales.
1. Sin conexion
	- No hay handshake como en [[TCP]]
	- Simplemente envia los paquetes.
2. Rapido: Al no verificar errores ni confirmar recepcion, es mas ligero y rapido que TCP.
3. No garantiza entrega ni orden.
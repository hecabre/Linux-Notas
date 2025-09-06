## `-sS`
Es un escaneo o "half-open-scan". 
1. nmap manda un paquete SYN para iniciar la conexion TCP al puerto objetivo
2. Si la respuesta del puerto es SYN/ACK es un puerto abierto, nmap no completa el handshake corta con RST.
3. Si la respuesta es un RST es un puerto cerrado.
4. Ninguna / timeout es un puerto filtrado firewall bloquea
Se llama half-open-scan porque nmap jamas completa el handshake, lo que lo hace menos detectable que un escaneo TCP completo
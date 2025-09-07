Con nmap podemos usar scripts al momento de ejecutar un escaneo. Los scripts nos permiten obtener mas informacion.
Se utiliza el parametro `--script` de nmap.
### Categorias:
1. default: incluye una gran cantidad de scripts de reconocimiento basicos y utiles para la mayoria de escaneos.
2. discovery: se enfoca en descrubir informacion sobre la red, como la deteccion de hosts y dispostivos activos, y la resolucion de nombres de dominio.
3. safe: son scripts considerados seguros y que no realizan actividades invsaivas que pueden desencadenar una alerta de seguridad en la red.
4. instrusive: incluye escripts mas invasivos que pueden ser detectados facilmente por un Firewall, pero que pueden proporcionar informacion valiosa sobre vulnerabilidades y debilidades en la red.
5. vuln: se enfoca en la deteccion de vulnerabilidades y debilidades en los sistemas y servicios que se estan ejecutando en la red.
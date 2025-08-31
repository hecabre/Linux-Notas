Es un conjunto de protocolos para proteger las comunicaciones en redes IP (IPV4 e IPV6)
Funciona cifrando y autenticando los datos que viajan entre dos dispostivos.
Funciona en la capa 3 del modelo OSI, no como HTTPS que solo protege aplicaciones, sino que puede proteger cualquier trafico IP.
Usa 2 protocolos:
AH(Authentication Header):
- Solo identifica (comprueba identidad + integridad).
- No cifra los datos.
- Solo necesitas que nadie altero el paquete, pero no ocultar el contenido
ESP (Encapsulating Security Payload):
- Autentica y cifra.
- Oculta el contenido del paquete IP y asegura que nadie lo altere.
- 
Nos sirve para crear un usuario, siempre que creemos un usuario debemos de agregarle una bash y una carpeta home.
Se utiliza de la siguiente manera:
`useradd -s /ruta/bash -d /ruta/home "usuario"`
Podemos hacer que automaticamente cree la carpeta del Home al usuario con:
`useradd -s /ruta/bash -m "usuario"`
# COMO GENERAR SSH
Vamos a crear un par de llaves rsa una publica y una privada para que puedan conectarse mediante ssh a un servidor sin tener que estar escribiendo continuamente la clave.

-  Descargar el ssh server
  
#### sudo apt install openssh-server

-  El comando cd .ssh , cambiará tu ubicación actual a «ssh».
  
    ### cd .ssh/

- Este comando se usa para listar todos los archivos y directorios. 
  
### ls

-  Crea la clave utilizada para la autenticación de cliente y servidor. Por medio de este comando podemos crear un par de claves publica y privada 
   
ssh-keygen

por defecto se guarda en un archivo id_rsa pero podemos usar otro archivo si queremos y despues escribir una contraseña que se podria dejar en blanco pero es muy recomendable para que se cifre el contenido de la clave privida.


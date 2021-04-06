# COMO GENERAR SSH
Vamos a crear un par de llaves rsa una publica y una privada para que puedan conectarse mediante ssh a un servidor sin tener que estar escribiendo continuamente la clave.

-  Descargar el ssh server
  
    ### sudo apt install openssh-server

-  El comando cd .ssh , cambiará tu ubicación actual a «ssh».
  
    ### cd .ssh/

- Este comando se usa para listar todos los archivos y directorios.
  
    ### ls

- Por medio de este comando podemos crear un par de claves publica y privada 
   
    ### ssh-keygen

por defecto se guarda en un archivo id_rsa pero podemos usar otro archivo si queremos le damos enter y despues escribir una contraseña que se podria dejar en blanco pero es muy recomendable para que se cifre el contenido de la clave privida.

- Volvemos a colocar el comando ls 

   ### ls

Donde nos genero dos archivos uno llamado id_rsa y otro id_rsa.pub en el archivo punto pub es el que se va a usar para subir al servidor

- Por medio de este comando podemos examinar el contenido de este archivo

    ### cat id_rsa.pub

Lo que contiene es un conjunto de caracteres que es básicamente nuetra clave pública y tambien la palabra ssh y el nombre de usuario en el ordenador

- Luego enviar a la máquina en la que este iniciando sesión en este caso usaremos GITHUB

    ### GITHUB 

- Darle click en el usuario 
- Buscar settings y darle click
- En la parte izquierda darle click en SSH and GPG keys
- Darle click en New SSH key 
- Te mostrara una nueva ventana 
- En la parte title(titulo) es darle un nombre significativo
- En la parte key (llave) es pegar el contenido del archivo de la clave pública tal cual lo pegamos
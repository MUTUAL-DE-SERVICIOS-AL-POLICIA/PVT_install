# INSTALACION DE DOCKER y DOCKER ENGINE


## Instalación Docker

 Para la instalación de Docker siempre es bueno revisar la página oficial ya que podría haber cambios que no se contemplan en el siguiente documento, he incluso usted podrá escoger el sistema operativo que este usando  https://docs.docker.com/engine/install/

* Primero desinstalamos cualquier versión de docker en el equipo para instalar la más actual  y así evitar errores futuros.
Poner el siguiente comando en su carpeta de usuario

```sh
$ sudo apt-get remove docker docker-engine docker.io containerd runc 
```

* Con los siguientes 2 comandos actualizaremos los paquetes he instalaremos un nuevo paquete que nos permitirá el uso de un repositorio sobre HTTPS.
Poner el siguiente comando en su carpeta de usuario
```sh
$ sudo apt-get update
```
```sh
$ sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    gnupg \
    lsb-release
```
* Agregue la clave GPG oficial de Docker:
Poner el siguiente comando en su carpeta de usuario
```sh
$ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
```
* Utilice el siguiente comando para configurar el repositorio de manera estable
Poner el siguiente comando en su carpeta de usuario
```sh
$ echo \
  "deb [arch=amd64 signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu \
  $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
```
## Instalación Docker Engine

* Actualice el apt índice del paquete e instale la última versión de Docker Engine y containerd

Poner el siguiente comando en su carpeta de usuario
```sh
$ sudo apt-get update
```
Poner el siguiente comando en su carpeta de usuario
```sh
$ sudo sudo apt-get install docker-ce docker-ce-cli containerd.io
```
* Una vez instalado todo lo anterior verificar la versión de docker para ver si todo esta correcto en su instalación 
Poner el siguiente comando en su carpeta de usuario
```sh
$ docker-compose --version 
```

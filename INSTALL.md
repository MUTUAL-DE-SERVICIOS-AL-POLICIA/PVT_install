# PLATAFORMA VIRTUAL DE TRÁMITES

# Install

# Guia de instalacion de Ubuntu 

Requisitos minimos del sistema para Ubuntu 

- RAM de 2 GB
- Procesador dual core con frecuencia de  2 GHZ
- Disco duro desde 25 GB
- Unidad  de DVD o un puerto de USB 
- Acceso a internet

# Instalación

- Paso 1: Descargar el archivo ISO Ubuntu actualizado o utilizar CD 
- Paso 2: Arranque desde USB/DVD 
- Paso 3: Una vez iniciemos nuestro medio , nos saldrá el splash de Ubuntu...
- Paso 4: Nos preguntara que si queremos probar o instalar ubuntu ,seleccionamos nuestro idioma y damos click en instalar 
- Paso 5: Seleccionamos nuestra distribucion de Teclado
- Paso 6: Actualizaciones y otro software donde seleccionamos en instalar programas se terceros 
- Paso 7: Tipo de instalcion seleccionamos borrar disco e instalar Ubuntu 
- Paso 8: Damos aceptar o continuar para que empiece la instalcion 
- Paso 9: Seleccionamos nuestro pais 
- Paso 10: Configuramos nuetro Usuario y Contraseña 
- Paso 11: Y empezara la instalacion 
- Paso 12: Al finalizar nos pedira Reiniciar y aceptar 
```

* Clone the project

```sh
git clone https://github.com/MUTUAL-DE-SERVICIOS-AL-POLICIA/PVT.git
cd PVT
git fetch --tags
latestVersion=$(git describe --tags `git rev-list --tags --max-count=1`)
git checkout $latestVersion
```

* Install dependencies

```sh
composer run-script post-root-package-install
composer install
yarn
```

* Edit `.env` file with database credentials and established manteinance modes

* Generate keys and compile JS files

```sh
composer run-script post-create-project-cmd
yarn prod
```
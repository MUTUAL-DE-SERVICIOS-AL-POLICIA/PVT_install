# COMO GENERAR PUSH Y PULL
  
# _GENERANDO PUSH_

## Inicializar el git
```sh
git init
 ```
 ![](https://github.com/DiegooGutierrez123321/PVT_install/blob/main/Screenshot_Install/Captura%20de%20pantalla%20de%202021-04-07%2010-13-07.png?raw=true)
## Agregar a git el archivo pushPull.md
```sh 
git add pushPull.md
```
![](https://github.com/DiegooGutierrez123321/PVT_install/blob/main/Screenshot_Install/Captura%20de%20pantalla%20de%202021-04-07%2010-34-54.png?raw=true)
## Verificar que se añadio el archivo
```sh
git status
``` 
![](https://github.com/DiegooGutierrez123321/PVT_install/blob/main/Screenshot_Install/Captura%20de%20pantalla%20de%202021-04-07%2010-34-44.png?raw=true)
## Creando un destino con etiqueta
```sh
git commint -m "nuevas imagenes "
```
![](https://github.com/DiegooGutierrez123321/PVT_install/blob/main/Screenshot_Install/Captura%20de%20pantalla%20de%202021-04-07%2010-40-21.png?raw=true)
## Descargar al repositorio local de la rama "main" 
```sh
git push origin main
```
![](https://github.com/DiegooGutierrez123321/PVT_install/blob/main/Screenshot_Install/Captura%20de%20pantalla%20de%202021-04-07%2010-56-41.png?raw=true)
   
## DIRECCIONANDO A MUTUAL-DE-SERVICIOS-AL-POLICIA/PVT_install.git
```sh
git remote set-url main git@github.com:MUTUAL-DE-SERVICIOS-AL-POLICIA/PVT_install.git
```
![](https://github.com/DiegooGutierrez123321/PVT_install/blob/main/Screenshot_Install/Captura%20de%20pantalla%20de%202021-04-07%2011-04-52.png?raw=true)

## ESPECIFICA LOS EXTREMOS REMOTOS QUE OPERARAN LOS COMANDOS DE SINCRONIZACIÓN
```sh
git remote -v
```
![](https://github.com/DiegooGutierrez123321/PVT_install/blob/main/Screenshot_Install/Captura%20de%20pantalla%20de%202021-04-07%2011-05-02.png?raw=true)

# _GENERANDO EL PULL_
## Subiendo el archivo a la rama main del repositorio
```sh
git pull origin main
``` 
![](https://github.com/DiegooGutierrez123321/PVT_install/blob/main/Screenshot_Install/Captura%20de%20pantalla%20de%202021-04-07%2010-56-41.png?raw=true)
## Subiendo el archivo a la rama main principal
```sh
git pull origin main main
``` 
![](https://github.com/DiegooGutierrez123321/PVT_install/blob/main/Screenshot_Install/Captura%20de%20pantalla%20de%202021-04-07%2010-06-47.png?raw=true)

## Generar PULL REQUEST

![](https://github.com/DiegooGutierrez123321/PVT_install/blob/main/Screenshot_Install/Captura%20de%20pantalla%20de%202021-04-07%2011-35-52.png?raw=true)

## Descargar en el repositorio local los cambios hecho por otras ramas
```sh
git pull main main
``` 
![](https://github.com/DiegooGutierrez123321/PVT_install/blob/main/Screenshot_Install/Captura%20de%20pantalla%20de%202021-04-07%2010-06-47.png?raw=true)

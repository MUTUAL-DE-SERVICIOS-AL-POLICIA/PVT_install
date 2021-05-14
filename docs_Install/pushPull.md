# COMO GENERAR PUSH Y PULL
  
# _GENERANDO PUSH_

## Inicializar el directorio de git
```sh
git init
 ```

## Preparar un evento del archivo pushPull.md
```sh 
git add pushPull.md
```

## Verificar que se añadio el archivo
```sh
git status
``` 

## Crea el commit o evento con un nombre " nuevas imagenes"
```sh
git commint -m "nuevas imagenes "
```

## Subir al repositorio local de la rama "main" 
```sh
git push origin main
```

## ESTABLECIENDO UN ENLACE CON LA RAMA PRINCIPAL

## DIRECCIONANDO A MUTUAL-DE-SERVICIOS-AL-POLICIA/PVT_install.git
```sh
git remote set-url main git@github.com:MUTUAL-DE-SERVICIOS-AL-POLICIA/PVT_install.git
```


## VERIFICANDO LOS ESTADOS DE LAS RAMAS
```sh
git remote -v
```

# _GENERANDO EL PULL_
## Subiendo el archivo a la rama main del repositorio
```sh
git push origin main
``` 

## Subiendo el archivo a la rama main principal
```sh
git push origin main main
``` 


## Generar PULL REQUEST

![](https://github.com/DiegooGutierrez123321/PVT_install/blob/main/Screenshot_Install/Captura%20de%20pantalla%20de%202021-04-07%2011-35-52.png?raw=true)

## Descargar en el repositorio local los cambios hecho por otras ramas
```sh
git pull main main
``` 

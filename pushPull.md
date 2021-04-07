# COMO GENERAR PUSH Y PULL
  
# _GENERANDO PUSH_

## Inicializar el git
```sh
git init
 ```
 ![ ]()
## Agregar a git el archivo pushPull.md
```sh 
git add pushPull.md
```

## Verificar que se añadio el archivo
```sh
git status
``` 

## Creando un destino con etiqueta
```sh
git commint -m "subiendo archivo "
```

## Descargar al repositorio local de la rama "main" 
```sh
git push origin main
```

   
## DIRECCIONANDO A MUTUAL-DE-SERVICIOS-AL-POLICIA/PVT_install.git
```sh
git remote set-url main git@github.com:MUTUAL-DE-SERVICIOS-AL-POLICIA/PVT_install.git
```

## GENERANDO EL GIT CON ETIQUETA
```sh
git commint -m "subiendo archivo"
```
# _GENERANDO EL PULL_
## Subiendo el archivo a la rama principal main
```sh
git pull origin main main
``` 

## Descargar en el repositorio local los cambios hecho por otras ramas
```sh
git pull main main
``` 

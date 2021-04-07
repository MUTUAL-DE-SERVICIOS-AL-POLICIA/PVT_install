# COMO GENERAR PUSH Y PULL
  
# _GENERANDO PUSH_

## Inicializar el git
```sh
git init
 ```
 
## agregar a git el archivo pushPull.md
```sh 
git add pushPull.md
```

## Verificar que se añadio el archivo
```sh
git status
``` 

## creando un destino con etiqueta
```sh
git commint -m "subiendo archivo "
```

## descargar al repositorio local de la rama "main" 
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
## SUBIENDO EL ARCHIVO A LA RAMA PRINCIPAL MAIN
```sh
git pull origin main main
``` 

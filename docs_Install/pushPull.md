# COMO GENERAR PUSH Y PULL
  
# _GENERANDO PUSH_

## Inicializar el git
```sh
git init
 ```

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
git commint -m "nuevas imagenes "
```

## Descargar al repositorio local de la rama "main" 
```sh
git push origin main
```

   
## DIRECCIONANDO A MUTUAL-DE-SERVICIOS-AL-POLICIA/PVT_install.git
```sh
git remote set-url main git@github.com:MUTUAL-DE-SERVICIOS-AL-POLICIA/PVT_install.git
```


## ESPECIFICA LOS EXTREMOS REMOTOS QUE OPERARAN LOS COMANDOS DE SINCRONIZACIÓN
```sh
git remote -v
```

# _GENERANDO EL PULL_
## Subiendo el archivo a la rama main del repositorio
```sh
git pull origin main
``` 

## Subiendo el archivo a la rama main principal
```sh
git pull origin main main
``` 


## Generar PULL REQUEST

![](https://github.com/DiegooGutierrez123321/PVT_install/blob/main/Screenshot_Install/Captura%20de%20pantalla%20de%202021-04-07%2011-35-52.png?raw=true)

## Descargar en el repositorio local los cambios hecho por otras ramas
```sh
git pull main main
``` 

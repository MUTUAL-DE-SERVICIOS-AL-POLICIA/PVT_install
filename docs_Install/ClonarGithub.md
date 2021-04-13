# PLATAFORMA VIRTUAL DE TRÁMITES

## Pasos para clonar un proyecto en github

Requisitos mínimos

- Tener instalado git en el computador
- Tener creada una cuenta de github
- Tener el link del proyecto a clonar
- Tener la llave SSH Generada
- Acceso a internet

## Pasos

1. Hacer un fork del repositorio principal donde se encuentra el proyecto, a nuestro propio repositorio para así tener la copia del mismo.

2. Cuando ya tenemos el repositorio, clonamos el proyecto en nuestro computador en la carpeta que elijamos con el comando:

```sh
 git clone <url copiado de code-ssh de github>
```
## Preparar el git
* Preparamos el git para tener bien dirigido donde vamos a subir y bajar los cambios que se hagan en el proyecto.

Todos estos comandos deben de escribirse en la carpeta donde se creo el proyecto.

Para ello primero añadimos al git el usuario y el email de github con los comados 
```sh
git config –global user.name “nombre_de_usuario_github”
git config –global user.email “correo_con_el_que_se_creo_la_cuenta_github”
```
* Ahora añadimos el url del proyecto principal para descargar los cambios directamente. Con el comando
```sh
 git remote add upstream <url copiado de code-ssh de github del proyecto original>
```

Con estos preparativos ya podremos subir y bajar cambios de github


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
3. Ingresamos a la carpeta del proyecto y abrimos el proyecto con el comando: 

```sh
 code .
```

## Preparar el git
* Preparamos el git para tener bien dirigido donde vamos a subir y bajar los cambios que se hagan en el proyecto.

Todos estos comandos deben de escribirse en la terminal del proyecto.

Para ello primero añadimos al git el usuario 
```sh
git remote -v

* Ahora añadimos el url del proyecto principal para descargar los cambios directamente. Con el comando
```sh
 git remote add upstream <url copiado de code-ssh de github del proyecto original>
```
Y volvemos a escribir el comando
```sh
git remote -v
```

Con estos preparativos ya podremos subir y bajar cambios de github


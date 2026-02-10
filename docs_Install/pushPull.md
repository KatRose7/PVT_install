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

## Agregar todo
```sh
git add .
``` 
## Verificar que se añadio el archivo
```sh
git status
``` 

## Crea el commit o evento con un nombre " nuevas imagenes"
```sh
git commit -m "nuevas imagenes"
```

## Subir al repositorio remoto (GitHub)  de la rama "main" 
```sh
git push origin main
```

## ESTABLECIENDO UN ENLACE CON LA RAMA PRINCIPAL

## DIRECCIONANDO A MUTUAL-DE-SERVICIOS-AL-POLICIA/PVT_install.git
```sh
git remote set-url origin git@github.com:MUTUAL-DE-SERVICIOS-AL-POLICIA/PVT_install.git
```


## VERIFICANDO LOS ESTADOS DE LAS RAMAS
```sh
git remote -v
```

# _GENERANDO EL PULL_
## Verificar el estado del repositorio
```sh
git status
``` 

## Descargar cambios desde GitHub
```sh
git pull origin main
``` 


## Generar PULL REQUEST

![](https://github.com/DiegooGutierrez123321/PVT_install/blob/main/Screenshot_Install/Captura%20de%20pantalla%20de%202021-04-07%2011-35-52.png?raw=true)

## El Pull Request se genera desde la plataforma web de GitHub despues de subir los cambios al repositorio remoto.

## Luego ingresar a GitHub y seleccionar  Create Pull Request.

## Descargar cambios en el repositorio local.

```sh
git pull origin main
``` 


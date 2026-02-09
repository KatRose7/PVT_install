# INSTALACION DE DOCKER 


## Instalación Docker

Para instalar Docker desde los repositorios oficiales de Ubuntu

* Primero desinstalamos cualquier versión de docker en el equipo para instalar la más actual  y así evitar errores futuros.
Poner el siguiente comando en su carpeta de usuario

```sh
$ sudo apt-get remove docker docker-engine docker.io containerd runc 
```

* Con el siguiente comando instalaremos: Docker Engine (Motor que ejecuta contenedores), Docker CLI (Comandos como docker run, docker ps), Servicio systemd docker.service(Arranca automáticamente).
Poner el siguiente comando en su carpeta de usuario

```sh
$ sudo apt install docker.io
```

* Una vez instalado lo anterior verificar la versión de docker para ver si todo esta correcto en su instalación 
Poner el siguiente comando en su carpeta de usuario

```sh
$ docker compose --version 
```
* Para confirmar que el servicio está activo

```sh
$ systemctl status docker
```

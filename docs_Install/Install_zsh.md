
![](https://raw.githubusercontent.com/IvetteCh/PVT_install/main/screenshot_Install/zsh_logo.webp)


# Cómo instalar ZSH en Ubuntu

 Es un programa que funciona como interprete de comandos, toma las ordenes que escribimos en la terminal y se las da al sistema operativo, también es un completo lenguaje de consola, podemos escribir scripts (.sh) y el shell los puede ejecutar. 

 ### - Primero actualice la caché del repositorio de paquetes de su sistema operativo Ubuntu 24.04 LTS con el siguiente comando:

      $ sudo apt update

![](https://raw.githubusercontent.com/IvetteCh/PVT_install/main/screenshot_Install/instalacion1.png)

  La caché del repositorio de paquetes debe actualizarse.  

### - Ahora instale ZSH con el siguiente comando:

     $ sudo apt install zsh

 ![](https://raw.githubusercontent.com/IvetteCh/PVT_install/main/screenshot_Install/instalacion2.png )

Ahora presione [S] y luego presione continuar.

![](https://raw.githubusercontent.com/IvetteCh/PVT_install/main/screenshot_Install/instalacion3.png)

### - Se debe cambiar ZSH como shell por defecto, con el siguiente comando

     $ chsh -s $(which zsh)


### - Ahora que el shell ZSH está instalado, puede verificar si ZSH funciona con el siguiente comando:

      $ zsh --version

 ![](https://raw.githubusercontent.com/IvetteCh/PVT_install/main/screenshot_Install/instalacion4.png)

Como puede ver, ZSH está funcionando correctamente.
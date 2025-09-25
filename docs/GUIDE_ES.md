# plurios-live (Español)

Esta guía es simple de seguir. Lo único que se necesita seguir estos 4 pasos:

- [Instalar dependencias](#1-dependencias)
- [Descargar plurios-live](#2-descargar-plurios-live)
- [Descargar la imagen ISO de Ubuntu Cinnamon LTS](#3-descargar-imagen-ubuntu-cinnamon-lts)
- [Ejecutar plurios-live](#4-ejecutar-plurios-live)

### 1. Instalar dependencias

Las siguientes dependencias son paquetes que utiliza plurios-live para su construcción:

    coreutils
    xorriso
    findutils
    rsync
    squashfs-tools
    curl
    wget
    git


> Nota: Es posible que aún falte registrar algunas dependencias.

Instalación de las dependencias:


    apt update 
    apt install -y coreutils xorriso findutils rsync squashfs-tools wget git


### 2. Descargar plurios-live

    git clone https://github.com/FershoUno/plurios-live.git
    cd plurios-live


### 3. Descargar imagen Ubuntu Cinnamon LTS

Se recomienda descargar la imagen 24.04 LTS desde la página oficial:

    https://ubuntucinnamon.org/


### 4. Ejecutar plurios-live

Instrucciones para ejecutar:

    bash plurios-live ubuntucinnamon-24.04.2-desktop-amd64.iso

> La imagen ISO se creará en el directorio `workspace/iso/`


## ¿Donde descargar?

las imagenes construidas de PluriOS se encuentran publciadas en el sitio web oficial: 

[https://plurios.openit.dev/](https://plurios.openit.dev/)

### 4. Ejecutar plurios-live

Como ejecutar:

    bash plurios-live ubuntucinnamon-24.04.2-desktop-amd64.iso

> La imagen ISO se creará en el directorio `workspace/iso/`


### Importante

Esta herramienta se encuentra en una fase inicial de desarrollo y se irá mejorando con el tiempo.

# plurios-live (English)

This guide is simple to follow. All you need to do is follow these four steps:

- [Install dependencies](#1-dependencies)
- [Download plurios-live](#2-download-plurios-live)
- [Download the Ubuntu Cinnamon LTS ISO image](#3-download-ubuntu-cinnamon-lts-image)
- [Run plurios-live](#4-run-plurios-live)

### 1. Install dependencies

The following dependencies are packages used by plurios-live for building the ISO:

    coreutils
    xorriso
    findutils
    rsync
    squashfs-tools
    wget
    git

> Note: Some dependencies may still need to be added.

Install the dependencies:


    apt update 
    apt install -y coreutils xorriso findutils rsync squashfs-tools wget git


### 2. Download plurios-live

    git clone https://github.com/FershoUno/plurios-live.git
    cd plurios-live

### 3. Download Ubuntu Cinnamon LTS image

It is recommended to download the 24.04 LTS image from the official website:

    https://ubuntucinnamon.org/

### 4. Run plurios-live

How to execute:

    bash plurios-live ubuntucinnamon-24.04.2-desktop-amd64.iso

> The ISO image will be created in the directory: `workspace/iso/`


### Important

This tool is in its early development stage and will be improved over time.

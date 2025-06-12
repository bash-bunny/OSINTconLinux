# Modulo 1: Instalacion & Configuracion de Kali Linux

Completa instalación de Kali Linux usando VirtualBox para la realización del curso, así como una guía del manejo de herramientas en Linux:
- Actualización del sistema operativo
- Manejo de Ficheros
- Regex

## Vídeos

### Módulo 1.1: Instalación de Kali Linux

[![Módulo 1.1: Instalación de Kali Linux](https://img.youtube.com/vi/vALesUdqTTg/0.jpg)](https://www.youtube.com/watch?v=vALesUdqTTg)

### Módulo 1.2: Comandos Básicos

[![Módulo 1.2: Comandos Básicos](https://img.youtube.com/vi/HEHeFDw5e7M/0.jpg)](https://www.youtube.com/watch?v=HEHeFDw5e7M)

### Módulo 1.3: Comandos Avanzados

[![Módulo 1.3: Comandos Avanzados](https://img.youtube.com/vi/kYt5_DrecYo/0.jpg)](https://www.youtube.com/watch?v=kYt5_DrecYo)

### Módulo 1.4: Anexo - Edición de Ficheros

[![Módulo 1.4: Anexo - Edición de Ficheros](https://img.youtube.com/vi/yFUUlofA7rw/0.jpg)](https://www.youtube.com/watch?v=yFUUlofA7rw)

## Recursos

- VMWare: https://www.vmware.com/products/workstation-player.html
- Virtualbox: https://www.virtualbox.org/wiki/Downloads
- Kali Linux: https://www.kali.org/get-kali/#kali-virtual-machines
- Instalacion Kali Linux iso: https://www.kali.org/docs/installation/hard-disk-install/
- Otros Sistemas Operativos:
    - Debian: https://www.debian.org/download
    - Arch: https://archlinux.org
    - Parrot OS: https://www.parrotsec.org
    - BlackArch: https://www.blackarch.org
- Shells:
    - ZSH: https://wiki.archlinux.org/title/Zsh
        - OhMyZsh: https://ohmyz.sh
    - Fish: https://fishshell.com
- Permisos ficheros Linux:
    - https://aprendolinux.com/como-leer-cambiar-los-permisos-en-linux/
- Regex:
    - https://regex101.com/

## Comandos

- Comprobar el hash de un fichero con powershell

```powershell
Get-FileHash .\nombre_fichero
```

- Comandos basicos de Linux

```bash
# Actualizar el listado de paquetes
sudo apt update
# Actualizar los paquetes instalados
## Añadir -y al final permite que no te pida confirmacion
sudo apt upgrade -y

# Actualizar la base de datos de locate
sudo updatedb

# Descarga los ficheros html de una web de manera recursiva
wget --accept html --mirror --page-requisites --convert-links --backup-converted --no-parent https://example.com
# Clonar una pagina para verla offline
wget -mkEpnp https://example.com
```

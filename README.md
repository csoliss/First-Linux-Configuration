# English
# FLC
First Linux Configuration (FLC) is a python script  that looking for load all package that I need in my Linux
## Introduction
Since I started in the world of linux (over ten years), I've always had problems with the distribution of shift and was to reinstall the whole system, but I resented the idea of revisiting what were the packages used. this idea was born this project, intended to have a program that I will configure the operating system as it was in the beginning, I hope you like this little script
## Tutorial
Download the script file:
```sh
   $ wget https://raw.githubusercontent.com/csoliss/FirstLinuxConfiguration/master/FirstLinuxConfiguration.py
```
Download de Config file:
```sh
   $ wget https://raw.githubusercontent.com/csoliss/FirstLinuxConfiguration/master/config_file_FLC.conf
```
Or Download the complete folder
```sh
   $ wget https://github.com/csoliss/FirstLinuxConfiguration/archive/master.zip
```
NOTE: You should save the config file

* Usage:
```sh
   $ sudo python3 FirstLinuxConfig.py config_file [options]
```
* Options:
   - **-y**        Answer "yes" to all questions
   - **-v**        View standart output
   - **--help**    Display the help
* Examples:
```sh
    $ sudo python3 FirstLinuxConfig.py config_file -v
    $ sudo python3 FirstLinuxConfig.py config_file -y
    $ sudo python3 FirstLinuxConfig.py config_file -v -y
    $ sudo python3 FirstLinuxConfig.py config_file -y -v
    $ sudo python3 FirstLinuxConfig.py --help
    $ python3 FirstLinuxConfig.py --help
```
#Español
# FLC
First Linux Configuration (FLC) es un scrypt en python que busca carga e instalar todos los paquetes que necesito en mi linux
## Introducción
Desde que empecé en el mundo de linux (hace más de diez años), siempre he tenido problemas con la distribución de turno y debia volver a instalar todo el sistema, pero me molestaba la idea de volver a revisar cuales eran los paquetes que usaba. con esta idea nacio este proyecto, cuya intención es tener un programa que me configurara el sistema operativo tal y como lo tenía en un principio, espero que les guste este pequeño script
## Instalación
Descarga fcl.py y config_file.txt
## Tutorial
* Uso:
```sh
   $ sudo flc.py config_file [options]
```
* Opciones:
   - **-y**        Responde si a todas las opciones
   - **-v**        Permite ver la salida estandar
   - **--help**    Para mostar la ayuda
* Ejemplos:
```sh
    $ sudo flc.py config_file -v
    $ sudo flc.py config_file -y
    $ sudo flc.py config_file -v -y
    $ sudo flc.py config_file -y -v
    $ sudo flc.py --help
    $ flc.py --help
```


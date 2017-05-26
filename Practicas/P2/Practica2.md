# SWAP #
## Práctica 2: Clonar la información de un sitio web ##
### Alumnos: ###

#### Gregorio Vidoy Fajardo  ####

#### Carmen Bueno Ben Boubker  ####


### CREAR UN TAR CON FICHEROS LOCALES EN UN EQUIPO REMOTO ###

Una vez que sabemos la dirección IP de las dos máquinas, vamos a probar a enviar un fichero tar con el contenido de /var/www de la máquina 2 a la máquina 1, cuya dirección IP es 172.16.212.128, para ello usaremos el comando que se nos indica en el guión de la práctica 2, en su segundo apartado.

![Imagen][1]
*FIgura 1.1: Envío de un tgz de la máquina virtual 1 a la máquina virtual 2*

Una vez se ha realizado la transferencia de los archivos en la máquina virtual 2 aparecerá un tgz, el cual contendrá el contenido de /var/www/ de la primera máquina.

### INSTALAR LA HERRAMIENTA RSYNC ###


Ahora vamos a clonar el contenido de /var/www/ de la máquina 1 a la máquina 2, para ello haremos uso de rsync, debemos de instalarlo con sudo apt-get install rsync, pero en este caso, en mis dos máquinas virtuales ya se encuentra instalado de forma predeterminada, igualmente procedimos a instalarlo para asegurarnos de ello.

![Imagen][2]









[1]: Imagenes/envioTgz.png
[2]: Imagenes/instalacionRsync.png

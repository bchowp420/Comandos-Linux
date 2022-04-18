# Comandos-Linux
Este es un repositorio de comandos de Linux del curso de SO
| Comandos | Descripcion | Ejemplo |
| -------- | ----------- |-------- |
| ps-aux   | Revisa el status de los procesos activos en el sistema | ps-aux muestra los procesos de X usuario |
| top      | Muestra un resumen de la informacion del sistema y la lista de procesos o hilos que estan actualmente administrador por el kernel | ![image](https://user-images.githubusercontent.com/98858890/154727171-81997a45-be4d-4d7b-bc64-de56425727a2.png) | 
| htop     | Permite al usuario monitorear los recursos vitales en tiempo real. Es un comando mas reciente que top | ![image](https://user-images.githubusercontent.com/98858890/154727409-f5fc2258-2a13-4b00-96f3-eaac41eb954e.png)|
|pstree | muestra el arbol de procesos de linux | ![image](https://user-images.githubusercontent.com/98858890/154728220-6f0269c5-080a-4e93-a5ce-36d660279607.png)|
|Sudo apt install ssh-server | Se utiliza para hacer conexiones SSH |  |
| whoami | Muestra el nombre de usuario | |
| df -hT | Muestra el sistema de archivos que se utiliza |  |
| touch | Crea un archivo en blanco | |
| chmod  | para concender permisos | |
| chown| para dar posesion de un archivo | chown mint test
| mv | mover archivos a otra ubicacion | mv archivo.txt Desktop |
| mkdir | Crear directorio | mkdir Weerk11 |
| rm | Eliminar | rm archivo.txt
| rm-Rf : | Eliminar todos los directorios apartir del directorio ingresado | rm-Rf :Desktop  |
|stat | Brinda la fecha de creacion o ultimo acceso | stat archivo1.txt |
| du -h | brinda el tamaño del archivo | du -h archivo.txt |
|ls -l | lista los permisos de cada directorio y archivo | ls -l |
| ls -li | para ver el numero de inodo para poder hacer uso de los hard links | ls -li |
|sudo su| para ingresar como root | sudo su|
|kill -9 PID  | Para matar un proceso en este caso PID | kill -9 PID |
|grep -r | para buscar caracteres de forma recursiva | grep -r log $HOME |
| ln + archivo original + ruta del enlace| comando utilizado para hacer enlaces entre ficheros | ln archivo1.txt $HOME
| ln -s ruta del archivo original + ruta del archivo de origien | para crear enlaces suaves | ln -s /var/log /home/myuser/archivo.log|
| crontab -e  | se utiliza para entrar al archivo crontab y poder setear la hora de ejecucion de nuestro script por medio de cron| cron -e |
|crontab -l | Se enlista las tareas que debe de realizar cron | crontab -l |
| m h dom mon dow user command | 15 10 *** bchowp420 /home/usuario/scripts/actualizar | m = minuto - dom = dia del mes - dow = el dia de la semana del 0 a 7 - command= es la ruta del script

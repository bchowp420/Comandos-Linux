# Comandos-Linux
Este es un repositorio de comandos de Linux del curso de SO
| Comandos | Descripcion | Ejemplo |
| -------- | ----------- |-------- |
| ps-aux   | Revisa el status de los procesos activos en el sistema | ps-aux muestra los procesos de X usuario |
| top      | Muestra un resumen de la informacion del sistema y la lista de procesos o hilos que estan actualmente administrador por el kernel | ![image](https://user-images.githubusercontent.com/98858890/154727171-81997a45-be4d-4d7b-bc64-de56425727a2.png) | 
| htop     | Permite al usuario monitorear los recursos vitales en tiempo real. Es un comando mas reciente que top | ![image](https://user-images.githubusercontent.com/98858890/154727409-f5fc2258-2a13-4b00-96f3-eaac41eb954e.png)|
|pstree | muestra el arbol de procesos de linux | ![image](https://user-images.githubusercontent.com/98858890/154728220-6f0269c5-080a-4e93-a5ce-36d660279607.png)|
|Sudo apt install ssh-server | Se utiliza para hacer conexiones SSH | Sudo apt install ssh--server |
| whoami | Muestra el nombre de usuario | ![whoami](https://user-images.githubusercontent.com/98858890/164571811-dee91ae1-7f8f-4870-8f5a-2d4fa972d3bd.PNG) |
| df -hT | Muestra el sistema de archivos que se utiliza |![df -hT](https://user-images.githubusercontent.com/98858890/164572433-2f41f439-7d0e-4e49-a09a-eb5cb864788e.png) |
| touch | Crea un archivo en blanco | touch prueba.txt |
| chmod  | para concender permisos | chmod +x prueba.txt |
| chown| para dar posesion de un archivo | chown mint test |
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
| m h dom mon dow user command | 15 10 *** bchowp420 /home/usuario/scripts/actualizar | m = minuto - dom = dia del mes - dow = el dia de la semana del 0 a 7 - command= es la ruta del script|
|sudo systemctl start openvpn-server@server.service | Run the openvpn |
| sudo cp [certicateName] /etc/openvpn/client.conf | Copiar el certificado en la carpeta cliente.conf| sudo cp ClienteServer.ovpn /etc/openvpn/client.conf |
|  sudo openvpn --client --config /etc/openvpn/client.conf | Utilizado para conectarse al servidor VPN |  sudo openvpn --client --config /etc/openvpn/client.conf
| curlftpfs 10.8.0.3 /media/ftpAndromeda/ -o user=bchowp420,allow_other | para montar la unidad de red | 

| For NEXTCLOUD |
| sudo mysql-uroot -p | Para ingresar al command prompt de MariaDB |
|Docker Commands|
|---------------|
|Docker ps -a | para ver el estado y ID del contenedor asi como cuando se creo, etc.| 
|Docker history imagen | para observar las capas del docker
|Docker info| Para saber el driver de almacenamiento que se esta utilizando| 
|Docker images | observar nuestras imágenes y tags y el Image ID| 
|Docker pull imageName | para instalar imágenes de docker
|Docker network ls | lista nuestras interfaces de red en docker
|Sudo ipconfig -s | para ver las diferentes interfaces que posee el equipo
|Sudo ipconfig docker0 | interfaz docker 0 que muestra informacion direccion ip,etc.
|Sudo ipconfig interfaz name| muestra la informacion de la interfaz especificada | 
|Docker network create --driver bridge name | Para crear nueva interfaz en modo bridge
Docker pull [imagen]:version | para descargar una imagen de docker
Docker run [image]  | Ejecutar una imagen de docker
Docker run –ti [image name]  | Ejecutar una imagen de docker con una terminal interactivca
docker run –ti - -rm [image] [parametros como uname - bash - ls ] | para que el contenedor se borre automaticamente y no gaste espacio en disco despues de su uso
Docker ps | para ver cuales contenedores tenemos activos y corriendo
Docker ps -a | se observan todos los contenedores incluso los que estan en estado exited.
Docker run -d [image] | para crear un contenedor y que este corriendo en segundo plano con un daemon.
run –d –name nombre_del_contenedor | para setear el nombre del contenedor
docker rm [id or name] | Se utiliza para borrar un contenedor 
docker stop [ID] | utilizado para detener un contenedor antes de borrarlo
docker rmi [imageName:version] | utilizado para borrar imágenes de docker
vim dockerfile | utilizado para crear y editar el dockerfile
docker build –t [RepositoryName][TagName] | Para compilar el dockerfile creado. El nombre del repositorio y el tag son personalizados
Docker history | ver la cantidad de capas de un dockerfile
Rm -rf /var/lib/apt/lists/ | para borrar la cache de los paquetes 




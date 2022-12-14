# <text style = "display:block; text-align: center">**Reconocimiento Del Sistema**</text>

| # | **Comandos** | **Descripcion**| **Imagen**
|-- |:--:|:--:|:--:| 
| 1 |**uname -a**| El comando (sudo su) permite a los Se mostrará el nombre del kernel o núcleo del sistema operativo. Pero este comando dispone del siguiente conjunto de opciones, que permiten obtener más información del sistema Linux donde se ejecute: <b>«a minúscula» / –all </b>, Si se añade al comando <b>uname</b> cualquiera de estas dos opciones, se mostrará toda la información técnca del sistema, que puede mostrar el comando uname: <b>uname -a;  uname --all</b>| ![R.Sis](img_Sis/img01.png) | 
| 2 | **cat /proc/sys/kernel/hostname** | Con el comando <b>“cat”</b> podemos visualizar la información contenido en ficheros. Por lo que lo utilizaremos para ver el contenido del fichero <b>“/proc/sys/kernel/hostname»</b>.| ![R.Sis](img_Sis/img02.png)|
| 3 | **echo "$USER"** | <b>echo</b> también puede mostrar variables. <b>$USER</b> es una variable de shell que contiene su nombre de usuario.</cite>| ![R.Sis](img_Sis/img03.png)|
| 4 | **pwd** | El comando ls es una utilidad de El comando pwd significa “directorio de trabajo de impresión” y es un comando de Linux simple pero útil. Este comando se usa para mostrar el nombre de su directorio actual, lo que puede ser útil al navegar por el sistema de archivos.| ![R.Sis](img_Sis/img04.png)|
| s | **ifconfig wifi0** | | ![R.Sis](img_linux/img05.png)|
| 6 | **ip route - grep default** | <b>ip route</b> nos permite ver y configurar la tabla de enrutamiento del sistema operativo, pero también nos permitirá ver y configurar todas las tablas de enrutamiento que nosotros creemos en el propio sistema operativo. Debemos tener en cuenta, que por cada entrada en la tabla de enrutamiento, debemos tener la dirección de red, máscara y el gateway, además, también podríamos configurar el ToS (tipo de servicio).| ![R.Sis](img_Sis/img06.png)|
| 7 | **curl ifconfig.me** | <b>ifconfig.me</b> Es un servicio web que muestra información sobre tu conexión, incluida la dirección IP, el nombre de host y la cadena de agente de usuario.| ![R.Sis](img_Sis/img06.png)|
| 8 | **ping -ac 10 8.8.8.8** | Utiliza el comando <b>ping</b> con la opción <b>-a</b> y la dirección IP del ordenador de destino para averiguar el nombre de host del destino. Se muestra el nombre del ordenador junto con la estadística Ping en el terminal. Con la bandera <b>-c</b> (recuento), puede especificar el número de pings que desea realizar.| ![R.Sis](img_Sis/img08.png)|
| 9 |**ping -c 10 1.1.1.1** | Con la bandera <b>-c</b> (recuento), puede especificar el número de pings que desea realizar.| ![R.Sis](img_Sis/img09.png)|
| 10 |**route -n** | Mostrar la tabla de enrutamiento en forma numérica completa.| ![R.Sis](img_Sis/img10.png)|
| 11 | **route.exe print** | muestra la configuración de enrutamiento de la red en el host.| ![R.Sis](img_Sis/img11.png)|
| 12 | **tracert.exe 8.8.8.8** | Ofrece una solución simple para seguir de cerca la pista a determinados paquetes de datos. Con base en estos resultados, el usuario puede diagnosticar qué estaciones individuales han enviado paquetes con un destino previsto, y dónde han surgido dificultades. Así, es posible identificar desvíos complicados o fallos en el router para comenzar con la solución de problemas.| ![R.Sis](img_Sis/img12.png)|
| 13 | **arp.exe -a** | Arp.exe es un proceso del comando Address Resolution Protocol. Estos servidores sirven para transferir capas de Internet a direcciones de capa de enlace. El archivo es esencial para rastrear las direcciones mac del usuario solo cuando la dirección IP es conocida. Adicionalmente, el archivo ayuda a comunicar dos ordenadores conectados a la misma red LAN. El archivo también puede ser usado para fines estadísticos. El comando –a funciona en cualquier sistema. Al introducirlo aparece una lista de combinaciones de direcciones para todas las interfaces de red que utilizan ARP. Además, también se puede obtener información acerca de si una entrada se ha generado de forma dinámica o de si se ha creado de forma manual.| ![R.Sis](img_Sis/img13.png)|
| 14 | **netstat.exe -nt** | Los archivos TCP/IP Netstat Command, tales como NETSTAT.EXE, se consideran un tipo de archivo Win32 EXE (Aplicación ejecutable), el comando <b>netstat.exe</b> con la opcion <b>-n</b> nos muestra una visualización numérica de direcciones y números de puerto y con la opcion <b>-t</b> nos muestra el estado de la descarga (descarga TCP para aliviar el procesador principal) de las conexiones activas, combinadas nos dara el siguiente resultado.| ![R.Sis](img_Sis/img14.png)|
| 15 | **netstat.exe-nat - grep -c 'ESTABLISHED'** | | ![R.Sis](img_Sis/img15.png)|
| 16 | **netstat.exe -nao - grep 'LISTEN' > cat ports_up.txt** | | ![R.Sis](img_Sis/img16.png)|
| 17 |**cat ports_up.txt** || ![R.Sis](img_Sis/img17.png)|ç

# Mas Información
* [CÓMO SABER LA DIRECCIÓN IP PÚBLICA EN LINUX][1_0]
* [¿Qué es PING y cómo usarlo?][1_1]
* [Cómo utilizar el comando Ping en Windows][1_2]
* [COMANDO ROUTE EN LINUX CON EJEMPLOS][1_3]
* [¿Qué es Traceroute (tracert)?][1_4]

[1_0]:https://esgeeks.com/direccion-ip-publica-en-linux/#:~:text=curl%20-s%20http%3A%2Fifconfig,dirección%20IP%20pública%20mediante%20curl.&text=ifconfig.me%20es%20un%20servicio,cadena%20de%20agente%20de%20usuario.

[1_1]:https://geekflare.com/es/what-is-ping-and-command-examples/

[1_2]:https://www.ionos.es/digitalguide/servidores/herramientas/comando-ping/

[1_3]:https://es.acervolima.com/comando-route-en-linux-con-ejemplos/#:~:text=El%20comando%20route%20en%20Linux,de%20enrutamiento%20de%20IP%20%2F%20kernel.

[1_4]:https://www.ionos.es/digitalguide/servidores/herramientas/usa-traceroute-y-sigue-la-pista-de-tus-paquetes-de-datos/
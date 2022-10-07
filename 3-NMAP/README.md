<h1><div align=center><img src="img/img01.jpg"></div></h1>

# <text style = "display:block; text-align: center"> <b>NMAP</b>

<text style = "display:block; text-align: justify"> 

Nmap es un programa de código abierto que sirve para efectuar rastreo de puertos escrito originalmente por Gordon Lyon (más conocido por su alias Fyodor Vaskovich​) y cuyo desarrollo se encuentra hoy a cargo de una comunidad. Fue creado originalmente para Linux aunque actualmente es multiplataforma. Se usa para evaluar la seguridad de sistemas informáticos, así como para descubrir servicios o servidores en una red informática, para ello Nmap envía unos paquetes definidos a otros equipos y analiza sus respuestas.

Este software posee varias funciones para sondear redes de computadores, incluyendo detección de equipos, servicios y sistemas operativos. Estas funciones son extensibles mediante el uso de scripts para proveer servicios de detección avanzados, detección de vulnerabilidades y otras aplicaciones. Además, durante un escaneo, es capaz de adaptarse a las condiciones de la red incluyendo latencia y congestión de la misma.

# Instalacion NMAP

<text style = "display:block; text-align: justify"> 

Nos dirigimos al siguiente enlace: https://nmap.org/download.html#windows

Seleccionamos donde indica la siguiente imagen para descargar la versión estable más reciente:

<div align=center><img src="img/img02.jpg"></div>

Una ves descargado procedemos con la instalación:

1- Ejecutamos el archivo descargado
<div align=center><img src="img/img03.png"></div>

2- Aceptamos los terminos de licencia
<div align=center><img src="img/img04.png"></div>

3- Le damos a Next
<div align=center><img src="img/img05.png"></div>

4- Seleccionamos la ruta de instalación y continuamos dando click en "Install"
<div align=center><img src="img/img06.png"></div>

5- Nos aparecera la siguiente imagen, donde empezara la instalación
<div align=center><img src="img/img07.png"></div>

6- Despues de un corto tiempo nos aparece este recuadro de terminos de Licencia, al cual le daremos en "I Agree"
<div align=center><img src="img/img08.png"></div>

7- Proseguimos con dar click en "Install"
<div align=center><img src="img/img09.png"></div>

8- Esperamos que termine de instalar
<div align=center><img src="img/img10.png"></div>

9- Cuando nos muestre que a completado le daremos en "Next"
<div align=center><img src="img/img11.png"></div>

10- Luego le daremos en "Finish"
<div align=center><img src="img/img12.png"></div>

11- Continuamos dandole en "Next"
<div align=center><img src="img/img13.png"></div>

12- Le damos click en "Next"
<div align=center><img src="img/img14.png"></div>

13- Finalizamos dando Click "Finish"
<div align=center><img src="img/img15.png"></div>

14- Ya tendriamos instalado NMAP
<div align=center><img src="img/img16.png"></div>

# Comprobacion de la carpeta de instalacion NMAP en el PATH
Ahora comprobamos que tengamos agragada la carpeta de instalacion de NMAP en el PATH del sistema de Windows

- Presionaremos nuestra tecla de Windows de nuestro teclado y escribiremos "variable, lo cual nos mostrara un aplicativo llamado "Editar las variables de entorno del sistema" la cual daremos Click
<div align=center><img src="img/img17.png"></div>

- Nos aparecera este recuadro y seleccionaremos donde dice "Variables de entorno.."
<div align=center><img src="img/img18.png"></div>

- Seleccionamos donde dice "Path" y luego en "Editar"
<div align=center><img src="img/img19.png"></div>

- Como podemos ver ya tenemos agregada la ruta de instalacion de NMAP en PATH
<div align=center><img src="img/img20.png"></div>

_________________________________________________________________________________
# **Comandos**

| # | **Comandos** |**Descripcion**| **Imangen**
|-- |:--:|:--:|:--:|
| 18 |**nmap localhost**| Estos son los puertos abiertos para la dirección **“localhost”**, que no es otra dirección más que la propia de la máquina servidor. Estos puertos evidentemente son locales, lo que quiere decir que no todos ellos necesiten ser abiertos en un router para poder dar los servicios hacia Internet, aunque muchos de ellos si.|<div align=center><img src="img/img21.png"></div>
| 19 |**nmap 172.25.160.1**| Este es el formato básico para Nmap y devolverá información sobre los puertos en ese sistema.|<div align=center><img src="img/img22.png"></div>
| 20 |**nmap -sP -n xxx.xxx.xxx.0/24**| |<div align=center><img src="img/img23.png"></div>
| 21 |**nmap -sP -n xxx.xxx.xxx.100-110**| |<div align=center><img src="img/img24.png"></div>
| 22 |**nmap -iL lista_ip.txt**|Se pasan los objetivos en un fichero, cada uno en una línea|<div align=center><img src="img/img25.png"></div>
| 23 |**nmap scanme.nmap.org**|Esta opción escanea todos los puertos TCP reservados en la máquina scanme.nmap.org.|<div align=center><img src="img/img26.png"></div>
| 24 |**nmap 1.1.1.1 8.8.8.8**|Esta opción escanea dos direcciones IP a la misma vez. |<div align=center><img src="img/img27.png"></div>
| 25 |**nmap udenar.edu.co**||<div align=center><img src="img/img28.png"></div>

# Mas Información
* [NMAP][1_0]
* [Nmap una aplicación fundamental en tu sistema linux][1_1]


[1_0]: https://es.wikipedia.org/wiki/Nmap

[1_1]: https://www.profesionalreview.com/2016/01/27/nmap-una-aplicacion-fundamental/



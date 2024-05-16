# Tools-for-Kali-Herramientas-para-kali


Aqui os dejo algunas herramientas que os pueden ser utiles para Kali Linux, estan muy resumiditas y facil de entender.


macchanger
Para cambiar nuestra direccion mac
macchanger --random wlan



proxychains
Utiliza varios servidores proxy para ocultar nuestra informacion, este comando no se suele ejecutar solo
proxychains nmap "ip"



traceroute: 
analiza todos los paquetes que viajan de cuando nosotros buscamos una web
traceroute google.com


whatweb: 
nos da informacion de una web
whatweb web.com


whois:
nos da informacion de una web
whois web.com


nmap:
es una herramienta de escaneo
nmap kali.org --script vuln


dirb
para encontrar archivos y directorios ocultos de una web
dirb (objetivo web) (wordlist)
dirb "hola.com" rockyou.txt


nikto:
para encontrar vulnerabilidades de un sistema
nikto -h "direccion ip"


SQLiv
es una herramienta para encontrar vulnerabilidades sql en una web


Burpsuite
es un programa que viene en nuestro sistema para hacer de proxy entre la conexion de un usuario y una web y tiene varias funciones para usar como solicitudes de fuerza bruta interceptar trafico inyectar sql... etc hasta se pueden crear herramientas en el programa con java para burpsuite.


OWASP ZAP
Es una herramienta creada con java para testear la seguridad de una web, viene con una interfaz grafica. Para abrir owasp zap ejecutar en el terminal:
owasp-zap



httrack
Es una herramienta para crear paginas web falsas para hacer phising.
httrack


JoomScan
es una aplicacion web para escanear CMS


wpscan
herramienta para escanear vulnerabilidades de word press


FINDMYHASH
Es una herramienta para encriptar codigo
Imaginemos que tenemos un codigo encriptado con el algoritmo de hash "MD5" Podemos desencriptarlo con findmyhash:
findmyhash MD5 -h "pegar codigo encriptado"



crunch
para crear wordlist a partir de lo que nosotros le digamos. Se ejecuta:

crunch "minimo de caracteres para indicarle a la herramienta" "maximo de caracteres", "palabra que queremos que contenga la wordlist como user" -t "patron de numeros como 1234" -o "nombre del archivo donde se creara la wordlist"


john the ripper: para crackear contraseñas


Hydra: Es un crackeador de contraseñas disponible para multiples servicios


Fluxion 
es una herramienta para realizar auditorías de redes inalámbricas Wi-Fi**. Fluxion funciona de manera similar a Wifite, lanza un ataque de ingeniería social y comprueba si el usuario de la red Wi-Fi atacada introduce la contraseña de su red y comprueba si dicha contraseña Wi-Fi es la correcta o no.


Set:
es una herramienta para crear ingenieria social como phising


Metasploit
Herramienta para automatizar ataques de detecion de vulnerabilidades



Wireshark
Es una herramienta analizadora de paquetes de red.
whireshark


Bettercap
Herramienta para realizar ataques MITM(Man in the midle)


Whoami
Herramienta que te hace anonimo en kali linux


Kalitorify
Herramienta para crear un proxy transparente en la red de Tor


Nipe
Herramienta para el anonimato


Zenmap
Busca vulnerabilidades de un sistema


Maltego
Maltego es una herramienta de inteligencia de código abierto diseñada para la recopilación y visualización de datos de inteligencia. Puedes crear graficos para investigar actividades criminales y usar transformaciones te permiten ver mas informacion de las huellas del atacante.


Exploit database
Viene con un monton de exploits para lanzar a bases de datos


Netcraft
Puedes obtener informacion detallada de una web como su infraestructura tecnologiaca.






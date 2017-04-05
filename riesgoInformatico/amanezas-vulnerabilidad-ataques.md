#Amenenazas, vulnerabiliadedes y ataques

## Vulnerabilidad
Es una defecto o debilidad en un sistema que puede ser aprovechado por un atacante.
Existen tres tipos de vulnerabilidades
1. *Vulnerabilidades conocidas* para las cuales existe un parche o actuliazacion que las corrige.
2. *Vulnerabilidadaes conocias* para las cuales **NO** existe un parche o actualizacion. (Zero day)
3. *Vulnerabilidades no conocidad* son a las que nos encontramos expuestos sin saberlo durante un largo tiempo.

> La amenza se vuelve ralidad a travez de un ataque

## Ataques

### Existen diferentes tipos de ataques segun la seguridad que vulneran.

1.*Interrupcion:* vulnera la disponibilidad del recurso, del sistema o de la red. El recurso no podra ser usado. (DoS o DDoS)
2.*Intercepcion:* Ataca la confidencialidad. Un intruso accede a la informacion almacenada en nuestros sistemas o que se ha transmitido por la red. (MITM)
3.*Modificacion:* Ataca la integridad de los datos. Los datos han sido manipulados por personal no autorizado. (DNS Spoofing, MITM)
4.*Fabricacion* vulnera la autenticidad. Se trata de conseguir que un producto sea similar a otro a fin de no poder distinguir al original (phising)

### Segun la forma de atacar o la forma de actuar de los ataques
1. *Spoofing o suplantacion de identidad:* Este tipo de tecnicas se hace uso en redes internas tipo LAN.
	- ARP Spoofing: consiste en modificar las tablas ARP de las victimas. falsificando la correspondencia : IP - MAC. Reemplazando en el router por la del nodo atacante. De esta manera el atacante puede decidir si ser activo suplantando la identidad o pasivo solo escuchando y retransmitiendo los paquetes a la victima (MITM)
	- DNS Spoofing: Busca falisificar la respuesta del servidor de DNS sobre una peticion de la victima y darle una direccion diferente a la real, (direccion maligna, puede contener phishing o malwares)

2. *Sniffing o Analisis de trafico:* Este tipo de ataque consiste en escuchar toda la red. En esta captura de trafico se pueden encotrar mensajes en texto planos como emails.Tambiense realizan sniffing de traficos en redes en las que no estamos autenticados, por ejemplo las redes wifi en las cuales enganchamos el canal de transmision y segun la intensidad de la señal que tengamos podemos capturar los paquetes que por ella transitan (Interfaz en modo promiscuo) y asi conseguir autenticaciones de la red.

3. *Conexiones no autorizadas a equipos y servidores:* Este tipo de ataque se logra de muchas maneras tanto fisicas mirando el teclado de una victima , o utilizando malwares, puertas traseras,Escala de privilegios, etc. permitiendo una conexion de acceso remoto al equipo.

4. *Introduccion de malwares: *Como malwares conocemos a virus, troyanos, gusanos, ramsonware, etc que infectan al equipo dañandolos de muchas formas.

5. *Keyloggers: * Se tratan de dispositivos que permiten grabar la informacion de las pulsaciones de teclas en el teclado. Pueden ser de tipo hardware o software.

6. *Denegacion de servicios: * Se ejecuntan contra servidores o redes con el objetivo de interrumpir el servicio que estan ofreciendo. DoS y DDoS. Este tipo de ataque se vieron potenciados con el fuerte crecimiento de dispositivos conectados a itnernet (IoT). En el ultimo tiempo el ataque DDoS que sufrio DynDNS el cual afecto a varios grandes servicios en internet que usban los servicios (Spotify, Netflix, twitter, etc) fue impulsado por una botnet de IoT llamada Mirari.
	
7. *Inundacion de peticiones SYN: * (SYN flood) Consiste en hacer una peticion de conexion al servidor (SYN) y no responder su aceptacion de conexion. Este tipo de ataque produce una saturacion de conexiones abiertas en el servidor de tal forma que si son muy elevados podramos llegar a un colapso del servicio.

8. *Ingenieria Social: * Este ataque afecta directamente a la confidencialidad y el vector de ataque es la persona.  Consiste en obtener informacion  confidencial de una persona u organismo.

9. *Phishing: *Es una tecnica de engaño a personas con la que se intenta obtener informacion confidencial apartentando ser otra persona, aplicacion o sitio web.


#Amenenazas, vulnerabiliadedes y ataques

### Vulnerabilidad
Es una defecto o debilidad en un sistema que puede ser aprovechado por un atacante.
Existen tres tipos de vulnerabilidades
1. *Vulnerabilidades conocidas* para las cuales existe un parche o actuliazacion que las corrige.
2. *Vulnerabilidadaes conocias* para las cuales **NO** existe un parche o actualizacion. (Zero day)
3. *Vulnerabilidades no conocidad* son a las que nos encontramos expuestos sin saberlo durante un largo tiempo.

> La amenza se vuelve ralidad a travez de un ataque

### Ataques

####Existen diferentes tipos de ataques segun la seguridad que vulneran.

1.*Interrupcion:* vulnera la disponibilidad del recurso, del sistema o de la red. El recurso no podra ser usado. (DoS o DDoS)
2.*Intercepcion:* Ataca la confidencialidad. Un intruso accede a la informacion almacenada en nuestros sistemas o que se ha transmitido por la red. (MITM)
3.*Modificacion:* Ataca la integridad de los datos. Los datos han sido manipulados por personal no autorizado. (DNS Spoofing, MITM)
4.*Fabricacion* vulnera la autenticidad. Se trata de conseguir que un producto sea similar a otro a fin de no poder distinguir al original (phising)

####Segun la forma de atacar o la forma de actuar de los ataques
1.*Spoofing o suplantacion de identidad:* Este tipo de tecnicas se hace uso en redes internas tipo LAN.
	- ARP Spoofing: consiste en modificar las tablas ARP de las victimas. falsificando la correspondencia : IP - MAC. Reemplazando en el router por la del nodo atacante. De esta manera el atacante puede decidir si ser activo suplantando la identidad o pasivo solo escuchando y retransmitiendo los paquetes a la victima (MITM)
	- DNS Spoofing: Busca falisificar la respuesta del servidor de DNS sobre una peticion de la victima y darle una direccion diferente a la real, (direccion maligna, puede contener phishing o malwares)
2. *Sniffing o Analisis de trafico*

3. Conexiones no autorizadas a equipos y servidores
4. Introduccion de malwares
5. Keyloggers
6. Denegacion de servicios
7. Inundacion de peticiones
8. Ingenieria Social
9. Phishing
# Tarefa 1.3 Instalación de zonas secundarias.


Partindo da tarefa 1.1, engadiremos un servidor DNS secundario con BIND9 nunha máquina Debian

1. Tomaremos a máquina darthsidious, e configuraremola para ser servidor secundario, tanto da zona primaria de resolución directa como de resolución inversa. Captura os ficheiros de configuración en ambalas dúas máquinas. Fai unha captura onde se vexa o reinicio da máquina darthsidious, no que se vexa no log dos dous equipos e que se fixo a transferencia de zona.

![imaxe1](imaxes/imaxe1.png)

![imaxe2](imaxes/imaxe2.png)

![imaxe3](imaxes/imaxe3.png)

![imaxe4](imaxes/imaxe4.png)

2. Engade un rexistro tipo A (Chewbacca 192.168.0.28) na zona de resolución directa e tamén na de resolución inversa.  Fai unha captura no momento do reinicio do equipo darthvader, no que se vexa o log dos dous equipos e que se amose que se fixo a transferencia de zona. Adxunta tamén unha captura do ficheiro de zona no servidor secundario.

![imaxe5](imaxes/imaxe5.png)

![imaxe6](imaxes/imaxe6.png)

![imaxe7](imaxes/imaxe7.png)

3. Comproba que o servidor secundario pode resolver ese nome.


![imaxe8](imaxes/imaxe8.png)


4. Fai os cambios necesarios para que as trasferencias se fagan de forma segura empregando chaves.  Repite as capturas e vídeos do punto 2, engadindo o rexistro r2d2 (192.168.0.29)

![imaxe9](imaxes/imaxe9.png)

![imaxe10](imaxes/imaxe10.png)

![imaxe11](imaxes/imaxe11.png)

![imaxe12](imaxes/imaxe12.png)

![imaxe13](imaxes/imaxe13.png)

![imaxe14](imaxes/imaxe14.png)



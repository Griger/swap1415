#Ejercicios Tema 3

##Ejercicio 1

Una herramienta para el enrutamiento en Linux es Iptables que está construido sobre Netfilter. También existe para esta plataforma [iprute2](http://www.linuxfoundation.org/collaborate/workgroups/networking/iproute2) que es un conjunto de herramientas con las que podemos controlar el tráfico de red.
El comando [route](http://www.ite.educacion.es/formacion/materiales/85/cd/linux/m6/enrutamiento_en_linux.html) también nos permite configurar las rutas dentro de nuestra máquina.

En Windows tenemos una herramienta gráfica que se llama [NetRouteView](http://www.nirsoft.net/utils/network_route_view.html) que se presenta como una alternativa a la clásica Route. También está disponible [Win IP Config](http://www.pkostov.com/wipcfg.html).

##Ejercicio 2

En Linux podemos usar [iptables](http://www.netfilter.org/documentation/HOWTO/packet-filtering-HOWTO-3.html), el problema es que los cambios que introduzcamos con este programa se perderán al reiniciar el ordenador, para evitar esto podemos usar scripts para poder guardar y usar la configuración de iptables cada vez que sea necesario. Este comando se encuentra dentro de [Netfilter](http://es.wikipedia.org/wiki/Netfilter/iptables).

En Windows podemos usar el Firewall que tiene el sistema instalado por defecto o también tenemos disponible [WinDivert](https://reqrypt.org/windivert.html).

---
layout: post
title: Mi servidor doméstico
---

Desde que descubrí la Rasberry Pi me quedé fascinado con la de posibildades que esta ofrecía. Si bien estuvo pensada para educación, su bajo coste y consumo hacen que sea una excelente opción a la hora de montar un servidor doméstico sin invertir demasido.

<iframe width="560" height="315" src="https://www.youtube.com/embed/VnBfCtGRXXo" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

Para los que quieran la versión en texto:

Comenzando por las entrañas del propio servidor, este está basado en la distro DietPi disponible para un montón de dispositivos como la Raspberry Pi, otras placas similares y también para casos curiosos, al menos a mi me sorprendió encontrar estas opciones, como son las máquinas virtuales.

Empleando este sistema operativo es relativamente sencillo meterle todos los servicios que se necesiten, aunque eso si, teniendo en cuenta que se van a instalar en un equipo de bajos recursos lo mejor sería no abusar. Eso si, se ahorra el tener que instalar dependencias ya que lo hace el propio sistema operativo en la instalación inicial.

Entrando ya en materia de servicios; cual fue el servicio base que me fascinó y me empujó a montar el servidor? Bien pues la respuesta es Nextcloud. Cuando descubrí este servicio me pareció brutal la de cosas que se pueden hacer con él partiendo de la base de que es una nube privada, como pueden ser Dropbox o Google Drive. La gracia? Puedes ser el dueño totalmente de tu información, cosa que en servicios como los anteriormente mencionados no ocurre pues no se está en posesión física de los datos y las empresas pueden borrar o manipular los ficheros como se les antoje realmente (véase crear perfiles publicitarios, por ejemplo). Mediante plugins que se pueden instalar desde el propio admin panel se le puede ir agregando funcionalidades como calendarios, los cuales se pueden sincronizar, por ejemplo con el horario de la uni, OJO. Una suite ofimática online desde el propio servidor Nextcloud y algunas cosillas interesantes más.

Sobre este servidor Nextcloud se basa todo el servidor doméstico prácticamente, lo instalé concretamente en un disco duro usb que conecté a la raspi de forma que el almacenamiento puede ser todo lo generoso que uno quiera ( a diferencia de cuando se instala sobre la SD de la Raspberry Pi).

![Servicios](https://ateuves.es/wp-content/uploads/2018/02/at0218_anestesia_cardiovascular_702.jpg)

Antes de pasar a hablar sobre los servicios que complementan a Nextcloud dentro del servidor me parece importante hablar sobre cómo se administra la Raspberry.
Siendo un dispositivo de recursos tan limitados a veces viene bien comprobar que todo está en orden, temperaturas, carga de trabajo, memorias, almacenamiento… Y esto se puede hacer realmente bien con RPI Monitor. Es un servicio ligero y directo que aporta gráficas y datos desde el propio navegador sobre la actividad de la raspi. Tan solo hace falta introducir la URL de la raspi junto con el puerto 8888 en el navegador y ya. Sencillo, no? Por otra parte, el servidor no cuenta con ningún tipo de periférico ( sin contar el disco duro) y por tanto se accede a este mediante SSH, un famoso conocido de los entornos Linux.

Bien, el punto anterior es perfecto desde el punto de vista local, pero ¿Y si se necesita (o quiere) acceder desde el exterior? Pues hay diferentes alternativas como crear una VPN, pero me pareció más sencillo emplear No-IP ya que ya lo conocía y su configuración al instalar el sistema operativo es realmente sencillo. Con un dominio gratuito cumple con creces su función.

![Plex](https://techcrunch.com/wp-content/uploads/2019/08/plex-desktop-movies-1024x659.jpg?w=730&crop=1)

Y por si Nextcloud no fuera lo suficientemente fascinante de por si mismo, vamos a pasar a hablar sobre servicios que se configuraron alrededor de este, es decir que lo complementan y aportan mayor funcionalidad a todo el servidor doméstico.

En primer lugar se encuentra Plex, un servidor multimedia muy potente y que permite ver todo tipo de series, pelis, escuchar música o visualizar esas fotos de las vacaciones de verano en Nueva York. Funciona bastante ágil teniendo en cuenta que se ejecuta en una Raspberry Pi y con un compañero en el salón como es un Chromecast permite disfrutar de todo el contenido del servidor de forma muy cómoda. 

Bien, pero ir metiendo pelis o fotos en el servidor no es muy cómodo desde Nextcloud, este es útil para mantener copias de seguridad o acceder puntualmente a archivos, pero no ir moviendo archivos pesados como puede ser un archivo en Full HD de varios gigas, para este menester instalé Transmission de forma que se le pueden añadir torrents muy facilmente. Concretamente con la versión servidor, recordemos que estamos en un servidor, que permite añadir torrents desde un navegador web o desde la app movil directamente al servidor.

Así que esta es la versión inicial de mi servidor doméstico, si inicial. Actualmente tengo otros servicios instalados de los que hablaré más adelante.

Podéis suscribiros al canal de Youtube y comentar en el video que hay en esta entrada que os parece tener un servidor doméstico y si os lo planteariais.

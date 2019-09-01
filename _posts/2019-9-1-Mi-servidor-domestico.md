---
layout: post
title: Mi servidor doméstico
---

Desde que descubrí la Rasberry Pi me quedé fascinado con la de posibildades que esta ofrecía. Si bien estuvo pensada para educación, su bajo coste y consumo hacen que sea una excelente opción a la hora de montar un servidor doméstico sin invertir demasido.

<iframe width="560" height="315" src="https://www.youtube.com/embed/VnBfCtGRXXo" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

Para los que quieran la versión en texto:

Este servidor lo planifiqué teniendo en cuenta el servicio de Nextcloud como base. Este se instaló en un disco duro externo y el resto de servicios giran a su alrededor. Esto lo hice así pues ofrece un buen sistema de sincronización (subida y bajada de ficheros) bastante sencilla aunque no automática al nivel de OneDrive o Dropbox, no como me gustaría. Por eso, entre otras cosas hablaré de los cambios que sufrió.

![Servicios](https://ateuves.es/wp-content/uploads/2018/02/at0218_anestesia_cardiovascular_702.jpg)

Para la monitorización del servidor a un nivel bastante básico pero útil decidí emplear RPI Monitor por su ligereza y facilidad de consulta, con la dirección IP del servidor y dándole como puerto el 8888 se puede tener de forma rápida gráficos y datos de cuanta carga de trabajo tiene el server, temperaturas, memorias y almacenamientos, etc. Además se puede ampliar para ver por ejemplo la carga de red que tiene el servidor.

Llegados al punto de la monitorización y mantenimiento del servidor a distancia, planteé varias formas de acceder a este desde fuera de la red local entre las que se encontraba el crear una red VPN. Al final me decidí por emplear No-IP ya que ya lo conocía y me pareció bastante sencillo de emplear con un sistema operativo como es DietPi. Con un dominio gratuito estaba más que servido.

![Plex](https://techcrunch.com/wp-content/uploads/2019/08/plex-desktop-movies-1024x659.jpg?w=730&crop=1)

En cuanto a los servicios que se complementan con Nextcloud es bastante sencillo: 
Por una parte se encuentra Plex, un servidor multimedia muy potente y que la verdad me sorprendió para bien como funcionaba, bastante rápido teniendo en cuenta que se ejecutaba desde una Raspi y junto con un Chromecast en el salón es una opción muy buena para disfrutar tanto de series, pelis, música, ver las fotos guardadas, etc.
Por otra parte se instaló Transmission para sincronizar mediante torrent con el servidor y luego poder manipular o usar dichos archivos con Plex o Nextcloud.


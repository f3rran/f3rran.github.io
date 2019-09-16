---
layout: post
title: Como crear una intranet fitness con Wordpress
---

Este tutorial se enfocará en un término general para la generación de una Intranet y luego se profundizará en enfocarla a un centro de deporte o un negocio fitness online, puede ser polivalente y válido en ambos casos, pues se puede habilitar una pasarela de pagos con las que mantener las sucripciones al servicio al cliente o incluso el pago del centro de deportes.

<iframe width="560" height="315" src="https://www.youtube.com/embed/lbitKnfY2Wk" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

#Estructura:

-Blog con noticias, novedades y contenido que ofrecer a los clientes y no clientes que visiten el sitio con lo que aportar valor.
-Dentro de la intranet compartir rutinas de deporte. Opcionalmente poder imprimir en PDF.
-Dentro de la intranet compartir dietas alimenticias. Opcionalmente poder imprimir en PDF.
-Notificaciones a clientes por correo electrónico.
-Perfil personalizado para clientes con; medidas(altura), peso, dieta(vegana, omnivora…), datos personales,etc. 

#Recursos:

-Servidor web; Nginx/Apache + Base de datos
-Wordpress
-Plugin Wordpress: WP Customer Area; 
    -WP Customer Area - Additional Owners Types
    -WP Customer Area - Front-Office publishing
    -WP Customer Area - Enhanced files
    -WP Customer Area - Notifications
    -WP Customer Area - Conversations
    -WP Customer Area - Tasks
    -WP Customer Area - Managed Groups
    -WP Customer Area - Owner restrictions
   - WP Customer Area - Projects

#Primeros pasos

En primer lugar, como es lógico es necesario realizar la instalación típica de Wordpress. Una vez está todo lo básico listo es necesario instalar el plugin WP Customer Area y encontrar un Theme que se amolde a su funcionamiento, GeneratePress funciona bien en escritorio pero no permite emplear el menú de navegación en móviles, hace falta encontrar otros themes para smartphone como por ejemplo “twenty seventeen theme”.

En la parte de WP Customer Area es necesario realizar la configuración básica:
1. Crear páginas básicas ( se autogeneran con pulsar un botón).
2. Dar permisos. El plugin puede requerir ciertos permisos.


Instalar WP Customer Area - Additional Owner Types
Con este plugin para el plugin se admite la gestión de usuarios por lotes, es decir, en caso de requerir clasificar los clientes por categorías, la información de la intranet podrá ser entregada a varios clientes o directamente según las agrupaciones de las categorías.

Por ejemplo, en el caso que concierne a este documento, en caso de realizar una rutina para varios clientes, esta puede ser entregada de una sola vez a los clientes, aunque tal vez, por el tema de comentarios en la propia rutina, sería mejor entregar por separado, pero podría ser útil también para la entrega de avisos que conciernen a la plataforma o al centro deportivo.


##Instalar WP Customer Area - Front-Office Publishing
Con este plugin se dotará a la intranet de la capacidad de generar y compartir contenido desde la propia intranet. Sin este plugin, la generación de documentación o contenido debe hacerse desde el propio panel de administración de Wordpress, algo que puede ser peligroso y perjudicial para el buen funcionamiento de Wordpress.
-Al instalarse, recordar seguir las instrucciones que da el plugin y generar las páginas necesarias para su funcionamiento.
-Y actualizar el menú de navegación para poder acceder a dichas páginas creadas.

##Instalar WP Customer Area - Enhanced files
Con este plugin se habilita la subida de varios archivos dentro de lo que este plugin entiende como un archivo. Puede ser útil para entregar, por ejemplo, una rutina de gimnasio en varios formatos; PDF,JPG…

Instalar WP Customer Area - Notifications
Es necesario para generar notificaciones por correo electrónico, tanto para los administradores, que estén al corriente de qué pasa como para los clientes al subir contenido nuevo que necesiten o que pueda interesarles, por ejemplo al subir una rutina, que le llegue un aviso al cliente de que ya la tiene disponible. El activar la notificación se realiza en la generación de contenido, es decir por ejemplo al generar una página.
-Al instalarse, recordar seguir las instrucciones que da el plugin y generar las páginas necesarias para su funcionamiento.
-Y actualizar el menú de navegación para poder acceder a dichas páginas creadas.



##Instalar WP Customer Area - Conversations
Mensajería interna en la intranet. Funciona como los comentarios de una página. Básicamente puede ser útil si no se emplean los comentarios de las páginas o archivos. Sería una buena idea comentarlo si se quiere externalizada la conversación, para poder entregar la misma rutina a varios clientes o dieta.
-Al instalarse, recordar seguir las instrucciones que da el plugin y generar las páginas necesarias para su funcionamiento.
-Y actualizar el menú de navegación para poder acceder a dichas páginas creadas.


##Instalar WP Customer Area - Tarks
Puede ser útil para generar listas de tareas. Principalmente su uso debería ser a nivel interno de la empresa y podría no ser del todo factible su uso.
-Al instalarse, recordar seguir las instrucciones que da el plugin y generar las páginas necesarias para su funcionamiento.
-Y actualizar el menú de navegación para poder acceder a dichas páginas creadas.

##Instalar WP Customer Area - Projects
Genera proyectos como si fueran páginas pero con información adicional destinada a crear proyectos. 

##Página del login
Para generar un login personalizado se puede usar la opción gratuita de ‘LoginPress’. Permite modificar el fondo, textos captcha… y eso solamente desde la versión gratuita, se puede ampliar a una versión pro con mayor funcionalidad.

---
layout: post
title: Creo un chat Android y pasa esto
---

¿Quién no ha soñado nunca con crear un chat que le hiciera la competencia a Whatsapp? Se podría decir que yo viví como es el desempeñar un proyecto de ingeniería a todos los niveles, evidentemente distando mucho de poder competir con Whatsapp. Os dejo con una preview de como es el chat.

VIDEO YOUTUBE:
<iframe width="560" height="315" src="https://www.youtube.com/embed/NGcMtGWpPkE" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

Bien, este chat nació como proyecto final de una asignatura de tercero de mi carrera llamada Ingeniería del Software. En ella vimos el ciclo (o ciclos) de vida que puede tener el software de cualquier tipo, desde su conceptualización, su posterior diseño para finalmente llevarlo a cabo y tratar de desplegarlo.Se trata de una historia que se tuerce por el camino, pero que al final creo que conseguí salvar el pellejo lo mejor que pude.

En los primeros días de clase, el profesor ya nos advirtió del proyecto final que tendría la asignatura, llevar a cabo todo el proceso de creación hasta llegar a una aplicación o servicio que hubiésemos pensado. Evidentemente nos dió sugerencias; aplicaciones de notas, algún juego, algún servicio web… Yo por mi parte, supe casi de inmediato por donde quería ir, quería ver cuánto había aprendido en la programación Android y tratar de mejorar en la medida de lo posible.

![Diagrama UML](https://d2slcw3kip6qmk.cloudfront.net/marketing/pages/consideration-page/UML/UML-used-by-developers.png)

De pura casualidad y sin yo esperarlo, oí como un compañero le hacía preguntas al profesor acerca de realizar el proyecto con Android, me acerqué a comentar algunas cuestiones sobre el desarrollo para Android y al final sin esperarlo encontré compañero para el proyecto. Empezamos con la conceptualización, el diseño UML, la especificación completa del proyecto… Estoy hablando de semanas de trabajo con lo que las otras asignaturas empezaron a aumentar su carga de trabajo, a esto se me sumó que arrastraba Fundamentos de Sistemas Operativos del año anterior, mis compañeros de clase entenderán porqué, con lo que a la hora de programar empezamos a retrasarnos y perdimos prácticamente el contacto. Mi idea, era dejar el desarrollo para pasados los exámenes de forma que a base de Monster y cafés saliera a la luz el proyecto.

Avanzamos hasta el dia de nochebuena del año pasado, me encuentro de celebración con mis amigos antes de irnos cada uno a sus respectivas cenas familiares cuando me llegan una serie de mensajes al móvil; mientras yo había dejado de trabajar en el proyecto para atender otras tareas de mayor urgencia, mi compañero había ido trabajando en el servidor y los sockets para comunicarse con este y me decía que abandonaba el barco para hacer el proyecto por su cuenta. Fue indescriptible como me sentí en ese momento, recuerdo que me fuí al acabar paseando lentamente hasta mi casa pensando y pensando. Había argumentos tanto para culparme, como para culparle a él, básicamente se podría resumir en que el problema era la comunicación.

![Firebase API](https://3.bp.blogspot.com/-aYo4ugzzp38/Vi7I6HxmjmI/AAAAAAAAB1Y/AD3mNx8XTUY/s640/firebase.png)

Bien pues, llegado el día de Navidad, empecé con el proyecto y me dediqué a él al 100%, básicamente era lo que quería hacer. Tenía de tiempo hasta pasado el día de reyes, así que era viable, pero tuve que replantear la parte del servidor pues no me iba a dar tiempo si trabajaba como teníamos planeado. Replantee el servidor empleando Firebase, una locura teniendo en cuenta que uno de los requisitos para el chat era poder crear e interactuar mediante grupos.Quien haya trabajado con FIrebase y su modelo de bases de datos lo entenderá y probablemente me dedique algunas palabras. Pero el tiempo apremiaba, contaba con lograr algún tipo de solución mientras creaba todo el cliente móvil y replanteaba la estructura de la base de datos exclusivamente para los grupos.

Rehice todo el cliente Android un par de veces, pero llegué a formar un servicio que funcionaba todo, a excepción de los grupos. Se podían crear, faltó perfeccionar como interactuar desde diferentes usuarios con dicho grupo, le di vueltas pero me quedé sin tiempo. El día de la presentación llegaba y la verdad es que creía que sería de los peores en cuanto al proyecto. Me alegró saber que no fue así.

![Desarrollo con Android Studio](https://developer.android.com/studio/images/projects/new-project-wizard-choose_2x.png?hl=es-419)

Llegó el día de la presentación y la verdad es que algunos proyectos eran auténticas maravillas, hay uno que todavía recuerdo muy bien, un chat también, realizado en web con PHP y JavaScript de manera muy profesional y también con un diseño fresco y pulcro. Conseguí una nota bastante decente, mi proyecto era uno de los más maduros que había en la presentación incluso superando a mi ‘compañero’ el cual solo llegó a realizar un login y un listado de agenda.

Debo añadir, que en cuanto el profesor oyó que el servidor estaba hecho en Firebase hizo muecas mientras presentaba, pero que al ver la demo se quedó por así decirlo tranquilo. La verdad es que era fácil tratar de adivinar qué podía estar pensando mientras evaluaba. Por otra parte también hacía bastantes preguntas cuando algo no le quedaba claro.


![Chat Android](https://hackernoon.com/hn-images/1*5SI-UdJqOpr0OTsArgdfsA.png)

La verdad es que interiormente me sentí triunfante pues había dado la vuelta a la situación consiguiendo un mejor proyecto que mi antiguo compañero. Eso sí, mi mente que es muy de darle vueltas a las cosas, me quedé pensando en cuál podría haber sido el potencial del proyecto si en vez de hacer algo a medio hacer por dos caminos distintos, nos hubiésemos comunicado mejor y hubiésemos creado un proyecto unificado y más sólido. 

Supongo que me quedaré con la curiosidad de saberlo y tendré que averiguarlo con nuevos proyectos. Espero que os haya gustado este fragmento de mis estudios.

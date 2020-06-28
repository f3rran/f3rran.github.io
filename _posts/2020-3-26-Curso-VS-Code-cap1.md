---
layout: post
title: Curso Visual Studio Code - Capítulo 1
---

Tras un tiempo probando esta fantástica herramienta, me he decidido a crear un breve curso de cómo exprimir algunas funcionalidades de Visual Studio Code.

Para poner a todos en contexto, conocía esta herramienta desde ya hace algún tiempo. No obstante, mis requerimentos en cuanto a programación se resumían en el uso de IDEs como Eclipse, Netbeans, PyCharm,etc. Entornos controlados donde se podía crear, compilar y ejecutar el código. ¿Pero qué pasa cuando entras a trabajar en una empresa donde no se pueden usar esa clase de entornos? Mis compañeros apostaban por Notepad++ y es la opción que me recomendaron. Y con la que empecé. No me malinterpreten, es una herramienta ligera y con un montón de posibilidades. Pero notaba que se me quedaba algo corta. Si tenía que estar horas delante de un editor de código, ¿qué menos que poder contar con un entorno donde poder estar a gusto y con ciertas 'chuches' que hagan el trabajo más llevadero?

A raiz de esto me planteé estos episodios o capítulos donde abordar un poco de qué manera empleo Visual Studio Code a día de hoy para que le pueda ayudar a cualquier persona que se encuentre en la misma situación que yo estuve.

![Visual Studio Code logo](https://www.linuxadictos.com/wp-content/uploads/visualstudio_code-card.png)

Para poner a la gente en contexto:
VS Code es un editor multipropósito, aunque enfocado en el mantenimiento de código, creado por Microsoft y por sorprendente que pueda parecer; multiplataforma. Se encuentra disponible tanto para Windows (obvio), Linux y macOS. Permite la depuración de código, control de versopnes, resaltado de sintaxis, entre otros. Desarrollado bajo licencia MIT para plataformas x86.

## Empezamos a trastear
Bien, como había comentado, voy a tratar de seguir (aproximadamente) el mismo recorrido que hice para amoldar VS Code a mis necesidades.

![Elementos principales](https://code.visualstudio.com/assets/docs/getstarted/userinterface/hero.png)

### A - Barra de actividad
Permite visualizar los archivos abiertos y las carpetas abiertas. También permite buscar dentro de los archivos abiertos o carpetas, es decir, dentro de varios archivos a la vez. Algo muy útil. También permite gestionar los distintos plugins, git y algún debugger que tengamos configurado.

### B - Estado
Permite llevar un control de todos los errors o warnings que haya detectado el editor dentro del código. Puede ser bastante útil a la hora de detectar errores.

### C - Grupos de trabajo
Aquí es donde se verá todo el código en el que trabajemos. Se puede ver una sola pestaña o se puede dividir el espacio en pantalla muy al estilo de las ventanas de Windows. Vendrá muy bien en caso de querer detectar posibles errores y cambios entre distintas versiones de un mismo código. También permitirá agilizar el proceso de programar y maquetar una web.

### D - Terminales
Esta es una de las partes más útiles del propio editor. Permite tener a mano una terminal del sistema operativo que se esté empleando para poder agilizar ciertos procesos. En mi caso, soy bastante fan de emplear GIT desde esta terminal. También me ha servido a la hora de hacer pequeños desarrollos con Powershell o Batch.
Permite también realizar el debugging del código, ver que muestra por terminal el programa que se esté ejecutando y visualizar algún posible mensaje de error que se pudiera lanzar.

### E - Codificaciones
Esto es muy útil para reconocer y cambiar, en caso de ser necesario, el resaltado del texto. Por ejemplo al estar programando con PHP, que resalte las palabras en función del lenguaje, no otro o ninguno. También permite cambiar la codificación en caso de programar para varios entornos con diferentes codificaciones y no encontrarnos con sorpresas de caractéres que no se representan adecuadamente.
También permite modificar entre ambos bandos de la eterna lucha entre programadores; tabulaciones o cuatro espacios.

## Temas
Con el atajo Ctrl + K seguido de Ctrl + T Se despliega el selector de temas. Empleando este menú se puede seleccionar el tema que mejor se amolde a las necesidades del trabajo. Por lo general, es más cómodo el módo claro para usos puntuales y dejar los temas más oscuros para los trabajos más extensos. Es poco frecuente, pero en caso de tener una pantalla AMOLED, es interesante emplear los temas con fondos en negro puro ya que serán más cómodos y ayudarán a ahorrar un poco de batería.

## Minimapa
Esta es una funcionalidad que viene activada por defecto y no entiendo porqué mucha gente la quita. Se trata de un minimapa de todo el código que tenemos que ayuda a ver la estructura del código y que además ofrece cierta ayuda para hacer scroll si estamos buscando algo y también si estamos buscando un fragmento concreto de código que se pueda ver de forma mucho más clara y directa.
En la propia barra de scroll se puede ver las coincidencias con el texto seleccionado y con el que se busca. Pero el minimapa puede ayudar en los casos en los que las coincidencias están muy juntas y el código es demasiado extenso como para diferenciar varias coincidencias dentro de la propia barra de scroll.

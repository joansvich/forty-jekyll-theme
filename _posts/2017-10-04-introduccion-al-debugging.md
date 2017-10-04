---
layout: post
title: Introducción al Debugging
description: Artículo sobre los primeros pasos para introducirnos al debugging
image: assets/images/inicio-debugger.png
---


[Aprende Javascript con mentoringjs - Pretraining Step 5](http://mentoringjs.com/ "Aprende Javascript con mentoringjs - Pretraining Step 5")


### Con este artículo quiero enseñaros cómo podéis conocer más a fondo las herramientas que nos proporciona nuestro navegador y cómo explotarlas.


Seguramente ya lo sabréis pero por si las moscas, os voy a decir que es la depuración o debugging. Se trata del proceso que realizamos para encontrar y resolver los problemas que tengamos en nuestro programa y que nos impidan el correcto funcionamiento. Es muy útil en la programación de todos los lenguajes actuales.


Una vez hecho una breve introducción, vamos a ello:


## Herramientas de desarrollo


Antes de nada, tenemos que saber cómo poder usar las herramientas de desarrollo en nuestro ordenador. En función del sistema operativo, tenemos una manera o otra de mostrarlas:  
- **Window/Linux:** ctrl + shift + I  
- **Mac os:** cmd + opt + I


En mi caso uso Mac, así que las capturas las veréis con el entorno de mac pero no os preocupéis, en Windows es idéntico.
![Debugging](https://raw.githubusercontent.com/joansvich/miblog/gh-pages/assets/images/debugging-1.png)


Lo que vemos abajo es las herramientas de desarrollo, donde como podemos observar tenemos bastantes opciones. En este artículo os mostaré las más usadas.


## Consola


La consola es una de las herramientas más usadas a la hora de programar con Javascript. Desde ella podremos ver los errores y las alertas que se generan en nuestro programa.


También podemos generar alertas para poder saber por dónde se mueve nuestro programa y saber en todo momento donde nos encontramos.  
![Consola](https://raw.githubusercontent.com/joansvich/miblog/gh-pages/assets/images/consola-debug.jpg)


## Línea de comandos


En la consola también tenemos una línea de comandos interactiva la cual podemos usarla para probar variables sobre el entorno. Algún ejemplo:  
`// Probamos una operación matemática
2 + 2
// Manipulamos un string
"La manzana " + "partida"
// Creamos una alerta
alert("Vamos por aqui");`


Como podemos observar, es bastante sencillo y muy útil a la vez ya que podremos poner más a prueba nuestro código.


## Depurador interactivo


También disponemos de un conjunto de herramientas útiles a la hora de depurar el código. Esto nos será
muy útil a la hora de tratar con códigos complejos de Javascript.  
Para lanzar el debugger en un punto específico tenemos que introducir la palabra `debugger`.  


![Consola](https://raw.githubusercontent.com/joansvich/miblog/gh-pages/assets/images/debugger.jpg)


Aquí podemos ver las diferentes opciones que nos permite el debugger para ir avanzando o pausando nuestro código.  
Gracias a todas estas opciones podemos ir viendo como actua punto por punto nuestro código y realizar un análisis más profundo de cómo se desarrolla nuestro programa.


Nos vemos en el siguiente artículo!

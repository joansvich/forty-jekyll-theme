---
layout: post
title: La terminal, esa gran desconocida
description: Artículo sobre la terminal de nuestro sistema operativo
image: assets/images/la-terminal.jpg
---


[Aprende Javascript con mentoringjs - Pretraining Step 4](http://mentoringjs.com/ "Aprende Javascript con mentoringjs - Pretraining Step 4")


### En este artículo vamos a ver por qué es tan importante conocer bien la terminal de nuestro ordenador


Estamos acostumbrados a trabajar con la interfaz gráfica de nuestro ordenador ya que es más intuitivo y "fácil". Te preguntarás por qué he puesto la palabra fácil entre comillas. Pues bien, gracias a este artículo vas a ver las funciones que puedes realizar con la terminal y cómo puede resultar mucho más fácil hacer una operación con una línea de código cuando por interfaz gráfica tardarías mucho más abriendo pestañas, minimzando, botón derecho, dando la orden, etc.  
Sin más preámbulos, vamos a ello.


#### ¿Qué es la Terminal?


Antes de empezar describiendo que es la terminal necesitamos saber qué es la shell. Senzillamente es un programa donde podemos introducir comandos vía nuestro teclado y él los manda al sistema operativo para realizar la operación que le digamos. 


Y entonces aquí respondemos a la pregunta inicial: la terminal es un programa el cual nos abre una ventana y nos permite interactuar con la shell.


#### ¿Qué podemos hacer con ella?


Gracias a la terminal podemos hacer muchísimas operaciones con nuestro ordenador. Primero de todo tenemos que saber que para hacer según que operaciones necesitaremos tener privilegios de administrador. En función de que sistema operativo estemos utilizando lo lograremos de una forma o otra.


#### Navegar con la terminal


Una de las principales utilidades de la terminal es el poder navegar por nuestros archivos rápidamente para poder interactuar con ellos.  
Aquí os dejo tres comandos básicos para poder movernos entre ellos. NOTA: son comandos para entornos Unix.


- **pwd**: Esta comanda nos muestra el directorio donde estamos ubicados para tener una visión del árbol del sistema. Así podremos saber la ruta desde el directorio raíz.


- **cd**: Está muy bien saber donde estamos pero, cómo nos podemos mover a diferentes carpetas? Gracias a esta comanda podremos ir a la ruta que le indiquemos o al archivo. Tanto podemos poner rutas relativas como completas.


- **ls**: Con esta comanda podremos saber todos los archivos que tenemos en la carpeta que nos encontremos. Tenemos que tener en cuenta que en los archivos de linux, las mayúsculas cuentan a la hora de dar un nombre a un archivo.


#### Un tour sobre los directorios principales


Cada sistema tiene sus directorios principales. Antes de empezar a escribir en la terminal, siempre recomiendo hacer un recorrido hacia la raíz y comprobar qué directorios nos encontramos y buscar por internet la función de cada carpeta. Aquí os dejo algunos de los básicos de linux para que tengáis una idea:  
- **/**: Es el directorio raíz de todo el sistema linux.  
- **/boot**: Aquí nos encontramos con el kernel y los archivos booteables. El kernel se llama _vmlinuz_.  
- **/etc**: En este directorio tenemos los archivos de configuración para el sistema.


Estos son algunos de los directorios principales más importantes, pero hay bastantes más. Para conocerlos todos, nuestro amigo San Google es muy bueno en eso.


#### Manipulando archivos


Llegamos a una parte muy interesante de la terminal: **la manipulación de los archivos**  
A mi siempre me ha parecido muy interesante ya que gracias a estas comandas podemos copiar un archivo a un directorio tan solo con una comanda de terminal. O directorios enteros dando permisos de administrador y diciendo que acepte y reemplaze todo. Sí, lo has leído bien, no tienes que esperarte a que prepare los archivos, darle a aceptar o reemplazar y estar pendiente de si salta algún aviso o advertencia diciendote que tal archivo no puede copiarse. Lo hace solo gracias a una línea de código. Maravilloso!!


Las principales comandas que usarás serán las siguientes:  
**CP**:  
- _cp [OPCION] origen destino_  
Gracias a esta comanda podremos copiar el archivo que queramos o un directorio entero a la ruta que le indiquemos. Existen muchas opciones adicionales que podemos añadir al comando para darle diferentes funciones, como por ejemplo -f que nos copiará todo a la fuerza.


---
**MV**:  
- _mv [OPCION] origen destino_  
Con esta comanda podremos mover archivos de un directorio a otro. También tendremos la opción de añadir diferentes opciones con las etiquetas.


---
**RM**:  
- _rm [OPCION] archivo_  
Con esta comanda podremos eliminar el archivo o directorio sin más complicaciones. Con la ayuda de etiquetas como -r le daremos la opción de recursividad y que nos elimine todo lo que hay dentro del directorio.


---
**MKDIR**:  
- _mkdir [OPCION] directorio_  
Gracias a esta comanda podremos crear directorios fácilmente.


#### Permisos de los archivos


Para tener un mejor control de la seguridad de nuestro sistema, los archivos están dotados de permisos. Gracias a ellos podemos decir que un usuario puede tener acceso a visualizar este archivo pero no a modificarlo, y otro usuario sí puede modificar y visualizarlo.  
Pero os preguntaréis, ¿cómo puedo configurar los permisos que quiero dar?  
Es muy sencillo, con un comando.  
Gracias al comando **chmod** podemos dar permisos a un archivo sin mucha complicación.  
Los permisos tienen tres bloques: propietario, grupo del propietario y otros. Esto se indicaría de la siguiente forma:  
![Permisos](http://oi64.tinypic.com/e5hedk.jpg)  


Y hasta aquí nuestro artículo de la terminal.  
Nos vemos en el siguiente!

---
layout: post
title: Cómo empezar con Github
description: Pasos básicos a tomar para introducirte en Github
image: assets/images/como-empezar-github.jpg
---


[Aprende Javascript con mentoringjs](http://mentoringjs.com/ "Aprende Javascript con mentoringjs")

### En este documento os intentaré explicar resumidamente lo básico que tenemos que saber para empezar a usar Git


Antes de todo aclarar que Git y Github son cosas distintas: Github usa el software de control de versiones Git. Es decir, Git es la parte de software y Github es la plataforma donde da cabida a nuestros proyectos usando Git para poder colaborar con los diferentes usuarios.
En mi caso voy a usar Github.


- Primero de todo tenemos que configurarnos nuestro entorno Git, en mi caso uso Github.
- Una vez configurado, nos vamos a la consola y inicializamos git con la comanda **git init**


> En Github podemos usar tanto la interfaz gráfica para hacer todos los cambios como la consola de nuestro sistema operativo. En mi caso me gusta más usar la consola ya que voy más rápido, pero eso es una cuestión de gustos y costumbres.


- Para empezar a hacer cambios, tendremos que hacer un clonaje del repositorio (si tenemos creado uno) a nuestro sistema local. En este caso lo haremos con la comanda **git clone /rutaDirectorio**


- Una comanda muy importante que tenemos que tener siempre en cuenta es la de **git status**. Gracias a esta comanda iremos viendo el estado de cómo tenemos nuestros archivos: en que rama estamos, si los tenemos pendientes de subir, etc.


- También hay otra comanda que sirve para ver los cambios que vamos haciendo, esta es **git log** donde vemos en un log los diferentes cambios que hemos ido haciendo.


Llegados a este punto, tenemos que saber una cosa muy importante sobre el funcionamiento de Git:
Git se divide en tres partes: Directorio de trabajo, Index y Head.  
-- **Directorio de trabajo**: donde tenemos los archivos con los que estamos trabajando.  
-- **Index**: es la zona intermedia donde podemos hacer commits para posteriormente subirlo al head.  
-- **Head**: es la última zona donde tendrás tus archivos preparados para ser enviados a tu branch.


- Para añadir archivos al Index usaremos la comanda **git add nombreArchivo**. También podemos subir varios archivos del mismo tipo de archivo haciendo uso de la comanda **git add ".txt"**. Así subiríamos todos los archivos .txt al head.
- Si queremos hacer commit a esos cambios usaremos la comanda **git commit -m "Mensaje Commit"** y así tendremos constancia de lo que hemos hecho.


- Por último, si queremos enviar los cambios que tenemos hechos en Head será tan fácil como usar la comanda **git push origin master** donde master nos referimos a la rama (o branch) que queramos subirlo. NOTA: si usamos la comanda **git push -u origin master** con la comanda _-u_ haremos que nos recuerde los parametros de origen y destino, así la próxima vez introduciendo **git push** ya automáticamente nos hará el origin master que le marcabamos antes.


> Una de las ventajas de Git es la posibilidad de crear ramas (o branch) para poder probar esas versiones _beta_ de nuestro proyecto sin poner en riesgo nuestro código fuente base.  
- Para crear una rama tendremos que usar la comanda **git branch nombreRama**. Si queremos directamente crear la rama y situarnos en ella podemos usar la comanda **git checkout -b nombreRama**.  
- Para cambiar de ramas usamos la comanda **git checkout nombreRama**.  
- Si queremos borrar una rama usaremos la comanda **git branch -d nombreRama**.  
- Por defecto, una rama nueva no la tendremos disponible en nuestro git a no ser que la subamos con la comanda **git push origin nombreRama**.


> Si hemos estado probando en una rama una versión del proyecto que nos ha gustado como funciona, podemos fusionar las ramas para que los archivos que teníamos en la rama _beta_ por ejemplo, las tengamos en la master y así seguir con la dirección del proyecto.
- Para actualizar nuestro repositorio a la versión más reciente usaremos la comanda **git pull**.  
- Si queremos fusionar una rama, nos situamos en la rama master y usamos la comanda **git merge ramaAFusionar** OJO: tenemos que tener en cuenta que a veces git no será capaz de fusionar los archivos y se generarán conflictos, nosotros seremos los encargados de solucionarlos manualmente y luego añadirlos a la rama nueva.  
- Si queremos visualizar los cambios antes de fusionar, podemos usar la comanda **git ramaOrigen ramaDestino**.

---
Al principio cuesta un poco el tema de las comandas, pero a la que vas cogiendo la práctica te darás cuenta que te salen automáticas.


Una página que me ha servido de mucha ayuda es <http://rogerdudler.github.io/git-guide/index.es.html> donde tienes un resumen de todas las comandas más usadas que puedes necesitar.


También recomiendo el curso de codeschool para familiarizarte con la consola y los pasos básicos inciales. Personalmente a mi me ha ido de perlas Aquí dejo el enlace al curso: [Try Git Codeschool](https://try.github.io/levels/1/challenges/1)




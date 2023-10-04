<center>

# UT1-A1 Documentación y sistema de control de versiones


</center>

***Alberto & Toste:***
***Curso:*** 2º de Ciclo Superior de Desarrollo de Aplicaciones Web.

### ÍNDICE

+ [Introducción](#id1)
+ [Objetivos](#id2)
+ [Material empleado](#id3)
+ [Desarrollo](#id4)
+ [Conclusiones](#id5)


#### ***Introducción***. <a name="id1"></a>

En este documento vamos a realizar la primera práctica de la asignatura

#### ***Objetivos***. <a name="id2"></a>

Aquí explicamos los objetivos que se pretenden alcanzar al realizar la práctica.

#### ***Material empleado***. <a name="id3"></a>

Enumeramos el material empleado tanto hardware como software y las conficuraciones que hacemos (configuraciones de red por ejemplo) 

#### ***Desarrollo***. <a name="id4"></a>

En esta parte explicamos detalladamente los pasos que seguimos para realizar la práctica incluyendo capturas de pantalla y explicando que vemos en ellas. 

> ***IMPORTANTE:*** si estamos capturando una terminal no hace falta capturar todo el escritorio y es importante que se vea el nombre de usuario.

Si encontramos dificultades a la hora de realizar algún paso debemos explicar esas dificultades, que pasos hemos seguido para resolverla y los resultados obtenidos.

#### ***Conclusiones***. <a name="id5"></a>

En esta parte debemos exponer las conclusiones que sacamos del desarrollo de la prácica.

![](/capturas%20git-work/cap1.png "user1 - Creando repositorio")
<br>
**1.** Primero creamos el repositorio en el cual queremos realizar el proyecto, llamada "Git-work" 
<br>
<br>

![](/capturas%20git-work/cap2.png "user1 - Clonando repositorio")
<br>
**2.** Se clona el repositorio en local
<br>
<br>

![](/capturas%20git-work/cap3.png "user1 - Subiendo archivos")
<br>
**3.* El usuario 1 sube los archivos para iniciar el proyecto
<br>
<br>

![](/capturas%20git-work/cap4.png "user1 - Creando Issue #1")
<br>
**4.** Despues el usuario 1 crea un Issue para 
<br>
<br>


![](/capturas%20git-work/cap5.png "user1 - Agregando colaborador")
<br>
**5.** Debido a las complicaciónes de los fallos por el uso del fork, se añade un participante en el repositorio 
<br>
<br>

![](/capturas%20git-work/branch.png "user2 - Creando branch custom-text")
<br>
**6.** El usuario 2 crea una nueva rama para modificar el contenido del index.html 
<br>
<br>

![](/capturas%20git-work/html%20mod.png "user2 - Modificando archivo index.html")
<br>
**7.** Se modifica el titulo y la clase del titulo del html  
<br>
<br>

![](/capturas%20git-work/pr.png "user2 - Crea PR")
<br>
**8.** Despues el usuario 2 crea un el pull request hacia main para integrear sus cambios en esa rama, donde el usuario 1 tendrá la resposabilidad de aceptar dichos cambios 
<br>
<br>

![](/capturas%20git-work/cap6.png "user1 - Cambio a rama custom-text")
<br>
**9.** El usuario 1 va a la rama creada por el usuario 2 para ver sus cambios   
<br>
<br>
 

![](/capturas%20git-work/cap7.png "user1 - Cambios a index.html")
<br>
**10.** El usuario cree pertinente hacer una modificación al contenido del html para poder añadirlo al pull request  
<br>
<br>

![](/capturas%20git-work/cap8.png "user1 - Subiendo cambios a PR")
<br>
**11.** Se suben los cambios 
<br>
<br>

![](/capturas%20git-work/cap9.png "user1 - Comprobando PR")
<br>
**12.** Los cambios son añadidos al pull request correctamente    
<br>
<br>

![](/capturas%20git-work/cambio%20pr.png "user2 - Añade imagen index.html")
<br>
**13.** El usuario 2 añade una imagen pero al parecer no funciona 
<br>
<br>


![](/capturas%20git-work/cap10.png "user1 - Corrige imagen index.html")
<br>
**14.** El usuario 1 corrige dicha imagen
<br>
<br>

![](/capturas%20git-work/cap11.png "user1 - Respuesta conversacion")
<br>
**15.** Los 2 usuarios tienen una breve discusión sobre los cambios hechos 
<br>
<br>

![](/capturas%20git-work/cap12.png "user1 - Aprobando PR y cerrando Issue #1")
<br>
**16.** Después de la conversación, el usuario 1 aprueba el pull request y cierra la issue asociada  
<br>
<br>

![](/capturas%20git-work/cap13.png "user1 - Actualiza main")
<br>
**17.** Se actualiza la rama main
<br>
<br>

![](/capturas%20git-work/pull%20de%20los%20cambios.png "user2 - Actualiza custom-text")
<br>
**18.** El usuario 2 actualiza sus ramas
<br>
<br>

![](/capturas%20git-work/cap14.png "user1 - Creando Issue #3")
<br>
**19.** El usuario 1 crea la siguiente issue 
<br>
<br>

![](/capturas%20git-work/cap15.png "user1 - Cambio color cover.css")
<br>
**20.** El usuario 1 cambia el color en el archivo cover.css
<br>
<br>
 
![](/capturas%20git-work/cap16.png "user1 - Commit del cambio de color")
<br>
**21.** El usuario 1 sube dichos cambios 
<br>
<br>
 
![](/capturas%20git-work/cambiar%20color.png "user2 - Cambio color cover.css")
<br>
**22.** El usuario 2 tambien cambia el mismo color en el mismo archivo cover.css 
<br>
<br>
 
![](/capturas%20git-work/pull%20colores.png "user2 - Crea PR colores")
<br>
**23.** Luego el usuario 2 crea un pull request para subir sus cambios 
<br>
<br>
 
![](/capturas%20git-work/cap17.png "user1 - Merge ramas")
<br>
**24.** El usuario 1 acepta el pull request pero da un error de conflicto
<br>
<br>
 

![](/capturas%20git-work/cap18.png "user1 - Conflicto")
<br>
**25.** El usuario 1 ve el conflicto en el editor de texto vscode 
<br>
<br>
 

![](/capturas%20git-work/cap19.png "user1 - Resolviendo conflicto")
<br>
**26.** El usuario 1 elige quitar sus cambios de su rama y permitir los cambios del usuario 2 
<br>
<br>
 
![](/capturas%20git-work/cap20.png "user1 - Text-shadow cover.css")
<br>
**27.** El usuario 1 modifica el archivo cover.css para añadir una sombra 
<br>
<br>
 

![](/capturas%20git-work/cap21.png "user1 - Commit y Cerrando Issue #3")
<br>
**28.** Se suben los cambios y se cierra el issue
<br>
<br>
 
![](/capturas%20git-work/cap22.png "user1 - Creando etiqueta 0.1.0")
<br>
**29.** Se crea la etiqueta: "0.1.0"
<br>
<br>
 
![](/capturas%20git-work/cap23.png "user1 - Creando Realease")
<br>
**30.** Se crea una version release con la etiqueta 
<br>
<br>
 
![](/capturas%20git-work/cap24.png "user1 - Release Creada")
<br>
**31.** Despues ver que la version release está creada correctamente 
<br>
<br>
 
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

En este documento vamos a realizar la primera práctica de la asignatura de DPL

#### ***Objetivos***. <a name="id2"></a>

El objetivo de esta práctica es coger soltura con Git, además de aprender a manejar un repositorio remoto en colaboración con otras personas, simulando así ciertas situaciones que se pueden dar en nuestro futuro entorno de trabajo.

#### ***Material empleado***. <a name="id3"></a>

El manterial necesario es:
* Un ordenador plenamente funcional
* La terminal del sistema (Preferiblemente Linux)
* Una cuenta de GitHub

> ***IMPORTANTE:*** - Debido a problemas (aún sin explicación), hemos tenido que realizar el ejercicio añadiendo como colaborador al user2, ya que mediante la creación de un Fork nos impedía avanzar del paso 9 -

#### ***Desarrollo***. <a name="id4"></a>

En esta parte explicamos detalladamente los pasos que seguimos para realizar la práctica incluyendo capturas de pantalla y explicando que vemos en ellas. 

> ***IMPORTANTE:*** si estamos capturando una terminal no hace falta capturar todo el escritorio y es importante que se vea el nombre de usuario.

Si encontramos dificultades a la hora de realizar algún paso debemos explicar esas dificultades, que pasos hemos seguido para resolverla y los resultados obtenidos.

![](/capturas%20git-work/cap1.png "user1 - Creando repositorio")
<br>
**1.** Primero creamos el repositorio en el cual queremos realizar el proyecto, llamada "Git-work".
<br>
<br>

![](/capturas%20git-work/cap2.png "user1 - Clonando repositorio")
<br>
**2.** Se clona el repositorio en local.
<br>
<br>

![](/capturas%20git-work/cap3.png "user1 - Subiendo archivos")
<br>
**3.* El user1 sube los archivos para iniciar el proyecto.
<br>
<br>

![](/capturas%20git-work/cap4.png "user1 - Creando Issue #1")
<br>
**4.** Después el user1 crea un Issue llamado "Add custom text for startup contents".
<br>
<br>

![](/capturas%20git-work/cap5.png "user1 - Agregando colaborador")
<br>
**5.** Como se explicó anteriomente, debido a complicaciónes técnicas con la función Fork, se añade a user2 como colaborador en el repositorio.
<br>
<br>

![](/capturas%20git-work/branch.png "user2 - Creando branch custom-text")
<br>
**6.** El user2 crea una nueva rama llamda "custom-text" para modificar el contenido del index.html.
<br>
<br>

![](/capturas%20git-work/html%20mod.png "user2 - Modificando archivo index.html")
<br>
**7.** Se modifica el titulo y la clase del titulo del html.
<br>
<br>

![](/capturas%20git-work/pr.png "user2 - Crea PR")
<br>
**8.** Después el user2 crea un Pull Request hacia main para integrear sus cambios en esa rama, donde el user1 tendrá la resposabilidad de aceptar dichos cambios. 
<br>
<br>

![](/capturas%20git-work/cap6.png "user1 - Cambio a rama custom-text")
<br>
**9.** El user1 comprueba los cambios realizados por user2 cambiando a la rama "custom-text".
<br>
<br>

![](/capturas%20git-work/cap7.png "user1 - Cambios a index.html")
<br>
**10.** El user1 cree pertinente hacer una modificación al contenido del html para poder añadirlo al Pull Request.
<br>
<br>

![](/capturas%20git-work/cap8.png "user1 - Subiendo cambios a PR")
<br>
**11.** El user1 sube los cambios al Pull Request.
<br>
<br>

![](/capturas%20git-work/cap9.png "user1 - Comprobando PR")
<br>
**12.** Se comprueba que los cambios se han subido correctemente.
<br>
<br>

![](/capturas%20git-work/cambio%20pr.png "user2 - Añade imagen index.html")
<br>
**13.** El user2 añade una imagen al archivo index.html pero al parecer no funciona. 
<br>
<br>

![](/capturas%20git-work/cap10.png "user1 - Corrige imagen index.html")
<br>
**14.** El user1 corrige dicha imagen, remplazandolo por un placeholder indicando que debe ponerse una imagen.
<br>
<br>

![](/capturas%20git-work/cap11.png "user1 - Respuesta conversacion")
<br>
**15.** Los 2 usuarios tienen una breve discusión sobre los cambios hechos mediante la interfaz del Pull Request.
<br>
<br>

![](/capturas%20git-work/cap12.png "user1 - Aprobando PR y cerrando Issue #1")
<br>
**16.** Después de la conversación, el user1 aprueba el Pull Request y cierra la Issue asociada.  
<br>
<br>

![](/capturas%20git-work/cap13.png "user1 - Actualiza main")
<br>
**17.** El user1 actualiza la rama main con los cambios finales del Pull Request.
<br>
<br>

![](/capturas%20git-work/pull%20de%20los%20cambios.png "user2 - Actualiza custom-text")
<br>
**18.** El user2 también actualiza sus ramas.
<br>
<br>

![](/capturas%20git-work/cap14.png "user1 - Creando Issue #3")
<br>
**19.** El user1 crea un Issue llamado "Improve UX with cool colors". 
<br>
<br>

![](/capturas%20git-work/cap15.png "user1 - Cambio color cover.css")
<br>
**20.** El user1 cambia el color en el archivo cover.css a morado.
<br>
<br>
 
![](/capturas%20git-work/cap16.png "user1 - Commit del cambio de color")
<br>
**21.** El user1 realiza un commit de los cabios sin subirlo a su rama. 
<br>
<br>
 
![](/capturas%20git-work/cambiar%20color.png "user2 - Cambio color cover.css")
<br>
**22.** El user2 tambien realiza un cambio en el mismo archivo cover.css, pero esta vez a verde.
<br>
<br>
 
![](/capturas%20git-work/pull%20colores.png "user2 - Crea PR colores")
<br>
**23.** Luego el user2 crea un Pull Request para subir el cambio de color.
<br>
<br>
 
![](/capturas%20git-work/cap17.png "user1 - Merge ramas")
<br>
**24.** El user1 acepta el Pull Request creando un conflicto debido a la modificación simultanea del mismo archivo.
<br>
<br>

![](/capturas%20git-work/cap18.png "user1 - Conflicto")
<br>
**25.** El user1 se ayuda del VSCode para visualizar mejor el conflicto. 
<br>
<br>

![](/capturas%20git-work/cap19.png "user1 - Resolviendo conflicto")
<br>
**26.** El user1 elige quitar sus cambios de su rama y mantener los cambios realizados por el usuario 2.
<br>
<br>
 
![](/capturas%20git-work/cap20.png "user1 - Text-shadow cover.css")
<br>
**27.** El user1 modifica el archivo cover.css añadiendo una sombra para el texto. 
<br>
<br>
 

![](/capturas%20git-work/cap21.png "user1 - Commit y Cerrando Issue #3")
<br>
**28.** El user1 sube los cambios y cierra el Issue.
<br>
<br>
 
![](/capturas%20git-work/cap22.png "user1 - Creando etiqueta 0.1.0")
<br>
**29.** El user1 crea la etiqueta: "0.1.0".
<br>
<br>
 
![](/capturas%20git-work/cap23.png "user1 - Creando Realease")
<br>
**30.** Mediante esta etiqueta, el user1 crea una release ayudandose de GitHub.
<br>
<br>
 
![](/capturas%20git-work/cap24.png "user1 - Release Creada")
<br>
**31.** Finalmente, se comprueba la creación de la release y se finaliza la tarea.
<br>
<br>
 
 #### ***Conclusiones***. <a name="id5"></a>

En esta práctica hemos aprendido a trabajar de manera ordenada en Git, resolviendo conflictos y realizando buenas prácticas como los Pull Request. Es una buena manera de introducir a una persona sin conocimiento previo a las situaciones más comunes en un entorno de desarrollo.
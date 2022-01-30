Ejercicio-5
1. How do you see the files changed within each commit from git log?
Se utiliza cuando se necesita examinar la secuencia de commits (confirmaciones) que se ha realizado en la historia de un proyecto y qué estados se ha tenido a lo largo de la vida del reposito. 
Cuando tenemos el listado en nuestro terminal podemos observar los mensajes de los commits y su identificador, pero también se puede obtener mas informacion de un commit en concreto, modificaciones en el código, o tener la referencia para moverse hacia atrás en el histórico de commits.
De un commit podemos ver diversas informaciones básicas como:
Identificador del commit
Autor
Fecha de realización
Mensaje enviado

2. How do you see the contents of what changed within each file from the git log?
Los cambios se pueden observar por medio del comando GIT DIFF, este nos resalta a traves de un color el codigo añadido, y en rojo el codogo anterior.

3. What does HEAD refer to in the context of git? (Not to be confused with the "HEAD<<<<" one observes within merge conflict)
Este hace referencia al commit en el cual esta posicionado en cada momento, por regla general coincide con la ultima rama donde estes, porque habitualmente se esta trabajando en lo ultimo.
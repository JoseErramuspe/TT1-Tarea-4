Parte 1:
Git te instala una carpeta en la carpeta Usuario, Download ZIP te instala un ZIP en la carpeta Descargas.
Git te instala el repositorio con toda la información (ramas e historial de commits), Download ZIP te lo instala tal como estaba en el momento de la descarga.

Parte 2:
La función principal de README.md es explicar al usuario visitante lo fundamental del repositorio, por ejemplo, qué es lo que hace, cómo instalarlo, entre otras.

Parte 3:
La carpeta Estudiantes aparece como "untracked", esto se debe a que, como no se hizo un "git add", Git considera que no está incluido en el repositorio a pesar de que sabe que está ahí.

Parte 4:
La función del commit en Git es guardar los cambios que se hayan hecho al proyecto en el repositorio local. Esto permite también que se puedan guardar los cambios en el repositorio remoto con "git push".
Nota: Hice el commit antes de leer lo que decía en Evidencia, así que no pude hacer la captura del git status antes del commit

Parte 5:
Es recomendable porque así se pueden hacer cambios aislados sin necesidad de modificar la versión principal del proyecto, y en cualquier momento se pueden implementar los cambios de las otras ramas a la principal con "git merge".

Parte 6:
No se puede agregar hello.sh al repositorio. Esto es porque el archivo .gitignore evita que se agregue un archivo con ese nombre.
El archivo .gitignore sirve para que no se guarden archivos no deseados al repositorio, por ejemplo, archivos generados automáticamente, que sean muy pesados o que contengan información sensible.

Parte 7:
El Pull Request sirve para que, antes de editar el proyecto original, otros desarolladores puedan analizar los cambios que se quieren hacer al repo para comprobar qué es lo que se quiere hacer, si tiene errores, si se puede mejorar, entre otras cosas.

Parte 8:
1. Lo más sencillo de la tarea fue el uso de la consola de Git, ya que los comandos son fáciles de entender, y las instrucciones de la tarea eran fáciles de seguir.
2. No noté alguna dificultad para destacar. Creo que, a pesar de ser la tarea más larga hasta el momento, no fue muy complicado seguir lo que había que hacer. Si tuviera que decir alguna dificultad, serían algunas partes específicas de las instrucciones que no comprendí bien, como ponerle mi nombre y apellido a la rama que creé por ejemplo, pero en general creo que no tuve muchas complicaciones.
3. Con Git y Github se pueden compartir y editar carpetas, archivos, código, etc. con otros desarrolladores de una forma simple, se pueden analizar todos los cambios que se hicieron en el repo, en el caso que sea necesario se puede volver a una versión anterior, y se pueden crear ramas para un desarrollo más organizado del proyecto.
4. Considero que es muy útil, ya que se pueden realizar cambios en el proyecto sin necesidad de modificar la versión original, por lo que otros desarrolladores pueden hacer más ramas para hacer otro tipo de cambios sin alterar nada, haciendo que el desarrollo del proyecto sea más organizado.
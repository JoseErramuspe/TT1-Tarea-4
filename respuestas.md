Pregunta 1: Descargar un proyecto como archivo ZIP permite obtener solo una copia de los archivos en su estado actual, sin incluir el historial de cambios ni la conexión con el repositorio remoto. Clonarlo con git clone descarga el proyecto completo junto con su historial de versiones.

Pregunta 2:El archivo README.md tiene como función principal dar información y documentación sobre el proyecto, como su propósito, estructura, instrucciones de instalación, uso y otros detalles importantes para que cualquier persona pueda entender y trabajar en un proyecto fácilmente.

Pregunta 3:Al ejecutar git status, aparecen como archivos no rastreados (untracked) la carpeta Estudiantes y el archivo creado dentro de ella. Esto sucede porque son archivos nuevos creados localmente y Git aún no los incluye en el repositorio, ya que todavía no fueron agregados al área de preparación mediante git add.

Pregunta 4:Un commit en git sirve para guardar un conjunto de cambios en el historial del proyecto. Permite registrar una versión específica del trabajo realizado, facilitando el seguimiento, la recuperación y la colaboración entre los que están utilizándolo.

Pregunta 5: Es recomendable trabajar en ramas separadas porque permite desarrollar cambios sin afectar la rama principal. Además, facilita las pruebas, la organización del trabajo y la colaboración entre varias personas.

Pregunta 6: El archivo hello.sh no puede ser agregado al área de preparación porque está siendo ignorado por una regla definida en el archivo .gitignore. Por ese motivo git no lo muestra para ser versionado ni incluido en un commit.
El archivo .gitignore sirve para indicar a git qué archivos o carpetas no deben ser rastreados ni incluidos en los commits. Esto permite evitar subir archivos temporales, configuraciones locales o archivos generados automáticamente.

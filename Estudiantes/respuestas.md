RESPUESTAS

Parte 1
Cuando se descarga un proyecto como archivo ZIP se obtiene únicamente una copia de los archivos en ese momento, sin historial de versiones ni información de Git. En cambio, al clonar un repositorio con git clone, se descarga el proyecto completo junto con su historial de cambios, ramas y configuración, permitiendo trabajar con Git y colaborar con otros desarrolladores

Parte 3
Al ejecutar git status aparecen la carpeta Estudiantes y el archivo nombre_apellido.txt como archivos no rastreados (untracked), ya que fueron creados recientemente y Git aún no los está siguiendo. Una vez agregados con git add, pasan al área de preparación (staging) para ser incluidos en un commit.

Parte 4
Un commit permite guardar una versión específica del proyecto. Funciona como una foto del estado de los archivos en un momento determinado, registrando los cambios realizados para poder consultarlos o recuperarlos posteriormente.

Parte 5
Trabajar en ramas distintas de la rama principal permite realizar modificaciones y desarrollar nuevas funcionalidades sin afectar la versión estable del proyecto. Además, facilita la organización del trabajo, las pruebas y la colaboración entre varios desarrolladores.

Parte 6
El archivo hello.sh no aparece en la salida de git status porque está siendo ignorado por Git. Esto ocurre debido a que el archivo .gitignore contiene una regla que coincide con el nombre hello.sh, por lo que Git no lo rastrea ni lo considera para futuros commits.

El archivo .gitignore sirve para indicar qué archivos o carpetas deben ser ignorados por Git. Esto resulta útil para evitar incluir archivos temporales, ejecutables, dependencias o configuraciones locales que no deben compartirse en el repositorio.

Ejemplos:
.tmp
.exe
node_modules/
.log
hello.sh

Parte 7
Un Pull Request permite solicitar la incorporación de cambios realizados en una rama hacia otra rama. Además, facilita la revisión del código, la discusión de modificaciones y la detección de posibles errores antes de integrar los cambios al proyecto principal.
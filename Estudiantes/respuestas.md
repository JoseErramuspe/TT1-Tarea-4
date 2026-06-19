RESPUESTAS Nahirí Keusherian

Parte 1 y 2
Cuando se descarga un proyecto como archivo ZIP se obtiene únicamente una copia de los archivos en ese momento, sin historial de versiones ni información de Git. En cambio, al clonar un repositorio con git clone, se descarga el proyecto completo junto con su historial de cambios, ramas y configuración, permitiendo trabajar con Git y colaborar con otros desarrolladores. La función principal del archivo README.md es proporcionar información y documentación sobre el proyecto. Generalmente incluye una descripción del proyecto, instrucciones de instalación y uso, así como cualquier información relevante para que otros usuarios o desarrolladores puedan comprender y utilizar el repositorio correctamente.

![alt text](<Captura de pantalla 2026-06-19 082847-1.png>)
![alt text](<Captura de pantalla 2026-06-19 083142.png>)
![alt text](<Captura de pantalla 2026-06-19 083543.png>)

Parte 3 (imagen adjubtada arriba)
Al ejecutar git status aparecen la carpeta Estudiantes y el archivo nombre_apellido.txt como archivos no rastreados (untracked), ya que fueron creados recientemente y Git aún no los está siguiendo. Una vez agregados con git add, pasan al área de preparación (staging) para ser incluidos en un commit.

Parte 4
Un commit permite guardar una versión específica del proyecto. Funciona como una foto del estado de los archivos en un momento determinado, registrando los cambios realizados para poder consultarlos o recuperarlos posteriormente.

![alt text](<Captura de pantalla 2026-06-19 085111.png>)
![alt text](<Captura de pantalla 2026-06-19 085124.png>)

Parte 5
Trabajar en ramas distintas de la rama principal permite realizar modificaciones y desarrollar nuevas funcionalidades sin afectar la versión estable del proyecto. Además, facilita la organización del trabajo, las pruebas y la colaboración entre varios desarrolladores.

![alt text](<Captura de pantalla 2026-06-19 085219.png>)
![alt text](<Captura de pantalla 2026-06-19 085914.png>)

Parte 6
El archivo hello.sh no aparece en la salida de git status porque está siendo ignorado por Git. Esto ocurre debido a que el archivo .gitignore contiene una regla que coincide con el nombre hello.sh, por lo que Git no lo rastrea ni lo considera para futuros commits.

![alt text](<Captura de pantalla 2026-06-19 090149.png>)
![alt text](<Captura de pantalla 2026-06-19 090544.png>)
![alt text](<Captura de pantalla 2026-06-19 090745.png>)

El archivo .gitignore sirve para indicar qué archivos o carpetas deben ser ignorados por Git. Esto resulta útil para evitar incluir archivos temporales, ejecutables, dependencias o configuraciones locales que no deben compartirse en el repositorio.

Ejemplos:
.tmp
.exe
node_modules/
.log
hello.sh

Parte 7
Un Pull Request permite solicitar la incorporación de cambios realizados en una rama hacia otra rama. Además, facilita la revisión del código, la discusión de modificaciones y la detección de posibles errores antes de integrar los cambios al proyecto principal.

![alt text](<Captura de pantalla 2026-06-19 091654.png>)
![alt text](<Captura de pantalla 2026-06-19 091722.png>)
![alt text](<Captura de pantalla 2026-06-19 091735.png>)
![alt text](<Captura de pantalla 2026-06-19 091807.png>)
![alt text](<Captura de pantalla 2026-06-19 092046.png>)

Parte 8
Lo más sencillo de la tarea fue clonar el repositorio y explorar su estructura, ya que los comandos necesarios son simples y directos. 
Lo más difícil fue comprender el flujo completo de trabajo con Git, especialmente el uso de ramas, commits y Pull Requests. 
Git y GitHub ofrecen varias ventajas para el desarrollo de software. Permiten mantener un historial de cambios, trabajar en equipo, recuperar versiones anteriores y organizar el trabajo de manera más segura y eficiente.
Sí, considero útil el uso de ramas porque permiten realizar cambios de forma aislada sin afectar la versión principal del proyecto. Esto facilita las pruebas, la organización y la colaboración entre desarrolladores.

![alt text](<Captura de pantalla 2026-06-19 092706.png>)

perdón profe quiza algunas imagenes pueden estar en desorden, igual están todas las capturas!
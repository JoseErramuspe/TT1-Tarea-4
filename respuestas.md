1) ¿Qué diferencia existe entre descargar un proyecto como archivo ZIP (Code > Download ZIP) y clonarlo (git clone ) utilizando Git? 
Descargar un proyecto como ZIP permite obtener únicamente los archivos. En cambio, al clonarlo con Git se descarga el proyecto completo junto con su historial de cambios, lo que permite seguir trabajando con Git y GitHub de manera más eficiente. 
2) ¿Cuál es la función principal del archivo README.md dentro de un proyecto? 
El archivo README.md sirve para explicar de qué trata el proyecto y proporcionar información sobre su instalación, uso y funcionamiento.
3) ¿Qué archivos aparecen como modificados cuando ejecuta el comando? 
git status 
Explique brevemente por qué aparecen en dicho estado.
Aparece el archivo nombre_apellido.txt como archivo nuevo. Esto sucede porque lo creé recientemente y Git todavía no lo tiene guardado en un commit. Por eso aparece como un cambio pendiente.
4) ¿Cuál es la función de un commit dentro de Git? 
Un commit guarda una versión específica de los cambios realizados en el proyecto, permitiendo registrar el historial y volver a estados anteriores si es necesario.
5) ¿Por qué es recomendable trabajar en ramas diferentes a la rama principal? 
Es recomendable trabajar en ramas diferentes a la rama principal porque permite realizar cambios y pruebas sin afectar la versión principal del proyecto. De esta forma, los cambios pueden revisarse antes de incorporarse al proyecto definitivo. 
6) ¿Qué sucede con hello.sh? ¿Por qué?
El archivo hello.sh no aparece en git status porque está siendo ignorado por las reglas definidas en el archivo .gitignore.
¿Para qué sirve el archivo .gitignore? Cite ejemplos.
El archivo .gitignore sirve para indicar qué archivos o carpetas Git no debe controlar. Esto evita que se agreguen archivos innecesarios al repositorio. Por ejemplo, se pueden ignorar archivos temporales, archivos de configuración o scripts específicos como hello.sh.
7) ¿Qué función cumple un Pull Request dentro del flujo de trabajo colaborativo? 
Un Pull Request sirve para mostrar los cambios que hice en mi rama antes de agregarlos a la rama principal. De esta forma, los cambios pueden revisarse y comprobar que todo esté bien antes de unirlos al proyecto.
8) ¿Qué fue lo más sencillo de la tarea? Lo más sencillo fue crear y modificar archivos dentro del repositorio, ya que son tareas simples de realizar con VS Code.

¿Qué fue lo más difícil? Lo más difícil fue comprender el uso de ramas y la creación del Pull Request, porque era la primera vez que trabajaba con esas herramientas.

¿Qué ventajas observa en el uso de Git y GitHub para proyectos de software? Git y GitHub permiten guardar los cambios realizados en un proyecto, mantener un historial de versiones y facilitar el trabajo en equipo.

¿Considera útil el uso de ramas? Justifique su respuesta. Sí, considero útil el uso de ramas porque permiten trabajar en cambios o nuevas funciones sin afectar la versión principal del proyecto. Además, ayudan a mantener una mejor organización del trabajo.

1. La diferencia entre clonar el repositorio y descargarlo como comprimido es que al clonar el repositorio se obtienen tanto los archivos de la última versión del repositorio como todo el historial de versiones y referencias al repositorio original. Al descargarlo como ZIP solamente se obtienen los archivos de la última versión del repositorio.

2. Los archivos readme (léeme en español), de formato markdown, se utilizan para que el usuario conozca sobre el funcionamiento, la estructura, la utilización y otros datos que el creador del repositorio quiera dar a conocer. Es lo que se ve debajo de la estructura de carpetas y archivos cuando el usuario accede al repositorio desde GitHub. Ayuda a que el código y el funcionamiento del mismo sea más comprensible.

3. Al ejecutar git status, se muestra en pantalla que el repositorio clonado está actualizado con respecto al original y que existe una nueva carpeta llamada Estudiantes la cual no está siendo trackeada en el repositorio. Esto se debe a que en el repo original esta carpeta no existe, pero en el local si.

4. El comando git commit se utiliza para capturar el estado actual del repositorio en el que se está trabajando para que sea guardado en el historial de cambios del repositorio. Es como hacer un nuevo archivo de guardado en un videojuego, permitiendo la posibilidad de volver a ese punto de la historia en cualquier momento y restaurar los cambios realizados a ese punto en específico. Se puede utilizar git push para subir los cambios al repositorio original.

5. Es recomendable trabajar en ramas distintas a la original ya que permite mejor trabajo asincrónico, no borra los cambios realizados por otro contribuidor la rama original en caso de que estos cambios no existan en el repositorio local en el que se está trabajando y desde donde se están realizando los cambios, permite que varias personas trabajen en varias partes distintas del código al mismo tiempo o a tiempos distintos sin perder ningún progreso, ayuda a mejorar la legibilidad y estructura del repositorio y permite un mejor control de todos los cambios realizados.

6. El archivo “hello.sh” no fue añadido al staging ya que el archivo “.gitignore” estaba previniendo que este fuera añadido. Los archivos de este estilo sirven para mantener archivos no deseados (como archivos temporales) o que puedan contener información privada (Como llaves de una API de IA en un archivo .env) fuera del repositorio. Son varios los casos en los que debido a una utilización incorrecta del archivo “.gitignore” usuarios han logrado conseguir acceso a llaves de APIs de distintas IAs buscando en el código de distintos repositorios públicos de proyectos que utilizan IA.

7. Lo más sencillo de la tarea fue crear la estructura de archivos y escribir el código.

8. Lo más difícil fue entender los conceptos de qué es el pull, push, branch, commit y staging.

9. Utilizar git y GitHub para trabajar en un proyecto permite a varias personas trabajar de forma asincrónica, dividir las tareas para aumentar la eficiencia del trabajo, mantener un control estructurado y legible de las distintas versiones y permite mantener copias de seguridad de las distintas versiones del código del proyecto en caso de que algo salga mal.

10. El uso de ramas es útil ya que permite dividir las tareas para aumentar la eficiencia del trabajo, mantener un control estructurado y legible de las distintas versiones y no borrar los cambios realizados por otras personas en caso de que estos no se encuentren en la versión local del repositorio.
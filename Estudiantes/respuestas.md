Parte 1- Diferencias entre .zip y clonarlo con git: el .zip pierde todo registro anterior y se pierde el control de las versiones pasadas, mientras que clonandolo con git 
se conservan los cambios realizados en el projecto en instancias pasadas.

Parte 2- El README.md es un archivo para llevar control del proyecto (documentacion) y sirve como carta de presentacion para aquellos interesados en averiguar
de que se trata el proyecto.

Parte 3- Aparece asi porque por mas que yo haya agregado el archivo a la carpeta y lo haya modificado, no use "git add" para que le haga tracking.

Parte 4- La funcion de un commit es guardar los cambios, con opcion de dejar un mensaje.

Parte 5- Sirve trabajar en ramas diferentes a la principal para evitar situaciones en las que, por ejemplo, mas de una persona necesita
modificar el archivo. De esta manera se pueden evitar conflictos al no estar todos modificando la misma linea de codigo.
Esto permite hacer los cambios de manera aislada, y despues se puede hacer el merge para unirlas.

Parte 6- *el archivo .gitignore hace que git ignore al archivo hello.sh
         *con .gitignore se puede pedir que git no trackee ciertos archivos y/o directorios. Sirve para mantener limpio el repositorio,
          leyendo solo los archivos necesarios para el proyecto en cuestion.

Parte 7- Un pull request es la herramienta central para hacer proyectos en equipo. Sirve para no modificar directamente la rama principal, evitar que codigo defectuoso llegue a produccion y se asegura mejor calidad y mejores practicas

Parte 8- 1- no fue tan complicado entender los comandos de git
         2- en mi caso lo mas dificil fue hacer el pull request porque me quedaba que el main era igual a mi tarea4-federicorios, impidiendome progresar tranquilamente (solucionado)
         3- la creacion de ramas y github es bastante usado por lo que debe ser bastante bueno
         4- Es bastante util porque en casos ya nombrados como un trabajar en un mismo proyecto con varias personas, se hace dificil tener a todos editando la rama principal por los diferentes conflictos que se pudieran llegar a dar. El uso de ramas permite hacer las cosas por separado y una vez verificadas y dadas como correctas unirlas a la rama principal.
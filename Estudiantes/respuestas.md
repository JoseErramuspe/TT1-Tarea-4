1- Pregunta
¿Qué diferencia existe entre descargar un proyecto como archivo ZIP (Code > Download ZIP) y clonarlo (git clone <url>) utilizando Git?

- La diferencia radica en el hecho de que al descargar el archivo como un zip se pierden todos los registros de historial y del control de versiones, por mas que se puedan generar cambios a posterior con el archivo y esos cambios se van a guardar, todo lo pasado se pierde, a diferencia de usar "git clone <url>" donde al clonar todo el proyecto, también vas a conservar los cambios realizados en el.

Parte 2:
Pregunta
¿Cuál es la función principal del archivo README.md dentro de un proyecto?

la principal función del archivo README.md es servir como "una carta de presentación" para aquellos que quieran ver de que se trata nuestro proyecto, en el se incluye la información básica del proyecto, tal como de que trata, los pasos básicos seguidos para la construcción del mismo, el objetivo del mismo, como instalarlo y usarlo, etc. 

Parte 3:
Pregunta
¿Qué archivos aparecen como modificados cuando ejecuta el comando?

git status

Explique brevemente por qué aparecen en dicho estado.

- los archivos aparecen en este estado porque por mas que yo haya agregado el archivo a la carpeta y lo haya modificado, no use "git add" para que git le haga tracking a mi archivo, el ya es consciente que existe, sabe que lo modifique, pero si no le pido que lo siga no lo va a tomar en cuenta para, si después guardo los cambios en mi proyecto (que seria lo ideal), los translade a una nueva version del proyecto.

Parte 4
Aclaración: me olvide de hacer una captura de pantalla en el momento anterior de crear un commit con los cambios realizados.
Pregunta
¿Cuál es la función de un commit dentro de Git?

-La función de un commit dentro de git es la de guardar los cambios realizados en el proyecto en una nueva version del mismo, en la cual se podrá consultar mas adelante en el historial todas las versiones del mismo y trabajar con la que sea de nuestra conveniencia. 

Parte 5
Pregunta
¿Por qué es recomendable trabajar en ramas diferentes a la rama principal?

-Es recomendable trabajar en ramas diferentes a la principal para varias situaciones, por ejemplo, si se quiere realizar un cambio en el proyecto se puede crear una rama, codificar, y ver si funciona el codigo antes de traerlo a la rama principal para evitar que el proyecto se rompa. Tambien es muy util cuando trabajas con varias personas, en vez de trabajar todos en la misma rama y que surgan conflictos, es muy saludable crear una rama para cada miembro distinta a la original donde cada uno trabaja de manera aislada, de esta manera, el codigo no sufre modificaciones de varias personas a la vez, donde mas de una persona puede modificar el mismo codigo a la vez.

Parte 6
Preguntas
¿Qué sucede con hello.sh? ¿Por qué?
¿Para qué sirve el archivo .gitignore? Cite ejemplos.

Hello.sh no puede ser trackeado por git debido a que el profesor utilizo el archivo .gitignore, el cual sirve para que git no trackee (ignore) ciertos archivos o directorios que no se desean guardar por el momento en los cambios del proyecto. Algunos de sus propositos principales son mantener el repositorio limpio con archivos solo necesarios para el proyecto, proteger informacion sensible como contraseñas o datos confidenciales, excluir archivos temporales, etc. Precisamente porque le pedimos al .gitignore que ignore el hello.sh es que no se puede incluir dentro del stagging
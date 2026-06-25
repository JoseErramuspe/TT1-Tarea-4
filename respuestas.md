# Respuestas - Tarea 4

## Parte 1
¿Qué diferencia existe entre descargar un ZIP y clonar con Git?
el ZIP te da solo una copia fija de los archivos, mientras que clonar con Git te da el proyecto completo, con su historial, y conectado al repositorio para poder seguir trabajando en equipo.

## Parte 2
¿Cuál es la función del README.md?
Readme sirve para explicar como funciona un proyecto/ dar instrucciones de uso/ explicar de que se trata, etc. Puede dar instrucciones de cualqueir cosa, a veces poner derechos de copyrigth y mas. Md sirve para poner titulos negritas, listas y mas.

## Parte 3
¿Qué archivos aparecen como modificados en git status?
Al ejecutar git status, aparece como modificado (más específicamente, como "untracked" o no rastreado) el archivo estudiantes/Luciano_Liori.txt. Esto sucede porque Git solo hace seguimiento de los archivos que en algún momento fueron agregados explícitamente al repositorio mediante git add. Como esta carpeta y archivo se crearon recién ahora y nunca fueron agregados al área de preparación (staging), Git los detecta como contenido nuevo que todavía no forma parte del historial del proyecto, y por eso los marca como "untracked files".

## Parte 4
¿Cuál es la función de un commit?
Un commit es básicamente un "guardado" del estado completo de tus archivos. Aparece quien lo hizo, cuando lo hizo, el mensaje q le puse y un link al commit anterior.

## Parte 5
¿Por qué es recomendable trabajar en ramas diferentes a la rama principal?

Trabajar en una rama distinta a la principl permite hacer cambios, probar cosas o cometer errores sin afectar la versión principal y estable del proyecto. Además, en proyectos colaborativos, esto permite que varias personas trabajen en distintas funcionalidades al mismo tiempo sin pisarse el trabajo entre sí.

## Parte 6
¿Qué sucede con hello.sh? ¿Por qué?

Al intentar agregar hello.sh con git add, Git rechaza la operación y avisa que el archivo está siendo ignorado por una regla del archivo .gitignore.  Por eso, aunque el archivo existe físicamente en la carpeta, Git lo trata como si no existiera.

¿Para qué sirve el archivo .gitignore? Cite ejemplos.

El archivo .gitignore le indica a Git qué archivos o carpetas debe ignorar y no rastrear, para evitar que terminen subidos al repositorio. Esto es útil para excluir archivos que no aportan valor al código fuente o que son específicos de cada máquina/usuario, como por ejemplo: archivos temporales o de configuración del editor (.vscode/, .DS_Store) o binarios (*.exe, *.class, *.pyc), archivos de configuración con datos sensibles (.env, donde suelen guardarse contraseñas o claves de API), y logs . De esta forma, el repositorio se mantiene limpio, liviano y sin información que no debería compartirse públicamente.

## Parte 7
¿Qué función cumple un Pull Request dentro del flujo de trabajo colaborativo?

Un Pull Request (PR) es una solicitud formal para integrar los cambios de una rama (en este caso, tarea4-lucianoliori) a otra rama, generalmente la principal (main). 

## Parte 8 - Reflexión final

### ¿Qué fue lo más sencillo de la tarea?

No me resultó compleja, ya que tenía conocimiento previo de Git y GitHub. De todas formas, si tengo que considerar una parte como menos compleja, sería la creación del archivo con mi nombre y mis datos.

### ¿Qué fue lo más difícil?

Lo más difícil en su momento fue hacerle el push de mi carpeta al repositorio, ya que no tenía los permisos. Cuando el profesor me dio acceso, el trabajo se facilitó, ya que yo tenía pensado hacer un fork al repositorio.

### ¿Qué ventajas observa en el uso de Git y GitHub para proyectos de software?

En mi caso, para el primer obligatorio de Taller, Git y GitHub fueron pilares para el trabajo en equipo. Usamos Git para probar que estuviera funcionando todo lo que hacíamos, y utilizamos un repositorio que abrimos desde VS Code, al que íbamos pusheando los cambios, así podíamos ir trabajando cada uno desde sus casas, teniendo las versiones anteriores y también en cuenta los cambios que hizo el otro.

### ¿Considera útil el uso de ramas? Justifique su respuesta.

Asimismo, como me refería en la pregunta anterior, usar ramas nos permitió poder avanzar teniendo un backup en caso de un error fatal que rompiera el trabajo.
# Taller de Tecnologías 1 - Tarea 4

## Requisitos

- Cuenta de [GitHub](https://github.com/).
- [Git](https://git-scm.com/install/) instalado en el equipo.
- [Visual Studio Code](https://code.visualstudio.com/download?_exp_download=fb315fc982) instalado en el equipo.
- Acceso al [repositorio en GitHub](https://github.com/NicoVG12/TT1-Tarea-4).
---

# Parte 1: Clonación del repositorio

- Acceder al [repositorio en GitHub](https://github.com/NicoVG12/TT1-Tarea-4).
- Copiar su URL


![Copiar URL del repositorio](/Images/01-clone.png)

- Clonar el repositorio utilizando git

    ```bash
    git clone https://github.com/NicoVG12/TT1-Tarea-4
    ```

- Situarse dentro del repositorio

    ```bash
    cd TT1-Tarea-4
    ```

- Abrir la carpeta con Visual Studio Code

    ```bash
    code .
    ```



### Evidencia

Adjuntar captura de pantalla donde se observe:
- La ejecución exitosa del comando de clonación del repo.
- La carpeta que contiene al repo local


### Pregunta

- ¿Qué diferencia existe entre descargar un proyecto como archivo ZIP (`Code > Download ZIP`) y clonarlo (`git clone <url>`) utilizando Git?

---

# Parte 2: Exploración del repositorio

1. Revise la estructura de carpetas.
2. Abra el archivo `README.md`.
3. Lea las instrucciones incluidas.

### Evidencia

Adjunte una captura mostrando la estructura del proyecto.

### Pregunta

¿Cuál es la función principal del archivo `README.md` dentro de un proyecto?

---

# Parte 3: Modificación de archivos

1. Cree una carpeta llamada:

   ```text
   Estudiantes
   ```

2. Dentro de ella cree un archivo:

   ```text
   nombre_apellido.txt
   ```

3. Escriba la siguiente información:

   - Nombre completo
   - Número de estudiante
   - Carrera
   - Semestre

### Evidencia

Adjunte una captura mostrando el archivo creado.

### Pregunta

¿Qué archivos aparecen como modificados cuando ejecuta el comando?

```bash
git status
```

Explique brevemente por qué aparecen en dicho estado.

---

# Parte 4: Primer Commit

1. Agregue los cambios al área de preparación (*staging*).
2. Cree un commit con el mensaje (o similar):

   ```text
   Add: student info
   ```

### Evidencia

Adjunte una captura mostrando:

```bash
git status
```

antes y después del commit.

### Pregunta

¿Cuál es la función de un commit dentro de Git?

---

# Parte 5: Trabajo con ramas

1. Cree una rama llamada:

   ```text
   tarea4-nombreapellido
   ```

2. Cambie a dicha rama.
3. Cree un archivo llamado:

   ```text
   respuestas.md
   ```

4. Escriba las respuestas de las preguntas anteriores.

### Evidencia

Adjunte una captura mostrando:

```bash
git branch
```

y la rama actual seleccionada.

### Pregunta

¿Por qué es recomendable trabajar en ramas diferentes a la rama principal?


---

# Parte 5: .gitignore

1. Cree un script bash llamado:

   ```text
   hello.sh
   ```

2. Agregue las líneas:

   ```bash
   #!/bin/bash

   echo hello.sh
   ```

3. Ejecute el script.

4. Agregue el commit al área de preparación (*staging*)

5. Revise el estado mediante:

   ```bash
   git status
   ```

6. Revise el archivo **.gitignore**

### Evidencia

Adjunte una captura mostrando:

```bash
git status
```

### Preguntas

* ¿Qué sucede con hello.sh? ¿Por qué?
* ¿Para qué sirve el archivo **.gitignore**? Cite ejemplos.


---

# Parte 7: Publicación en GitHub

1. Realice un nuevo commit con el mensaje:

    ```bash
    Add: respuestas.md
    ```

1. Suba su rama al repositorio remoto.
2. Cree un Pull Request hacia la rama principal.

### Evidencia

* Adjunte una captura de la rama publicada en GitHub.
* Adjunte una captura del Pull Request creado.

### Pregunta

¿Qué función cumple un **Pull Request** dentro del flujo de trabajo colaborativo?

---

# Parte 8: Reflexión final

Responda las siguientes preguntas:

1. ¿Qué fue lo más sencillo de la tarea?
2. ¿Qué fue lo más difícil?
3. ¿Qué ventajas observa en el uso de Git y GitHub para proyectos de software?
4. ¿Considera útil el uso de ramas? Justifique su respuesta.

---

1. Realice un nuevo commit con el mensaje:

    ```bash
    Update: respuestas.md
    ```
2. Suba sus cambios al repositorio remoto y revise que se visualicen en la Pull Request creada.
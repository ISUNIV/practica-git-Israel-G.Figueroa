# Práctica de Git y GitHub

* **Nombre del estudiante:** Israel G. Figueroa
* **Matrícula:** 2630192
* **Nombre de la práctica:** Crear un repositorio local utilizando Git y sincronizarlo con GitHub.

## Objetivo de la práctica
Crear un repositorio local utilizando Git, sincronizarlo con un repositorio remoto en GitHub y comprobar el flujo de trabajo en ambos sentidos (Local a Remoto y viceversa).

## Descripción del procedimiento realizado
1. **Creación del entorno:** Creé una carpeta específica para la práctica en mi escritorio y abrí la consola de PowerShell en esa ubicación.
2. **Inicialización local:** Inicialicé el repositorio de Git y renombré la rama principal a `main`. Posterior a eso, creé los archivos solicitados.
3. **Registro de cambios:** Utilicé el Staging Area para preparar los archivos y realicé el primer commit de forma local.
4. **Vinculación remota:** Creé un repositorio vacío en GitHub, lo vinculé a mi entorno local y subí mis archivos usando comandos de Git.
5. **Prueba de flujo bidireccional:** Realicé una modificación directa desde la interfaz web de GitHub y la descargué a mi computadora. Luego, hice otra modificación en mi entorno local y la subí exitosamente a la nube.

## Comandos de Git utilizados y su función
* `git init`: Inicializa un nuevo repositorio de Git en la carpeta actual, creando una carpeta oculta `.git`.
* `git branch -M main`: Renombra de forma forzada la rama principal actual del repositorio local a `main`.
* `git status`: Muestra el estado actual del repositorio de trabajo, indicando qué archivos han sido modificados, agregados o cuáles no tienen seguimiento.
* `git add .`: Agrega todos los archivos nuevos y modificados de la carpeta actual al Staging Area (área de preparación).
* `git commit -m "mensaje"`: Guarda de forma permanente en el historial del repositorio los cambios que estaban en el Staging Area, asignándoles un mensaje descriptivo.
* `git remote add origin [URL]`: Vincula el repositorio local con un repositorio remoto en GitHub bajo el nombre por defecto 'origin'.
* `git remote -v`: Permite verificar los enlaces remotos (URLs de lectura y escritura) que están conectados al repositorio local.
* `git push -u origin main`: Sube los commits locales de la rama `main` al repositorio remoto 'origin' por primera vez, estableciendo una relación de seguimiento entre ambas ramas.
* `git pull origin main`: Descarga y fusiona los últimos cambios que existen en el repositorio remoto directamente en la rama local.
* `git push`: Sube los nuevos commits locales al repositorio remoto una vez que la relación entre ramas ya fue establecida.

## Descripción de los archivos contenidos
* **README.md:** Archivo en formato Markdown que contiene toda la documentación del proyecto, datos del alumno y explicación de los pasos.
* **datos.txt:** Archivo de texto plano utilizado para experimentar con las modificaciones de Git tanto de manera local como de manera remota.

## Conclusión personal
En general aprendí un poco mas sobre la programación, tanto para el uso de Powershell, códigos, comandos de git y GitHub; supongo que Git es muy util para la carrera ya que es gracias a sus comandos que podemos desarrollar, modificar y sincronizar datos de nuestro equipo y vincularlos a la red de GitHub; el proceso de esta Tarea me pareció interesante e intuitivo.

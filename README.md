# Taller Interactivo de Python para GitHub Pages

Este paquete contiene la aplicación web del taller interactivo de Python, estructurado específicamente para publicarse en **GitHub Pages**. 

## Instrucciones para publicar en GitHub Pages:

1. Extrae los archivos de este `.zip`.
2. Ve a tu cuenta de [GitHub](https://github.com/) y crea un **nuevo repositorio** público (ejemplo: `taller-python`).
3. Sube el archivo `index.html` (y este README si lo deseas) directamente a la rama `main` del repositorio.
4. En tu repositorio, haz clic en la pestaña **Settings** (Configuración).
5. En la barra lateral izquierda, selecciona **Pages** (Páginas).
6. Bajo la sección "Build and deployment", asegúrate de que el **Source** sea "Deploy from a branch".
7. Selecciona la rama **`main`** y haz clic en **Save**.

En un par de minutos, tu taller interactivo estará publicado y disponible para cualquier estudiante a través del enlace que GitHub te proporcionará (normalmente será `https://<tu-usuario>.github.io/taller-python`).

### Notas técnicas:
* Esta versión incluye el intérprete original con **CodeMirror** y **Skulpt** vía CDNs de alta velocidad, lo que garantiza una excelente respuesta y coloreado de sintaxis (imposible de usar en LMS cerrados como Schoology).
* La función `input()` utiliza la ventana de ingreso nativa del navegador, la cual no será bloqueada por GitHub Pages.
* El sistema guarda internamente la progresión en el navegador del estudiante, pero al ser un sitio web estático no enviará las notas a ninguna plataforma LMS.

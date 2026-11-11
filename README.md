# Cantes — registro de alumnos de judicatura

App web para llevar los cantes de cada alumno: temas que trae, sorteo, cronómetro, apuntes, examen y vuelta de temas.
Funciona sin conexión y se puede añadir a la pantalla de inicio del iPhone.

## Publicarla con GitHub Pages

1. Entra en https://github.com y crea un repositorio nuevo (por ejemplo `cantes`). Puede ser público.
2. En el repositorio pulsa **Add file → Upload files** y sube estos archivos:
   `index.html`, `manifest.json`, `sw.js`, `icon-180.png`, `icon-192.png`, `icon-512.png`.
   Pulsa **Commit changes**.
3. Ve a **Settings → Pages**. En *Source* elige **Deploy from a branch**, rama **main**, carpeta **/ (root)** y **Save**.
4. En uno o dos minutos la app estará en `https://TU-USUARIO.github.io/cantes/`.

## Añadirla al iPhone

1. Abre esa dirección en **Safari**.
2. Pulsa el botón **Compartir** → **Añadir a pantalla de inicio**.
3. Se abrirá a pantalla completa como una app, con el icono de la balanza.

## Importante sobre los datos

- Los datos se guardan **solo en el dispositivo** (no se suben a GitHub ni a ningún servidor). El repositorio solo contiene la app vacía.
- Usa **Exportar** (pantalla de inicio de la app) de vez en cuando para guardar una copia, por ejemplo en Archivos o enviándotela por correo. Con **Importar** la recuperas o la pasas a otro dispositivo.
- Si borras la app de la pantalla de inicio, iOS puede borrar sus datos: exporta antes.

## Actualizar la app

Si cambias algún archivo, súbelo de nuevo al repositorio y cambia `cantes-v1` por `cantes-v2` (etc.) en `sw.js` para que el iPhone descargue la nueva versión. Los datos de los alumnos no se pierden al actualizar.

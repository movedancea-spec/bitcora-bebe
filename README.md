# Bitácora — Diario del bebé 🍼

Una app sencilla de una sola página para llevar registro de las comidas y novedades diarias
de tu bebé (palabras nuevas, diarrea, fiebre, cómo comió, etc.), pensada para que **cualquier
persona que lo cuide** la pueda usar sin complicaciones.

- Colores que cambian a **azul** (niño), **rosado** (niña) o **morado neutro**, desde Ajustes.
- Todo se guarda automáticamente en el navegador del dispositivo donde se usa.
- Se puede **exportar** un respaldo (.json) para compartir por WhatsApp/correo con otros
  cuidadores o con el pediatra, e **importarlo** en otro dispositivo.
- No necesita instalación, servidor, ni base de datos: es un solo archivo `index.html`.

## Cómo publicarla en GitHub Pages (gratis)

1. Entra a [github.com](https://github.com) y crea una cuenta si no tienes una.
2. Crea un repositorio nuevo (botón verde **"New"**), dale un nombre como `bitacora-bebe`,
   y márcalo como **Public**. No marques "Add a README" (ya tienes uno).
3. Dentro del repositorio, haz clic en **"Add file" → "Upload files"**.
4. Arrastra el archivo `index.html` (y este `README.md` si quieres) y presiona **"Commit changes"**.
5. Ve a **Settings → Pages** (menú de la izquierda).
6. En "Branch", selecciona `main` y la carpeta `/ (root)`, luego **Save**.
7. Espera 1–2 minutos y GitHub te dará un enlace como:
   `https://tu-usuario.github.io/bitacora-bebe/`
8. Comparte ese enlace con quien cuide al bebé — pueden abrirlo desde el celular y
   **agregarlo a la pantalla de inicio** (en Chrome/Safari: menú → "Agregar a pantalla de inicio")
   para que se sienta como una app.

## Importante sobre los datos

Como es una página sin servidor, los registros se guardan **solo en el navegador de cada
dispositivo**. Si dos personas la usan desde celulares distintos, cada una tendrá su propio
registro por separado. Para juntar la información:

- Usa el botón **"Exportar respaldo"** en Ajustes para descargar un archivo `.json`.
- Envíalo a la otra persona, y que use **"Importar respaldo"** en su propio dispositivo.

Si más adelante quieres que **todos vean lo mismo en tiempo real** (sin exportar/importar),
se puede agregar una base de datos gratuita (por ejemplo Firebase o Supabase) — avísame y
te ayudo a ese siguiente paso.

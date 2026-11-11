# B2 First Trainer v4

## Novedades
- Biblioteca de tests numerados por sección.
- Marca ✓ y progreso para tests completados.
- Shorts diarios: dos ejercicios seleccionados automáticamente para cada fecha.
- Apartados separados para Reading & Use, Listening, Writing, Speaking y Grammar & Vocabulary.
- Botón «Otro ejercicio» que propone un test pendiente de esa sección.
- Buscador de tests.
- Historial y estadísticas guardados localmente.
- Diseño responsive y PWA básica.

## Actualizar GitHub Pages desde el móvil
1. Descarga y descomprime `B2_First_Trainer_v4.zip` en Archivos.
2. Abre tu repositorio `b2-first-trainer` en GitHub.
3. Add file → Upload files.
4. Sube y reemplaza `index.html`, `exercises.json`, `manifest.webmanifest`, `sw.js` y `README.md` desde la carpeta descomprimida.
5. Pulsa Commit changes. GitHub Pages publicará la actualización automáticamente.
6. Si ves la versión anterior, cierra la pestaña y vuelve a abrir la web; si persiste, borra los datos/caché del sitio o espera a que se actualice el service worker.

## Importante
- Esta versión usa `exercises.json` como banco de ejercicios y localStorage para el progreso. No es una base de datos online compartida: el progreso queda en ese navegador/dispositivo.
- Los shorts diarios se eligen a partir de la fecha actual y el banco disponible. En esta primera biblioteca hay 17 tests; se pueden añadir más editando `exercises.json`.
- Listening usa guiones originales como transcripciones, no grabaciones.
- Writing y Speaking tienen autoevaluación, no corrección oficial Cambridge.
- Los ejercicios son originales y no reproducen en bloque contenido de English Revealed.

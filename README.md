# Mi Rutina (Mary)

Rutina en casa (4 días, 30-40 min) con modo guiado, imágenes de cada ejercicio, registro de peso, medidas y datos del Cubitt. Funciona sin internet. Los datos viven **solo en el teléfono**.

## Publicar en GitHub Pages
1. Sube a la raíz: `index.html`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png`, `icon-512-maskable.png` y `README.md`. Las 31 fotos ya van dentro de `index.html`.
2. Settings → Pages → Deploy from a branch → `main` / `(root)`.
3. Espera 1-2 min y abre la dirección que muestra Pages.

## Instalar (Android, Chrome)
Abre la dirección → menú ⋮ → **Instalar app**. Ábrela una vez con internet para que guarde todo; después funciona sin conexión.

## Respaldo
Ajustes → **Exportar respaldo** cada semana (Drive o WhatsApp). Restaurar: **Importar JSON o CSV**. Las imágenes y el logo no van en el respaldo.

## Actualizar
Cambia `CACHE` en `sw.js` (rutina-v4 → rutina-v5) y sube los archivos. En la app toca **↻**. No borra datos.

## Cambios
- v4 (2026-11-13): las 31 imágenes van dentro de index.html.
- v3 (2026-11-13): 31 imágenes incluidas, logo nuevo, íconos instalables, caché que no toca a FitCoach.

# 安気 (Anqui)

App de tarjetas de repaso espaciado, hecha como web app instalable (PWA). Gratis, sin cuenta y funciona sin internet.

- Algoritmo SM-2 como Anki, con tres respuestas: もう一度 (10 min) / 正解 (1 día) / 簡単 (4 días)
- Un solo mazo, que arranca con las 333 palabras de **Favoritos** en japonés (lectura + significado)
- Pronunciación en japonés con la voz del sistema
- Importar desde texto, exportar y restaurar copias de seguridad
- Colores del sistema de diseño de Empujón; fuentes Inclusive Sans + Noto Sans JP

## Instalar en el iPhone

1. Abrí la página publicada (GitHub Pages) en **Safari**.
2. Compartir → **Agregar a pantalla de inicio**.

Las tarjetas y el progreso se guardan solo en el teléfono. Exportá una copia de vez en cuando desde Ajustes.

## Publicar con GitHub Pages

Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)`.

## Archivos

- `index.html`: toda la app
- `sw.js`: service worker (modo sin internet)
- `manifest.webmanifest` e `icon-*.png`: instalación e ícono
- `favoritos.json`: mazo inicial de vocabulario

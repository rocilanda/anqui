# Anqui

App de tarjetas de repaso espaciado (estilo Anki) para iPhone, hecha como web app instalable (PWA). Gratis, sin cuenta y funciona sin internet.

- Algoritmo SM-2 como Anki (Otra vez / Difícil / Bien / Fácil)
- Mazo inicial **Favoritos** con 333 palabras en japonés (lectura + significado)
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

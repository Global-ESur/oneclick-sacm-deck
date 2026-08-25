# OneClick License · Propuesta para SACM

Deck HTML autocontenido (fuentes e imágenes embebidas en base64, sin dependencias externas) con la propuesta de OneClick License para SACM.

## Estructura

- `index.html` — el deck completo. Es un único archivo estático, sin build ni dependencias.

## Deploy en Vercel

Este repo no necesita build step: es HTML estático puro.

1. Importar el repo en [Vercel](https://vercel.com/new).
2. Framework Preset: **Other** (o "Static").
3. Build Command: dejar vacío.
4. Output Directory: dejar el default (`.`) — Vercel detecta `index.html` en la raíz automáticamente gracias a `vercel.json`.
5. Deploy.

También se puede previsualizar localmente abriendo `index.html` directo en el navegador, sin servidor.

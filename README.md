# 🌿 EcoTrack — Web App (PWA)

App móvil que funciona escaneando un QR, sin instalar nada.
Proyecto Innova Schools 2025 · San Isidro Etapa 2.

## Cómo publicarla (gratis, en 5 minutos)

### Paso 1 — Sube el código a GitHub

```bash
git init
git add .
git commit -m "EcoTrack PWA"
git remote add origin https://github.com/TU_USUARIO/ecotrack.git
git push -u origin main
```

### Paso 2 — Activa GitHub Pages

1. Ve a tu repo en github.com
2. Settings → Pages
3. Source: **Deploy from a branch**
4. Branch: **main** → carpeta **/ (root)**
5. Guarda

En 1-2 minutos tu app estará en:
**https://TU_USUARIO.github.io/ecotrack**

### Paso 3 — Genera el QR

Ve a cualquier generador de QR (por ejemplo qr-code-generator.com) y pega la URL de GitHub Pages. ¡Listo!

### Paso 4 — Pruébalo

Cualquier persona que escanee el QR abre la app en su celular.
En Android puede instalarla como app real (aparece un banner "Agregar a pantalla de inicio").

## Archivos

```
ecotrack-web/
├── index.html     # Toda la app (HTML + CSS + JS)
├── manifest.json  # Hace que sea instalable
├── sw.js          # Funciona sin internet
└── README.md
```

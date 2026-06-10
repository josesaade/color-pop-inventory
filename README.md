# Color Pop

Mini PWA de consulta rápida del inventario de outfits por enfoque de color.

Muestra cuántos outfits disponibles quedan de cada uno de los 12 enfoques JoJo, leyendo directamente desde Supabase.

## Stack

- HTML / CSS / JS puro — archivo único `index.html`
- Supabase REST API (sin SDK)
- Google Fonts — Syne + DM Mono
- Service Worker para instalación PWA

## Archivos

```
color-pop-inventory/
├── index.html      ← toda la app
├── manifest.json   ← config PWA
├── sw.js           ← service worker
├── icon-192.png    ← ícono PWA (agregar manualmente)
└── icon-512.png    ← ícono PWA (agregar manualmente)
```

## Íconos

Los archivos `icon-192.png` e `icon-512.png` deben agregarse manualmente al repo. Sin ellos la app funciona pero no es instalable correctamente desde iOS/Android.

## Deploy

Conectar el repo a Netlify como nuevo site. Publish directory: `/` (raíz).

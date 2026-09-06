# Geopolítica IA — V1

Página web estática preparada para GitHub Pages y Supabase.

## Configuración

1. Abre `index.html`.
2. Busca:
   `window.SUPABASE_ANON_KEY = ...`
3. Añade la Publishable key (o la clave `anon` antigua) de Supabase.
4. NO uses nunca `service_role` ni una secret key.
5. Sube estos tres archivos a un repositorio de GitHub.
6. Activa GitHub Pages desde Settings → Pages → Deploy from branch.

## Archivos

- index.html
- style.css
- app.js

La V1 lee `sources`, `articles` y `events` mediante la API REST de Supabase.

# Floservice — Sitio web

Sitio web de **Servicios Integrales Flo Service SpA** (Puerto Varas, Región de Los Lagos).
Construcción marítima (astilleros, pontones, construcciones marinas) y obra civil (hormigones, radieres, gasfitería, tuberías, carpintería, cambio de ventanas).

Diseño y desarrollo: **ATENIA**.

## Estructura
- `index.html` — sitio completo en un solo archivo (HTML + CSS + JS, sin dependencias de build).
- `img/` — fotografías del sitio (pendientes: fotos reales del cliente).

## Pendientes
- Logo definitivo sin marca de agua.
- Fotos reales de trabajos para la galería de proyectos y vistas previas de servicios.

## Publicación
- Despliegue: cPanel → Git Version Control (repo clonado en el servidor). Tras cada push: *Update from Remote* y *Deploy HEAD Commit*. Las tareas están en `.cpanel.yml` (copia a `public_html`).
- Dominio: floservice.cl (NIC Chile) → hosting AltaHosting (cPanel, plan Starter).
- Correo: jmunoz@floservice.cl

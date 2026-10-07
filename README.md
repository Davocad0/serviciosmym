# Servicios M&M · Menú del recreo

Sitio público del menú de Servicios Gastronómicos M&M: https://serviciosmym.vercel.app

- `index.html` — la página del menú (fotos, precios, WhatsApp).
- `fotos/` — fotos de los productos en WebP (900 px y 640 px).

El QR impreso en la propuesta abre https://serviciosmym.vercel.app y muestra esta página directo, sin iniciar sesión en nada.

## Para publicar un cambio (precios, fotos, textos)

1. Editar `index.html` (o subir fotos nuevas a `fotos/`) aquí en GitHub y guardar con commit.
2. En Vercel: proyecto **serviciosmym** → Deployments → el último → menú ⋯ → **Redeploy**.

En cada publicación Vercel descarga este repositorio, así que no hace falta subir nada más. El QR impreso no cambia nunca.

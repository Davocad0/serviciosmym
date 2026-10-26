# Servicios M&M · Menú del recreo

Sitio público de Servicios Gastronómicos M&M (Mejores Momentos): https://serviciosmym.vercel.app

- `index.html`: la página (fotos, precios, cómo trabajamos, trayectoria, contacto).
- `fotos/`: fotos de los productos en WebP (900 px y 640 px).
- `propuesta/`: la propuesta en PDF liviano para descargar. `servicios-mym-2027.pdf` es la genérica; hay una por colegio (`lasalle.pdf`, `bautista.pdf`, …).
- `404.html`, `favicon.svg`, `apple-touch-icon.png`: página de error e íconos.

## Enlaces por colegio

Cada colegio tiene su enlace, por ejemplo https://serviciosmym.vercel.app/lasalle. La página muestra "Propuesta para el Colegio La Salle", el botón descarga su PDF y el WhatsApp ya dice de qué colegio escriben. En las estadísticas de Vercel se ve qué enlace se abrió.

bautista · lasalle · marista · donbosco · interamericano · senorjesus · henryprince · lasantacruz · mariagoretti · domingosavio · isabelsaavedra · adventista

Para agregar un colegio: sumarlo en `COLEGIOS` dentro de `index.html`, agregar su PDF en `propuesta/` y su nombre en la regla `rewrites` de `vercel.json` (proyecto de Vercel).

## Para publicar un cambio

1. Editar aquí en GitHub y guardar con commit.
2. En Vercel: proyecto **serviciosmym** → Deployments → el último → menú ⋯ → **Redeploy**.

El QR impreso siempre apunta a https://serviciosmym.vercel.app y no cambia.

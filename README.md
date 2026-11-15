# Red Polo 120 · Paradise Ranch — sitio web

Sitio estático de una sola página (HTML + CSS + JS en `index.html`, sin build).

- Idiomas: inglés, español y francés (selector con banderas arriba a la derecha; recuerda la elección y detecta el idioma del navegador).
- WhatsApp: botón flotante y formulario que arma el mensaje y abre wa.me/19498749399.
- Fotos: por ahora se cargan desde el CDN del sitio actual de Squarespace. Antes de dar de baja Squarespace hay que copiar las fotos a una carpeta `img/` del repo y cambiar la constante `CDN` en el script.

## Publicar en Vercel (cuando Matias lo apruebe)
1. Crear un repo en GitHub y subir esta carpeta.
2. En Vercel: Add New → Project → importar el repo. Framework preset: "Other". Sin comando de build. Output: raíz.
3. Para el dominio: Vercel → Settings → Domains → agregar redpolo120.com y cargar los DNS que indique en GoDaddy, manteniendo los registros MX y SPF de Hostinger para no cortar el correo.

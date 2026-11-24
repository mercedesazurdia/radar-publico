# Radar Público

Panel abierto de M+ Intelligence en https://radar.mpluscorp.com

Una sola página (`index.html`) sin dependencias. Lee `snapshot.json` del
bucket público `radar-publico` de Supabase Storage, que Apps Script sube
cada hora (repo privado `radar`, `Etapa30_RadarPublico.js`). La página no
lleva claves ni toca la base.

- `?demo` en la URL muestra datos de ejemplo para revisar el diseño.
- `CNAME` le dice a GitHub Pages el dominio. El registro CNAME `radar` →
  `mercedesazurdia.github.io` vive en el DNS de Bluehost.
- Mapa: límites departamentales de Natural Earth (dominio público).

Para cambiar el correo o el WhatsApp: bloque `CONFIG` al inicio del script.

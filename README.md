# Propuesta Rock and Rolla × Bresco Media

Landing interactiva de la propuesta "Plan de Rescate 90 días" para Rock and Rolla Chimaltenango. Es un solo archivo HTML, sin dependencias ni paso de compilación, pensado para verse en teléfono.

## Contenido

- `index.html`: la página completa (CSS y JavaScript incluidos, logo incrustado).
- `assets/logo.jpg`: el logo recortado, solo de referencia.
- `.nojekyll`: evita que GitHub Pages procese los archivos.

## Publicar en GitHub Pages

1. Cree un repositorio nuevo y suba estos archivos a la raíz.
2. En **Settings → Pages**, elija **Deploy from a branch**, la rama `main` y la carpeta `/ (root)`.
3. En un par de minutos la página queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Qué editar

Todo está al inicio del bloque `<script>` de `index.html`:

- `CONFIG.whatsapp`: número con código de país y sin signos, por ejemplo `502XXXXXXXX`. Mientras esté vacío, el botón abre WhatsApp sin contacto.
- `CONFIG.nombre`: nombre que aparece en el mensaje de aprobación.
- `K`: precios y descuentos por paquete. `m` es el precio mensual normal y `d` el porcentaje de descuento (Pro 5, Premium 10).
- `DL`: fecha límite del descuento (domingo 22 de nov de 2026, 11:59 pm hora de Guatemala). Después de esa fecha la página muestra solo el precio normal.
- `H`, `P` y `C`: causas a probar, fases con fechas y lista de requisitos del cliente.

## Notas

- Las fuentes (Anton y Barlow) se cargan desde Google Fonts, así que se necesita conexión.
- Las fechas del plan suponen arranque el lunes 23 de noviembre de 2026.
- Los anuncios (Q3,000 al mes sugeridos) se cotizan aparte de los honorarios.

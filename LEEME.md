# Portafolio de Sergio Morales Meza

Sitio estático de una sola página (sin dependencias). Contenido:

- `index.html` – todo el sitio (estilos y scripts incluidos).
- `images/` – imágenes optimizadas con nombres limpios.

## Cómo publicarlo en GitHub Pages (repositorio `portafolio`)

1. En tu repositorio, reemplaza `index.html` por el de este paquete.
2. Copia la carpeta `images/` (puede convivir con las imágenes anteriores).
3. Puedes borrar `assets/`, `README.txt` y `LICENSE.txt` de la plantilla anterior: el nuevo diseño ya no la usa.
4. Haz commit y push. El sitio se actualiza en https://sergiomorame.github.io/portafolio/

## Qué editar

Todo está al final de `index.html`, dentro de `<script>`:

- `CORREO_CONTACTO`: escribe tu correo para activar el formulario.
- `PROYECTOS`: lista de proyectos (imagen, título, tipo, descripción y herramientas).
  - `tipo`: `tablero`, `web`, `mapa` o `dron`.
  - `forma`: `""` (normal), `"ancho"` o `"alto"` para el tamaño en la galería.

La experiencia laboral y las herramientas están como HTML normal en las secciones
`#experiencia` y `#herramientas`.

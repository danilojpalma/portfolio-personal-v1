 # Portafolio Personal

 Portafolio estático para mostrar proyectos y experiencia como Frontend Developer. Construido únicamente con HTML y CSS, e incluye un modelo 3D embebido con `model-viewer` para dar un toque interactivo.

 ## Demo

- Live: https://danilojpalma.github.io/portfolio-personal-v1/

 ## Características

- Secciones: hero con CTA, proyectos destacados, línea de tiempo (bio), stack, links y about.
- Modelo 3D (`model-viewer`) con rotación automática y controles de cámara deshabilitados para mantener el foco.
- Diseño responsive básico pensado para portafolio personal.

 ## Tecnologías

- HTML5
- CSS3
- model-viewer (web component)
- Iconos: Font Awesome (vía CDN en el HTML)

 ## Estructura del proyecto

- index.html: página principal con todas las secciones del portafolio.
- assets/css/style.css: estilos globales y componentes de layout.
- assets/img/: imágenes del fondo, logo y previsualizaciones.
- assets/3d/: modelos `.glb` usados por `model-viewer`.

 ## Ejecutar en local

 1) Clona el repositorio.
 2) Abre `index.html` en tu navegador o sirve la carpeta con un servidor estático (por ejemplo: `python -m http.server 8000`).
 3) Verifica que las rutas de `assets/` funcionen; evita mover la carpeta para no romper referencias.

 ## Notas sobre el modelo 3D

- El modelo se carga desde `assets/3d/old_pc_low_poly_game_model.glb`.
- Si necesitas reemplazarlo, mantén el formato `.glb` y actualiza la ruta en la etiqueta `<model-viewer>` de `index.html`.

 ## Personalización rápida

- Colores y tipografías: ajusta variables y reglas en `assets/css/style.css`.
- Proyectos: edita el contenido de la sección `Latest Projects` en `index.html` (títulos, descripciones, tags y enlaces).
- Links y redes: actualiza las URLs en la sección `Links` y en los íconos de contacto.

 ## Licencia

 MIT. Si reutilizas el diseño, agradece manteniendo la atribución.

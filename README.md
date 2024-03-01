# Página Web Accesible con ARIA

Este repositorio contiene una página web diseñada para ser accesible para todos los usuarios, incluyendo aquellos con discapacidades. Se han realizado varias modificaciones y añadido etiquetas ARIA (Accessible Rich Internet Applications) para mejorar la experiencia de usuario.

## Modificaciones Realizadas

1. **Etiquetas ARIA en el Menú de Navegación:**
   - Se ha añadido el atributo `aria-label` al elemento `<nav>` para proporcionar una etiqueta descriptiva que ayuda a los usuarios con discapacidad a comprender la función del menú de navegación.
   - Se ha eliminado el atributo `for` de las etiquetas `<a>` dentro de la lista de navegación, ya que no es necesario y puede confundir a los usuarios con lectores de pantalla.

2. **Etiqueta ARIA en el Formulario de Búsqueda:**
   - Se ha añadido el atributo `role="search"` al formulario para indicar que es un formulario de búsqueda, lo que ayuda a los usuarios con discapacidad a comprender su propósito.

3. **Etiquetas ARIA en las Imágenes:**
   - Se han añadido las etiquetas `<figure>` y `<figcaption>` alrededor de las imágenes y sus descripciones correspondientes para mejorar la asociación entre la imagen y su descripción.
   - Se ha añadido el atributo `aria-labelledby` para asociar cada imagen con su descripción correspondiente.

## Cómo Contribuir
¡Las contribuciones son bienvenidas! Si deseas mejorar la accesibilidad de esta página web aún más, siéntete libre de realizar un fork del repositorio y enviar un pull request con tus modificaciones.

## Licencia
Este proyecto está bajo la Licencia MIT. Para más detalles, consulta el archivo [LICENSE](LICENSE).

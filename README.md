CEMIP Odontología - Sitio Web Institucional
Este proyecto es un sitio web sencillo para un consultorio odontológico ficticio llamado CEMIP. Fue desarrollado con el objetivo de reforzar conocimientos en HTML5, CSS3 (utilizando SASS/SCSS) y el framework de CSS, Bootstrap 5.

🚀 Características Principales
Páginas Principales: Inicio, Turnos, Tratamientos, Contacto y Sobre Nosotros.
Diseño Responsivo: Adaptable a diferentes tamaños de pantalla (desktops, tablets, móviles) gracias a Bootstrap y media queries personalizadas.
Estilizado con SASS/SCSS: Uso de preprocesador CSS para una estructura de estilos modular, mantenible y escalable, incluyendo variables y anidamiento.
Componentes de Bootstrap 5: Utilización de la barra de navegación, sistema de grid y estilos de formulario de Bootstrap para un desarrollo rápido y un diseño limpio.
Formularios Interactivos: Formularios dedicados para solicitar turnos y enviar consultas, con campos claros para la recolección de información.
Efectos Visuales Ligeros: Transiciones y efectos hover sutiles para mejorar la experiencia del usuario, especialmente en la página de inicio.
Iconografía de Font Awesome: Integración de iconos de redes sociales en el pie de página.
Optimización SEO Básica: Meta etiquetas de descripción y palabras clave para mejorar la visibilidad en buscadores.
📁 Estructura del Proyecto
cemip-odontologia/
├── css/
│   ├── contacto.css
│   ├── estilos.css
│   ├── nosotros.css
│   ├── tratamientos.css
│   └── turnos.css
├── images/
│   ├── background.jpg
│   ├── background1.jpg
│   ├── background2.jpg
│   ├── dental_teeth_tooth_dentist_icon_220580.png (favicon)
│   ├── favicon.jpg
│   └── (otras imágenes de tratamientos, etc.)
├── pages/
│   ├── contacto.html
│   ├── nosotros.html
│   ├── tratamientos.html
│   └── turnos.html
├── scss/
│   ├── partials/
│   │   ├── _body.scss
│   │   ├── _contacto-body.scss
│   │   ├── _contacto-mediaqueries.scss
│   │   ├── _footer.scss
│   │   ├── _mediaqueries.scss
│   │   ├── _menu.scss
│   │   ├── _nosotros-body.scss
│   │   ├── _nosotros-mediaqueries.scss
│   │   ├── _reset.scss
│   │   ├── _tratamientos-body.scss
│   │   ├── _turnos-body.scss
│   │   ├── _turnos-mediaqueries.scss
│   │   └── _vars.scss
│   ├── contacto.scss
│   ├── estilos.scss
│   ├── nosotros.scss
│   ├── tratamientos.scss
│   └── turnos.scss
└── index.html
🛠️ Tecnologías Utilizadas
HTML5: Para la estructura del contenido.
CSS3: Para el estilizado básico.
SASS/SCSS: Preprocesador CSS para una organización de estilos avanzada.
Variables (_vars.scss): Para la gestión centralizada de colores, fuentes y gradientes.
Partials (_*.scss): Para modularizar los estilos por componentes y secciones.
Anidamiento: Para escribir reglas CSS más concisas y legibles.
Mixins (no explícitamente usados en los archivos proporcionados, pero es una capacidad de SASS que se puede explorar).
Loops (@each en _footer.scss): Para generar estilos repetitivos de manera eficiente.
Bootstrap 5: Framework CSS para un diseño responsivo y componentes de UI predefinidos (navbar, grid system, forms).
Google Fonts: Para la tipografía Ysabeau Office.
Font Awesome: Para los iconos de redes sociales.
✨ Aspectos Destacados del Aprendizaje
Durante el desarrollo de este proyecto, se hizo especial énfasis en:

Dominio de HTML5 Semántico: Uso correcto de etiquetas como <header>, <main>, <section>, <footer>, <nav>, etc.
Diseño Responsivo con Flexbox y Grid: Aplicación de las propiedades de CSS Flexbox y Grid para la construcción de layouts complejos y adaptables, complementando el sistema de grid de Bootstrap.
Modularización de CSS con SASS: Aprendizaje y aplicación de las mejores prácticas en SASS para organizar los estilos en archivos parciales, usar variables para la consistencia del diseño y escribir código más DRY (Don't Repeat Yourself).
Integración de Frameworks (Bootstrap): Combinación de estilos personalizados con un framework externo, entendiendo cómo sobrescribir o extender sus funcionalidades.
Gestión de Activos (Imágenes y Fuentes): Referenciamiento correcto de imágenes y fuentes externas/locales.
Mejora de la Experiencia de Usuario (UX): Implementación de transiciones suaves y efectos hover para una interfaz más atractiva y dinámica.
⚙️ Cómo Ejecutar el Proyecto
Clona el repositorio (si está en un control de versiones) o descarga los archivos.
Abre el archivo index.html en tu navegador web.
Dado que es un proyecto de solo frontend, no requiere de un servidor web ni de dependencias de backend.

🤝 Contribuciones
Este proyecto fue creado como una herramienta de aprendizaje personal. Las sugerencias y mejoras son siempre bienvenidas.
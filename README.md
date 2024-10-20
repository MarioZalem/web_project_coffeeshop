**Nombre del Proyecto**: Cafetería Triple Peaks (web project coffeeshop)

**Descripción del Proyecto**:  
Este proyecto es una página web para una cafetería llamada "Triple Peaks". La página incluye secciones como el encabezado, recetas, y una sección de reservas. También cuenta con un pie de página que muestra la información de contacto y enlaces a redes sociales. La estructura del proyecto sigue la metodología BEM (Block Element Modifier) para mantener el código HTML y CSS organizado y modular.

**Tecnologías utilizadas**:

- **HTML**: Para estructurar el contenido de la página de manera semántica.
- **CSS**: Para dar estilo a la página siguiendo la metodología BEM. Incluye el uso de propiedades como `position`, `z-index`, `border-radius`, y efectos de transición para estados hover.
- **JavaScript (en su caso)**: Aunque en este proyecto específico aún no se implementó JavaScript, podría añadirse en el futuro para mejorar la funcionalidad, como la validación del formulario de reservas.
- **Normalize.css**: Para eliminar las inconsistencias en los estilos por defecto de los navegadores y asegurar una experiencia uniforme para los usuarios.
- **Bash (terminal)**: Para automatizar tareas de refactorización y organización del CSS, dividiendo los estilos en archivos por bloques.

**Estructura del Proyecto**:

- `blocks/`: Contiene archivos CSS organizados por bloques (`footer.css`, `form.css`, `header.css`, etc.).
- `images/`: Incluye todas las imágenes utilizadas en el proyecto.
- `pages/index.css`: Archivo CSS principal que importa los estilos de los diferentes bloques.
- `vendor/normalize.css`: Archivo para normalizar estilos predeterminados.
- `index.html`: Archivo HTML principal del proyecto.

**Planes de mejora del Proyecto**:

- **Animaciones Adicionales**: Agregar animaciones suaves a los elementos al cargar la página, como un fade-in para el encabezado o un slide-in para el pie de página.
- **Validación del Formulario con JavaScript**: Implementar validación de campos para el formulario de reservas, asegurando que los usuarios ingresen información correcta antes de enviar.
- **Diseño Responsivo**: Mejorar el diseño para hacerlo completamente responsivo en dispositivos móviles y tabletas, asegurando que la experiencia del usuario sea perfecta en cualquier pantalla.
- **Modo Oscuro**: Añadir un "Modo Oscuro" que permita a los usuarios cambiar la paleta de colores de la página, mejorando la accesibilidad y haciendo la experiencia más personalizable.

**Autor**: Mario Zamora Alemán

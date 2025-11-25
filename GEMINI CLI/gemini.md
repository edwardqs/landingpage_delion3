Actúa como un experto en Astro Framework y Tailwind CSS. Genera el código completo para un componente llamado `Navbar.astro` basado en la imagen y especificaciones siguientes:

1.  **Tecnología:**
    - Archivo: `.astro` (con el bloque de script frontmatter `---` si es necesario).
    - Estilos: Tailwind CSS (usando la propiedad `class`).
    - Lógica: CSS puro para interacciones (hover) para mantener el "Zero JS" por defecto de Astro.

2.  **Diseño (Tokens de Figma):**
    - Fondo: `#002269` (bg-[#002269]).
    - Altura: `98px` (h-[98px]).
    - Tipografía: Fuente 'Inter', texto blanco.
    - Padding: `px-[35px]`.

3.  **Estructura del Componente:**
    - **Logo:** A la izquierda. Usa una etiqueta `<img>` apuntando a `/logo.png` (o un placeholder).
    - **Menú Central:**
        - Items: "PRODUCTOS", "SERVICIOS", "BLOG", "NOSOTROS".
        - **Dropdown en PRODUCTOS:**
            - Debe desplegarse al hacer hover.
            - Usa las clases `group` (en el padre) y `hidden group-hover:block` (en el hijo) de Tailwind.
            - Sub-items: "HARDWARE", "SOFTWARE".
            - Estilo del dropdown: Fondo blanco, texto oscuro, sombra `shadow-lg`, posicionado absolutamente `absolute top-full`.
    - **Zona Derecha:**
        - Selector de Idioma: Icono Mundo (SVG inline) + Texto "Español" + Chevron (SVG inline).
        - Link "NUBE".
        - Botón CTA "CONTACTO": Borde blanco (`border border-white`), `rounded-[13px]`, hover con fondo blanco y texto azul.

4.  **Requisito de Iconos:**
    - Usa SVGs inline simples dentro del código para evitar dependencias de librerías de iconos externas por ahora.
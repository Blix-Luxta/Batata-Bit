# Batata Bit Landing Page - CSS Design

Este proyecto es una landing page moderna y responsiva, diseñada para presentar información relacionada con una criptomoneda ficticia.
El diseño no es de mi propiedad. Está estructurado para adaptarse a diferentes tamaños de pantalla, desde móviles hasta tablets y desktops.

## Estructura de Archivos

- **style.css**: Contiene los estilos principales de la página.
- **tablet.css**: Incluye los estilos específicos para dispositivos tablet.

## Estilos Globales

- **Variables CSS**: Se definen en `:root` para asegurar la consistencia de colores en todo el proyecto.
  - `--bitcoin-orange`: #f7931a
  -  `--bitcoin-orange`: #f7931a;
  -  `--soft-orange`: #ffe9d5;
  -  `--secondary-blue`: #1a9af7;
  -  `--soft-blue`: hsl(205, 100%, 95%);
  -  `--warm-black`: #282623;
  -  `--black`: #201e1c;
  -  `--grey`: #bababa;
  -  `--off-white`: #faf8f7;
  -  `--just-white`: #fff;

- **Tipografía**: Se utilizan fuentes personalizadas como `DM Sans` e `Inter` para mantener un diseño limpio y moderno.
  
- **Reset de Estilos**: Se eliminan márgenes y padding predeterminados de todos los elementos (`*`) y se utiliza `box-sizing: border-box` para facilitar el manejo de tamaños.

## Secciones Principales

### Header
El `header` es la primera sección visible de la página. Está diseñado con un fondo degradado de negro a naranja y contiene:

- **Logo**: Se muestra centrado en la parte superior.
- **Título y Subtítulo**: Texto descriptivo sobre la página.
- **Botón**: Botón de acción que invita a los usuarios a explorar más.

### Main
La sección principal (`main`) está dividida en varias subsecciones:

- **Exchange Container**: Muestra gráficos y tablas de datos financieros. Las tablas se pueden desplazar horizontalmente para acomodar más contenido.
- **Detalles del Producto**: Sección con información sobre productos, destacada con un fondo oscuro y texto en blanco para mayor contraste.
- **Planes**: Descripción de los planes disponibles, presentada en un slider horizontal. Cada plan tiene un diseño único que destaca visualmente.

### Footer
El `footer` está dividido en dos secciones:

- **Enlaces**: Una lista de enlaces útiles para navegar por la página.
- **Logo**: Un logo que se muestra junto a los enlaces.

## Responsividad

El diseño se adapta automáticamente a diferentes dispositivos:

- **Tablet**: En `tablet.css`, se ajustan los tamaños de fuente, márgenes y disposición de elementos para asegurar que todo sea legible y esté bien organizado en dispositivos de tamaño medio.

## Cómo Usar

1. **Clonar el Repositorio**: 
   ```bash
   git clone https://github.com/tuusuario/bitcoin-landing-page.git

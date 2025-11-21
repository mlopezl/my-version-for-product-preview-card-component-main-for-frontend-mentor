# Frontend Mentor – Solución al Product Preview Card Component

Esta es mi solución al desafío **Product Preview Card Component** de [Frontend Mentor](https://www.frontendmentor.io/).  
Este reto me ayudó a mejorar mis habilidades en **HTML y CSS** construyendo una tarjeta de vista previa de producto totalmente responsive, adaptada a distintos tamaños de pantalla e incluyendo estados interactivos de hover y focus.

## Tabla de Contenidos
- [Descripción General](#descripción-general)  
- [El Desafío](#el-desafío)  
- [Diseño](#diseño)  
- [Enlaces](#enlaces)  
- [Mi Proceso](#mi-proceso)  
- [Construido Con](#construido-con)  
- [Lo Que Aprendí](#lo-que-aprendí)

## Descripción General
Este proyecto es un **componente de tarjeta de vista previa de producto**, diseñado para mostrar un producto (imagen, título, descripción, precio y botón de compra) en un diseño visualmente atractivo.  
Los usuarios pueden visualizar la tarjeta tanto en pantallas de escritorio como en dispositivos móviles, e interactuar con los estados hover/focus del botón y otros elementos interactivos.

La interfaz incluye:
- Un diseño moderno y limpio con imagen e información en columnas (escritorio) o apiladas (móvil)  
- Estados hover y focus en elementos interactivos (botones, acciones de la tarjeta)  
- Diseño responsive que se adapta al ancho de pantalla  
- Estilos consistentes usando propiedades personalizadas de CSS para facilitar el mantenimiento

## El Desafío
Los usuarios deben poder:

- Ver el diseño óptimo según su dispositivo (móvil o escritorio)  
- Ver los estados hover y focus para los elementos interactivos  
- Observar una representación visual fiel al diseño proporcionado por Frontend Mentor

## Diseño
### Diseño en Escritorio  
![Desktop Design](./design/desktop-design.jpg)

### Hover & Focus States  
![Hover & Focus States](./design/active-states.jpg)

### Diseño en Móvil  
<img src="./design/mobile-design.jpg" width="200px" alt="Diseño móvil">

## Enlaces
- [Repositorio en GitHub](https://github.com/mlopezl/my-version-for-product-preview-card-component-main-for-frontend-mentor)  
- [Live Demo](https://mlopezl.github.io/my-version-for-product-preview-card-component-main-for-frontend-mentor/)

## Mi Proceso
1. Revisé las especificaciones del diseño proporcionado por Frontend Mentor y definí los puntos de quiebre para móvil y escritorio.  
2. Construí la estructura HTML semántica de la tarjeta: contenedor de la imagen, contenedor de texto, título, descripción, precio y botón de compra.  
3. Apliqué propiedades personalizadas de CSS (variables) para colores, tamaños de fuente y espaciados, asegurando un estilo consistente en todo el componente.  
4. Implementé el diseño responsive usando Flexbox (y/o CSS Grid) para alternar entre diseño apilado en móvil y dos columnas en escritorio.  
5. Añadí estilos hover y focus al botón para mejorar la retroalimentación de interacción.  
6. Verifiqué que la tarjeta se viera y funcionara correctamente en distintos tamaños de pantalla, ajustando media queries y accesibilidad en los estados interactivos.

## Construido Con
- HTML5  
- CSS3  
- Flexbox  

## Lo Que Aprendí
- Cómo estructurar un componente para que se adapte eficientemente entre diseño móvil y de escritorio usando Flexbox/Grid.  
- Cómo usar propiedades personalizadas de CSS (variables) para gestionar un sistema de diseño consistente (colores, fuentes, espaciados).  
- Cómo crear y gestionar estados hover y focus para mejorar la experiencia del usuario y la accesibilidad.  
- La importancia del HTML semántico en el diseño de componentes y el valor de un layout responsive.  
- Cómo analizar un diseño y convertirlo en código que respete la composición, la tipografía y los detalles de interacción.

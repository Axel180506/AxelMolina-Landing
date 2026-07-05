# NimbusCore – Landing Page

**Estudiante:** Axel Josué Molina Vera
**Tema asignado:** Empresa de centros de datos y servicios cloud empresariales
**Asignatura:** Fundamentos Web

## Descripción

Landing page semántica y responsive para **NimbusCore**, una empresa ficticia de centros de datos y servicios cloud empresariales. El sitio presenta la propuesta de valor de la empresa (alojamiento en la nube, servidores, respaldo, disponibilidad, planes empresariales, soporte y seguridad de la información) mediante una estructura HTML5 semántica, estilos propios organizados en CSS externo y componentes de Bootstrap 5, siguiendo un enfoque **mobile first**.

## Tecnologías utilizadas

- HTML5 semántico
- CSS3 (variables, Flexbox/Grid, media queries, mobile first)
- Bootstrap 5.3 (sistema de rejilla, tarjetas, botones, formularios, utilidades responsive)
- Bootstrap Icons 1.11
- Google Fonts (Poppins / Inter)
- Ilustraciones propias generadas para el proyecto (logo, hero e imágenes de servicios)

## Estructura del proyecto

```
AxelMolina-Landing
├─ css
│  ├─ componentes.css
│  ├─ estilos.css
│  └─ variables.css
├─ docs
│  └─ P3Tarea1.docx
├─ img
│  ├─ Cloud-Data-Center-2.jpeg
│  ├─ hero.webp
│  ├─ logo.png
│  ├─ Servicios1.png
│  └─ Servicios2.webp
├─ index.html
└─ README.md

```

## Paleta de colores

| Color | Código | Uso |
|---|---|---|
| Azul nube | `#C5DCEB` | Fondos de sección y tarjetas |
| Celeste hielo | `#D7EDF4` | Degradados y fondos suaves |
| Lavanda grisácea | `#D8D7E9` | Detalles y decoraciones |
| Azul pizarra | `#465D70` | Encabezados, botones y textos principales |

## Iconografía

Se utilizó **Bootstrap Icons**, con íconos relacionados al tema: servidor (`bi-server`), nube (`bi-cloud`), base de datos (`bi-database-check`), escudo (`bi-shield-lock`) y red (`bi-diagram-3`), entre otros, manteniendo un mismo estilo visual en toda la página.

## ¿Qué es y para qué sirve una variable en CSS?

Una variable en CSS (también llamada *custom property*) es un valor reutilizable que se define una sola vez y se referencia en múltiples lugares del código mediante la función `var()`. Se declaran generalmente dentro de `:root` con el prefijo `--`, por ejemplo `--color-principal: #465D70;`.

Sirven para mantener la coherencia visual del proyecto: si un color, tipografía o espaciado necesita cambiar, basta con modificar la variable una sola vez en `variables.css` y el cambio se refleja automáticamente en todos los archivos que la utilizan. Esto evita repetir valores "sueltos" a lo largo del CSS, facilita el mantenimiento y hace que el diseño sea más ordenado y escalable.

**Uso en este proyecto:** todas las variables (colores de la paleta asignada, tipografías, espaciados, radios de borde y sombras) se definieron en `css/variables.css` dentro de `:root`, y se consumen mediante `var(--nombre-variable)` en `estilos.css` y `componentes.css` — por ejemplo, `background-color: var(--color-principal);` en los botones, o `padding: var(--espacio-lg);` en las secciones.

## Instrucciones para abrir la página

1. Descargar o clonar la carpeta `molina-axel-landing/`.
2. Abrir el archivo `index.html` con cualquier navegador (Chrome, Edge, Firefox).
3. No requiere instalación ni servidor local, ya que Bootstrap y los íconos se cargan desde CDN (requiere conexión a internet).

## Enlace de GitHub Pages

_Pendiente de publicar. Al subir el proyecto a un repositorio de GitHub, activar GitHub Pages desde la rama principal y colocar aquí el enlace generado._

## Fuentes de imágenes e iconos

- **Iconos:** Bootstrap Icons (https://icons.getbootstrap.com/) — biblioteca open source.
- **Tipografías:** Google Fonts — Poppins y Inter (https://fonts.google.com/).
- **Imágenes (logo, hero, ilustraciones de servicios):** ilustraciones originales creadas para este proyecto académico, inspiradas en la temática de nube, servidores y seguridad de la información.

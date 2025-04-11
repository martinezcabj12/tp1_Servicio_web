# Proyecto Web: Sitio de Gimnasio

Este proyecto es un sitio web moderno y responsivo para un gimnasio, diseñado con HTML y CSS puro, sin frameworks adicionales. Incluye varias secciones como precios, entrenadores, clases, contacto y un blog de fitness.

---

## Estructura del Proyecto

**Carpetas principales:**

- **css/**
  Contiene todos los archivos CSS organizados por secciones del sitio:

  - `global.css`: estilos base y reseteo general.
  - `font.css`: declaración de fuentes personalizadas.
  - Archivos `style.*.css` para estilos específicos de cada sección: inicio, precios, entrenadores, contacto, clases y bloc/blog.

- **pages/**
  Páginas individuales del sitio, cada una enlaza su propio CSS específico:

  - `bloc.html`: sección blog con artículos filtrables.
  - `clases.html`: muestra las diferentes disciplinas.
  - `contacto.html`: formulario de contacto.
  - `entrenadores.html`: tarjetas de entrenadores con efecto flip.
  - `precios.html`: tabla de precios con toggle mensual/anual.

- **public/**
  Contenido público y recursos:
  - `favicon.svg`: ícono del sitio que aparece en la pestaña del navegador.
  - `fonts/`: contiene las fuentes Urbanist y Boldonse en formato `.woff2`.
  - `img/`: imágenes organizadas en subcarpetas (blog, cards, categorías, entrenadores).
  - `logo.png` y `logo.webp`: logotipos del sitio.
  - `video/motivación.mp4`: video motivacional para futuras integraciones multimedia.

---

## Características Destacadas

- **Favicon en formato SVG**
  El sitio utiliza un ícono en formato vectorial como favicon, lo cual garantiza buena calidad en cualquier resolución.

- **Diseño modular con CSS**
  Cada sección del sitio tiene su propio archivo CSS, lo que facilita el mantenimiento y escalabilidad.

- **Tarjetas con efecto Flip**
  En la sección de entrenadores, al pasar el cursor sobre las tarjetas, estas se giran para mostrar información adicional.

- **Barras de habilidad animadas**
  Visualización gráfica del nivel de fuerza, flexibilidad u otras habilidades clave en el perfil de cada entrenador.

- **Tabla de precios interactiva**
  Permite alternar entre planes mensuales y anuales mediante un toggle estilizado con CSS puro.

- **Blog estilo revista**
  Diseñado con CSS Grid, con sistema de etiquetas filtrables sin JavaScript y avatares generados con pseudoelementos.

- **Scroll Reveal en artículos del blog**
  Los artículos se animan al hacer scroll, dando dinamismo visual sin frameworks adicionales.

---

## Cómo navegar el sitio

Abrí el archivo `index.html` en tu navegador para iniciar el recorrido. Desde ahí podrás acceder a cada una de las páginas mediante el menú de navegación.

---

## Créditos

- Tipografías usadas:
  - **Boldonse** (Licencia Open Font License).
  - **Urbanist** (Google Fonts - OFL).
- Imágenes utilizadas con fines demostrativos y de inspiración visual.

# De Buena Masa - Sitio Web Oficial

Este proyecto corresponde a la entrega del **Proyecto Final** de Desarrollo Web. Es un sitio web estático de 5 páginas completamente responsivo, estilado mediante SCSS con arquitectura modular de partials, componentes de Bootstrap, animaciones nativas y de librería externa (AOS), y optimización SEO local.

## 🚀 Despliegue en Vivo
- **Sitio subido a Vercel/Netlify:** [https://debuenamasa.vercel.app](https://debuenamasa.vercel.app)

---

## 📁 Estructura del Proyecto

```text
de-buena-masa-final/
├── index.html                 # Página principal (Inicio)
├── pages/
│   ├── masamadre.html         # Página 2: Masa Madre
│   ├── recetas.html           # Página 3: Recetas
│   ├── blog.html              # Página 4: Blog
│   └── contactos.html         # Página 5: Contactos
├── scss/                      # Código fuente SCSS
│   ├── base/
│   │   └── _reset.scss        # Reset y estilos globales
│   ├── components/
│   │   ├── _cards.scss        # Tarjetas, extend y animación nativa @keyframes
│   │   ├── _forms.scss        # Estilos de formularios
│   │   └── _navbar.scss       # Personalización de Navbar Bootstrap
│   ├── layout/
│   │   ├── _footer.scss       # Estilos de pie de página
│   │   ├── _header.scss       # Estilos de encabezado
│   │   └── _main_layout.scss  # Grid responsivo y contenedores
│   ├── utilities/
│   │   ├── _mixins.scss       # Mixins con parámetros y media queries
│   │   └── _variables.scss    # Paleta de colores y tipografías
│   └── main.scss              # Archivo principal de SCSS (solo imports @use)
├── styles/
│   └── style.css              # CSS final compilado desde SCSS
├── assets/                    # Imágenes y recursos del sitio
└── README.md                  # Documentación del proyecto
```

---

## 🛠️ Tecnologías y Requisitos Cumplidos

1. **HTML5 Semántico:** Uso riguroso de `<header>`, `<main>`, `<footer>`, `<nav>`, `<section>`, `<article>`, `<figure>`, `<figcaption>`.
2. **SEO Local:**
   - `<title>` único y descriptivo por cada archivo.
   - `<meta name="description">` y `<meta name="keywords">` específicos por página.
   - Atributos `alt` descriptivos en el 100% de las imágenes.
3. **Bootstrap 5:** Componente Navbar responsivo en las 5 páginas con hamburguesa funcional en mobile y sobreescritura de estilos desde SCSS.
4. **SCSS Avanzado:**
   - Arquitectura modular de partials (`utilities/`, `base/`, `components/`, `layout/`).
   - `main.scss` exclusivo para imports utilizando `@use`.
   - Uso de **variables**, **nesting**, **mixins con parámetros**, **%extend** y animación nativa `@keyframes`.
5. **Responsividad:** Design Mobile-First probado en pantallas mobile, tablet y desktop sin scroll horizontal.
6. **Animaciones:**
   - **Nativa:** Animación `@keyframes pulseGlow` al hacer hover en las tarjetas de artículos.
   - **Librería Externa:** Integración de la librería **AOS** (`data-aos="fade-up"`, `fade-right`, `fade-left`, `zoom-in`).

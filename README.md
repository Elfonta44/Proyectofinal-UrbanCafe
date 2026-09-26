# UrbanCafé ☕🥐

Sitio web estático desarrollado como Proyecto Final para el curso de Desarrollo Web. Es un sitio web de 5 páginas completamente responsivo, diseñado para una cafetería y panadería artesanal.

## 🚀 Enlace al proyecto en producción
Podes ver el sitio funcionando en vivo en el siguiente enlace:
👉 **[Ver UrbanCafé en Vercel](https://proyectofinal-urban-cafe.vercel.app/)
---

## 🛠️ Tecnologías y Características

* **HTML5 Semántico:** Estructura limpia y ordenada (`<header>`, `<main>`, `<footer>`, `<nav>`, `<section>`).
* **CSS / SCSS Avanzado:** Uso de variables, *nesting*, *mixins* con parámetros, *extend* y arquitectura de *partials*. El archivo `main.scss` se utiliza exclusivamente para importar con `@use`.
* **Bootstrap 5:** Implementación de la barra de navegación responsiva (*navbar*) con menú hamburguesa adaptada a la identidad visual del proyecto.
* **Animaciones:** Animaciones nativas mediante CSS/SCSS y efectos dinámicos integrados con la librería externa **AOS**.
* **SEO Local y Accesibilidad:** Títulos únicos, etiquetas `<meta description>` y `<meta keywords>` específicas por página, y atributos `alt` en todas las imágenes.
* **Diseño Responsivo:** Adaptación fluida para dispositivos *mobile*, *tablet* y *desktop* sin scroll horizontal.

---

## 📁 Estructura de Carpetas



```text
/
├── index.html
├── pages/
│   ├── cafe-caliente.html
│   ├── cafe-frio.html
│   ├── panaderia.html
│   ├── nosotros.html
│   └── merch.html
├── scss/
│   └── (archivos parciales y main.scss)
├── styles/
│   └── main.css (CSS compilado)
└── assets/ (o img/)
    └── (imágenes, logos y favicon)
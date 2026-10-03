# Rony — Portafolio Personal

Portafolio personal de **Jorge Rosbel** (Rusindo.tv). Sitio web estático construido con HTML y CSS puro, sin frameworks ni dependencias externas.

---

## 📋 Tabla de Contenidos

- [Descripción](#descripción)
- [Historial del Proyecto](#historial-del-proyecto)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Tecnologías](#tecnologías)
- [Secciones](#secciones)
- [Diseño Responsivo](#diseño-responsivo)
- [Despliegue](#despliegue)
- [Autor](#autor)

---

## 📝 Descripción

Portafolio personal de una sola página (single-page) que presenta información sobre el perfil profesional, habilidades técnicas, proyectos y formulario de contacto. El diseño utiliza una paleta de colores cálidos (tonos beige y marrón) con estética elegante y minimalista.

---

## 🕐 Historial del Proyecto

| Fecha | Hito |
|-------|------|
| **Finales de 2025** | Creación inicial del proyecto. Se desarrolló la estructura HTML completa y los estilos CSS con diseño responsivo. |
| **Octubre 2026** | Retomado para preparar el repositorio y subirlo a GitHub. Se creó la documentación del proyecto (README). |

---

## 📁 Estructura del Proyecto

```
01-Proyecyto/
├── index.html          # Estructura principal del sitio
├── css/
│   └── stayle.css      # Hoja de estilos completa
├── imagen/
│   ├── favicon.svg     # Icono del sitio y logo
│   ├── img2.webp       # Imagen de perfil (sección About)
│   └── descargar.webp  # Imagen de fondo para proyectos del portafolio
└── README.md           # Documentación del proyecto
```

---

## 🛠️ Tecnologías

- **HTML5** — Semántica y accesibilidad
- **CSS3** — Flexbox, CSS Grid, Container Queries, animaciones con Scroll-driven Animations
- **Sin JavaScript** — Todo el interactividad se logra con CSS puro (checkbox hack para menú móvil)

---

## 📄 Secciones

1. **Header** — Barra de navegación fija con logo y enlaces. En móvil se despliega como menú hamburguesa.
2. **About (Perfil)** — Foto de perfil, descripción personal y barras de progreso de habilidades (HTML, CSS, JS, Python, SQL).
3. **Portfolio** — Grid de proyectos con imágenes de fondo y efecto hover.
4. **Contact** — Formulario con campos de nombre, apellido, email y mensaje.
5. **Footer** — Créditos y copyright.

---

## 📱 Diseño Responsivo

El sitio utiliza **CSS Container Queries** (no media queries tradicionales) para adaptar el diseño según el tamaño de cada contenedor:

- **Móvil** — Layout en columna, menú hamburguesa, grid de 1 columna
- **Tablet/Desktop** — Layout en fila para perfil, navegación horizontal, grid de 2-4 columnas para proyectos

---

## 🚀 Despliegue

Al ser un sitio 100% estático, se puede desplegar en cualquier servidor estático:

- **GitHub Pages** — Subir el repositorio y activar Pages en Settings
- **Netlify / Vercel** — Arrastrar la carpeta del proyecto
- **Servidor local** — Abrir `index.html` directamente en el navegador

---

## 👤 Autor

**Jorge Rosbel** — [Rusindo.tv](https://rusindo.tv)

---

## 🤝 Contribuciones

Este proyecto fue creado a finales del 2025 y retomado en octubre de 2026 para su publicación en GitHub.

> **Nota:** La documentación de este proyecto (README.md) fue generada con asistencia de inteligencia artificial.

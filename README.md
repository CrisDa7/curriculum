# Curriculum Profesional - Portfolio Personal

Este es un curriculum profesional con diseño moderno y tema oscuro, similar al diseño mostrado en la imagen de referencia.

## 🚀 Características

- **Diseño Moderno**: Tema oscuro con acentos azules
- **Responsive**: Se adapta a todos los dispositivos
- **Navegación Suave**: Transiciones animadas entre secciones
- **Portfolio Interactivo**: Filtros para proyectos
- **Formulario de Contacto**: Funcional y validado
- **Animaciones**: Efectos hover y transiciones suaves

## 📁 Estructura del Proyecto

```
curriculum/
├── templates/
│   └── index.html          # Página principal
├── css/
│   └── style.css          # Estilos CSS
├── js/
│   └── script.js          # Funcionalidad JavaScript
└── README.md              # Este archivo
```

## 🎨 Personalización

### 1. Información Personal

Edita el archivo `templates/index.html` y modifica:

```html
<!-- En la sección del sidebar -->
<h2 class="name">Tu Nombre</h2>
<p class="title">Tu Profesión</p>

<!-- Información de contacto -->
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>tu.email@ejemplo.com</span>
</div>
```

### 2. Foto de Perfil

Reemplaza la imagen placeholder:
```html
<img src="tu-foto.jpg" alt="Tu Foto">
```

### 3. Sección "Sobre Mí"

Modifica el texto en la sección `about`:
```html
<p class="about-text">
    Tu descripción personal aquí...
</p>
```

### 4. Educación y Experiencia

Actualiza las fechas y descripciones en la sección `resume`:
```html
<div class="timeline-item">
    <div class="timeline-date">2020 - 2022</div>
    <div class="timeline-content">
        <h4>Tu Título</h4>
        <p>Tu Institución</p>
    </div>
</div>
```

### 5. Habilidades

Ajusta los porcentajes en la sección de skills:
```html
<div class="skill-item">
    <div class="skill-info">
        <span>Tu Habilidad</span>
        <span>85%</span>
    </div>
    <div class="skill-bar">
        <div class="skill-progress" style="width: 85%"></div>
    </div>
</div>
```

### 6. Portfolio

Reemplaza los proyectos con los tuyos:
```html
<div class="portfolio-item" data-category="web-development">
    <div class="portfolio-image">
        <img src="tu-proyecto.jpg" alt="Tu Proyecto">
    </div>
    <div class="portfolio-info">
        <h4>Nombre del Proyecto</h4>
        <p>Categoría</p>
    </div>
</div>
```

### 7. Blog

Actualiza los artículos del blog con tu contenido:
```html
<article class="blog-card">
    <div class="blog-image">
        <img src="tu-articulo.jpg" alt="Título del Artículo">
    </div>
    <div class="blog-info">
        <h3>Título del Artículo</h3>
        <p class="blog-date">Fecha</p>
        <p class="blog-excerpt">Resumen del artículo...</p>
    </div>
</article>
```

### 8. Información de Contacto

Actualiza el mapa y la información de contacto:
```html
<!-- Cambia las coordenadas del mapa -->
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d...">
```

## 🎯 Secciones Disponibles

1. **Sobre Mí**: Descripción personal y servicios
2. **Curriculum**: Educación, experiencia y habilidades
3. **Portfolio**: Proyectos con filtros por categoría
4. **Blog**: Artículos y publicaciones
5. **Contacto**: Formulario y mapa

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Estilos modernos con Grid y Flexbox
- **JavaScript**: Interactividad y navegación
- **Font Awesome**: Iconos
- **Google Fonts**: Tipografía Inter

## 📱 Responsive Design

El diseño se adapta automáticamente a:
- **Desktop**: Layout completo con sidebar
- **Tablet**: Ajustes de navegación
- **Mobile**: Menú hamburguesa y layout vertical

## 🚀 Cómo Usar

1. Abre `templates/index.html` en tu navegador
2. Personaliza el contenido según tus necesidades
3. Reemplaza las imágenes placeholder con las tuyas
4. Actualiza la información de contacto
5. Sube a tu servidor web

## 🎨 Personalización de Colores

Para cambiar los colores, edita las variables en `css/style.css`:

```css
/* Colores principales */
--primary-color: #3498db;    /* Azul principal */
--background-dark: #1a1a1a;  /* Fondo oscuro */
--sidebar-bg: #2c2c2c;       /* Fondo del sidebar */
--text-light: #ffffff;       /* Texto claro */
--text-gray: #cccccc;        /* Texto gris */
```

## 📝 Notas

- Las imágenes son placeholders, reemplázalas con las tuyas
- El formulario de contacto es simulado, conéctalo a tu backend
- El mapa de Google Maps necesita coordenadas reales
- Los enlaces de redes sociales deben apuntar a tus perfiles

## 🤝 Contribuciones

Siéntete libre de mejorar el código y compartir tus mejoras.

---

¡Disfruta creando tu curriculum profesional! 🎉 
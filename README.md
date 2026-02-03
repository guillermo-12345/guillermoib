# 🌟 Portfolio Personal

Portfolio moderno y profesional construido con HTML, CSS y JavaScript vanilla. Diseñado para ser fácil de personalizar y desplegar en Vercel.

## 🚀 Características

- ✨ Diseño moderno y limpio con animaciones suaves
- 📱 Totalmente responsive (móvil, tablet, desktop)
- 🎨 Paleta de colores personalizable
- ⚡ Rápido y optimizado con Bootstrap 5
- 🔍 SEO friendly
- ♿ Accesible
- 🎭 Animaciones AOS (Animate On Scroll)
- 📊 Timeline interactivo para experiencia laboral
- 📈 Progress bars animadas para habilidades
- 🎓 Sección de certificaciones con cards animadas
- 🎯 Bootstrap Icons integrados

## 📋 Secciones

1. **Hero** - Presentación con nombre y título
2. **Sobre Mí** - Biografía y habilidades
3. **Trayectoria Laboral** - Timeline interactivo con tu experiencia profesional
4. **Educación & Certificaciones** - Formación académica y certificaciones con progress bars
5. **Proyectos** - Portafolio de trabajos
6. **Contacto** - Información de contacto y redes sociales

## 🛠️ Personalización

### Tecnologías Integradas
- **Bootstrap 5.3.2**: Framework CSS para componentes y grid system
- **Bootstrap Icons**: Biblioteca de iconos
- **AOS (Animate On Scroll)**: Biblioteca de animaciones al hacer scroll
- **Google Fonts**: Playfair Display + Work Sans

### 1. Información Personal

Edita el archivo `index.html` y busca las siguientes secciones:

#### Navegación (línea 18)
```html
<a href="#inicio" class="logo">TU NOMBRE</a>
```

#### Hero Section (líneas 29-41)
```html
<h1 class="hero-name">Tu Nombre Completo</h1>
<p class="hero-title">Desarrollador Web • Diseñador • Creativo</p>
<p class="hero-description">
    Transformo ideas en experiencias digitales excepcionales...
</p>
```

#### Sobre Mí (líneas 57-91)
Reemplaza el texto con tu biografía y experiencia.

#### Trayectoria Laboral (Timeline)
Para editar tu experiencia profesional, busca la sección `id="trayectoria"` y modifica cada `.timeline-item`:
```html
<div class="timeline-item" data-aos="fade-up">
    <div class="timeline-icon">
        <i class="bi bi-briefcase-fill"></i>
    </div>
    <div class="timeline-content">
        <div class="timeline-date">
            <i class="bi bi-calendar-event"></i>
            <span>Enero 2023 - Presente</span>
        </div>
        <h3 class="timeline-title">Tu Puesto</h3>
        <h4 class="timeline-company">Nombre de la Empresa</h4>
        <p class="timeline-description">
            Descripción de tus responsabilidades y logros...
        </p>
        <div class="timeline-tags">
            <span class="badge bg-primary">Tecnología 1</span>
            <span class="badge bg-primary">Tecnología 2</span>
        </div>
    </div>
</div>
```

#### Educación y Certificaciones
Para editar tu formación académica y certificaciones, busca la sección `id="educacion"`:
- **Educación formal**: Modifica los elementos `.education-item`
- **Certificaciones**: Modifica los elementos `.certification-card`
- **Progress Bars**: Ajusta los porcentajes en `.skill-percentage` y el atributo `style="width: X%"` de cada barra

#### Proyectos (líneas 107-217)
Para cada proyecto, edita:
- `.project-image img src` - URL de la imagen del proyecto
- `.project-title` - Nombre del proyecto
- `.project-description` - Descripción del proyecto
- `.project-tags` - Tecnologías utilizadas
- `.project-links` - Enlaces a demo y código

Ejemplo de proyecto:
```html
<article class="project-card">
    <div class="project-image">
        <div class="project-overlay">
            <a href="TU_LINK_DEMO" class="project-link">Ver Proyecto →</a>
        </div>
        <img src="URL_IMAGEN" alt="Proyecto 1">
    </div>
    <div class="project-content">
        <div class="project-tags">
            <span class="tag">React</span>
            <span class="tag">Node.js</span>
        </div>
        <h3 class="project-title">Nombre del Proyecto</h3>
        <p class="project-description">
            Descripción del proyecto...
        </p>
        <div class="project-links">
            <a href="LINK_DEMO" class="project-btn">Demo</a>
            <a href="LINK_GITHUB" class="project-btn">Código</a>
        </div>
    </div>
</article>
```

#### Contacto (líneas 226-254)
```html
<a href="mailto:tu@email.com" class="contact-item">
    <span>tu@email.com</span>
</a>
```

Actualiza los enlaces de redes sociales:
- GitHub: línea 258
- LinkedIn: línea 266
- Twitter/X: línea 274
- Instagram: línea 282

### 2. Colores

Edita las variables CSS en `styles.css` (líneas 2-11):

```css
:root {
    --primary-color: #1a1a2e;      /* Color principal */
    --secondary-color: #16213e;     /* Color secundario */
    --accent-color: #0f3460;        /* Color de acento */
    --highlight-color: #e94560;     /* Color de resaltado */
    --text-light: #f1f1f1;          /* Texto claro */
    --text-dark: #1a1a2e;           /* Texto oscuro */
    --bg-light: #ffffff;            /* Fondo claro */
    --bg-dark: #0a0a0f;             /* Fondo oscuro */
}
```

### 3. Fuentes

Las fuentes actuales son:
- **Playfair Display** - Títulos y headers
- **Work Sans** - Texto del cuerpo

Para cambiar las fuentes, edita el `<link>` de Google Fonts en `index.html` (línea 9).

## 📦 Estructura de Archivos

```
portfolio/
├── index.html          # Estructura HTML principal
├── styles.css          # Estilos y diseño
├── script.js           # Interactividad y animaciones
├── README.md           # Esta guía
└── vercel.json         # Configuración de Vercel (opcional)
```

## 🚀 Desplegar en Vercel

### Opción 1: Desde la interfaz web de Vercel

1. Ve a [vercel.com](https://vercel.com) e inicia sesión
2. Haz clic en "Add New Project"
3. Importa tu repositorio de GitHub/GitLab/Bitbucket
4. Vercel detectará automáticamente la configuración
5. Haz clic en "Deploy"

### Opción 2: Desde la línea de comandos

1. Instala Vercel CLI:
```bash
npm install -g vercel
```

2. En la carpeta del proyecto, ejecuta:
```bash
vercel
```

3. Sigue las instrucciones en pantalla

### Opción 3: Arrastra y suelta

1. Ve a [vercel.com](https://vercel.com)
2. Arrastra la carpeta del proyecto al área de "Deploy"
3. ¡Listo!

## 🔧 Desarrollo Local

Para ver el sitio localmente:

### Opción 1: Live Server (VS Code)
1. Instala la extensión "Live Server" en VS Code
2. Click derecho en `index.html`
3. Selecciona "Open with Live Server"

### Opción 2: Python
```bash
python -m http.server 8000
```
Visita `http://localhost:8000`

### Opción 3: Node.js
```bash
npx serve
```

## 📸 Imágenes de Proyectos

Las imágenes actuales son de Unsplash. Para usar tus propias imágenes:

1. **Opción A - Subir a tu repositorio:**
   - Crea una carpeta `/images` en tu proyecto
   - Agrega tus imágenes
   - Actualiza las rutas en `index.html`:
   ```html
   <img src="images/proyecto1.jpg" alt="Proyecto 1">
   ```

2. **Opción B - Usar un CDN:**
   - Sube tus imágenes a [Imgur](https://imgur.com), [Cloudinary](https://cloudinary.com), etc.
   - Usa las URLs directas en el `src` de las imágenes

## 🎨 Personalización Avanzada

### Agregar más proyectos

Copia y pega el bloque de código de un proyecto existente y personalízalo:

```html
<article class="project-card">
    <!-- Contenido del proyecto -->
</article>
```

### Agregar nuevas secciones

1. Agrega un nuevo `<section>` en `index.html`
2. Dale un `id` único (ej: `id="testimonios"`)
3. Agrega un enlace en la navegación que apunte a ese `id`
4. Estiliza la sección en `styles.css`

### Modificar animaciones

Las animaciones están definidas en `styles.css`. Puedes ajustar:
- Duración: cambia los valores de `transition` y `animation`
- Tipo de animación: modifica `@keyframes`
- Desactivar animaciones: elimina o comenta las propiedades de animación

## 🌐 SEO y Metadatos

Agrega estas etiquetas en el `<head>` de `index.html`:

```html
<meta name="description" content="Tu descripción profesional">
<meta name="keywords" content="desarrollador, diseñador, web, portfolio">
<meta name="author" content="Tu Nombre">

<!-- Open Graph / Facebook -->
<meta property="og:title" content="Tu Nombre - Portfolio">
<meta property="og:description" content="Tu descripción">
<meta property="og:image" content="URL_DE_TU_IMAGEN">
<meta property="og:url" content="https://tu-sitio.vercel.app">

<!-- Twitter -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Tu Nombre - Portfolio">
<meta name="twitter:description" content="Tu descripción">
<meta name="twitter:image" content="URL_DE_TU_IMAGEN">
```

## 📱 Agregar tu foto

1. Prepara tu foto (recomendado: 500x500px, formato JPG o PNG)
2. Reemplaza el placeholder en la sección "Sobre Mí":

```html
<div class="about-image">
    <img src="tu-foto.jpg" alt="Tu Nombre" style="width: 100%; border-radius: 20px;">
</div>
```

## 🐛 Solución de Problemas

### Las fuentes no se cargan
- Verifica la conexión a internet
- Asegúrate de que el link de Google Fonts esté correcto

### Las animaciones no funcionan
- Revisa la consola del navegador (F12) por errores en JavaScript
- Verifica que `script.js` esté correctamente vinculado

### El sitio no es responsive
- Asegúrate de tener la etiqueta viewport en el `<head>`:
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

## 📚 Recursos Adicionales

- [Vercel Documentation](https://vercel.com/docs)
- [MDN Web Docs](https://developer.mozilla.org/)
- [Google Fonts](https://fonts.google.com/)
- [Unsplash](https://unsplash.com/) - Imágenes gratis
- [Font Awesome](https://fontawesome.com/) - Iconos

## 📄 Licencia

Este proyecto es de código abierto. Siéntete libre de usarlo y modificarlo para tu portfolio personal.

## 🤝 Contribuciones

¡Las sugerencias y mejoras son bienvenidas! Si encuentras algún bug o tienes ideas para mejorar el portfolio, no dudes en abrir un issue o hacer un pull request.

---

**¡Buena suerte con tu portfolio!** 🚀

Si tienes alguna pregunta, no dudes en contactarme.

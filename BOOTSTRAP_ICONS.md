# 🎨 Guía de Bootstrap Icons

Esta es una referencia rápida de los iconos de Bootstrap que puedes usar en tu portfolio.

## 📌 Cómo Usar los Iconos

Los iconos se agregan usando la clase `bi` seguida del nombre del icono:

```html
<i class="bi bi-nombre-del-icono"></i>
```

## 🔥 Iconos Populares para Portfolio

### Profesión y Trabajo
```html
<i class="bi bi-briefcase-fill"></i>        <!-- Maletín -->
<i class="bi bi-laptop"></i>                <!-- Laptop -->
<i class="bi bi-code-square"></i>           <!-- Código -->
<i class="bi bi-terminal"></i>              <!-- Terminal -->
<i class="bi bi-cpu"></i>                   <!-- CPU/Tech -->
<i class="bi bi-cloud"></i>                 <!-- Cloud -->
<i class="bi bi-server"></i>                <!-- Servidor -->
<i class="bi bi-database"></i>              <!-- Base de datos -->
```

### Educación
```html
<i class="bi bi-mortarboard"></i>           <!-- Birrete -->
<i class="bi bi-mortarboard-fill"></i>      <!-- Birrete relleno -->
<i class="bi bi-book"></i>                  <!-- Libro -->
<i class="bi bi-journal-code"></i>          <!-- Diario de código -->
<i class="bi bi-pencil-square"></i>         <!-- Lápiz -->
```

### Certificaciones y Logros
```html
<i class="bi bi-award"></i>                 <!-- Premio -->
<i class="bi bi-award-fill"></i>            <!-- Premio relleno -->
<i class="bi bi-patch-check"></i>           <!-- Check badge -->
<i class="bi bi-patch-check-fill"></i>      <!-- Check badge relleno -->
<i class="bi bi-trophy"></i>                <!-- Trofeo -->
<i class="bi bi-trophy-fill"></i>           <!-- Trofeo relleno -->
<i class="bi bi-star"></i>                  <!-- Estrella -->
<i class="bi bi-star-fill"></i>             <!-- Estrella rellena -->
```

### Contacto y Redes Sociales
```html
<i class="bi bi-envelope"></i>              <!-- Email -->
<i class="bi bi-envelope-fill"></i>         <!-- Email relleno -->
<i class="bi bi-telephone"></i>             <!-- Teléfono -->
<i class="bi bi-geo-alt"></i>               <!-- Ubicación -->
<i class="bi bi-geo-alt-fill"></i>          <!-- Ubicación rellena -->
<i class="bi bi-github"></i>                <!-- GitHub -->
<i class="bi bi-linkedin"></i>              <!-- LinkedIn -->
<i class="bi bi-twitter"></i>               <!-- Twitter -->
<i class="bi bi-instagram"></i>             <!-- Instagram -->
<i class="bi bi-facebook"></i>              <!-- Facebook -->
<i class="bi bi-youtube"></i>               <!-- YouTube -->
```

### Tiempo y Calendario
```html
<i class="bi bi-calendar"></i>              <!-- Calendario -->
<i class="bi bi-calendar-event"></i>        <!-- Evento -->
<i class="bi bi-calendar-check"></i>        <!-- Calendario check -->
<i class="bi bi-clock"></i>                 <!-- Reloj -->
<i class="bi bi-hourglass"></i>             <!-- Reloj de arena -->
```

### Habilidades y Herramientas
```html
<i class="bi bi-lightbulb"></i>             <!-- Idea -->
<i class="bi bi-lightbulb-fill"></i>        <!-- Idea rellena -->
<i class="bi bi-rocket"></i>                <!-- Cohete -->
<i class="bi bi-rocket-takeoff"></i>        <!-- Despegue -->
<i class="bi bi-gear"></i>                  <!-- Engranaje -->
<i class="bi bi-tools"></i>                 <!-- Herramientas -->
<i class="bi bi-brush"></i>                 <!-- Pincel (diseño) -->
<i class="bi bi-palette"></i>               <!-- Paleta (arte) -->
```

### Proyectos
```html
<i class="bi bi-folder"></i>                <!-- Carpeta -->
<i class="bi bi-folder-fill"></i>           <!-- Carpeta rellena -->
<i class="bi bi-file-code"></i>             <!-- Archivo código -->
<i class="bi bi-filetype-html"></i>         <!-- HTML -->
<i class="bi bi-filetype-css"></i>          <!-- CSS -->
<i class="bi bi-filetype-js"></i>           <!-- JavaScript -->
<i class="bi bi-image"></i>                 <!-- Imagen -->
```

### Navegación
```html
<i class="bi bi-arrow-right"></i>           <!-- Flecha derecha -->
<i class="bi bi-arrow-left"></i>            <!-- Flecha izquierda -->
<i class="bi bi-arrow-up"></i>              <!-- Flecha arriba -->
<i class="bi bi-arrow-down"></i>            <!-- Flecha abajo -->
<i class="bi bi-chevron-right"></i>         <!-- Chevron derecha -->
<i class="bi bi-chevron-down"></i>          <!-- Chevron abajo -->
<i class="bi bi-download"></i>              <!-- Descargar -->
<i class="bi bi-link-45deg"></i>            <!-- Enlace -->
```

### Estado
```html
<i class="bi bi-check"></i>                 <!-- Check -->
<i class="bi bi-check-circle"></i>          <!-- Check círculo -->
<i class="bi bi-check-circle-fill"></i>     <!-- Check círculo relleno -->
<i class="bi bi-x"></i>                     <!-- X -->
<i class="bi bi-exclamation-circle"></i>    <!-- Exclamación -->
<i class="bi bi-info-circle"></i>           <!-- Información -->
```

## 🎨 Personalizar Tamaño

```css
/* CSS para ajustar tamaño */
.bi {
    font-size: 1.5rem;  /* Tamaño base */
}

/* Tamaños específicos */
.icon-sm { font-size: 1rem; }
.icon-md { font-size: 1.5rem; }
.icon-lg { font-size: 2rem; }
.icon-xl { font-size: 3rem; }
```

Ejemplo de uso:
```html
<i class="bi bi-heart-fill icon-xl"></i>
```

## 🌈 Personalizar Color

```css
/* Cambiar color de iconos */
.icon-primary {
    color: #e94560;
}

.icon-secondary {
    color: #0f3460;
}
```

Ejemplo de uso:
```html
<i class="bi bi-star-fill icon-primary"></i>
```

## 💡 Ejemplos de Uso en el Portfolio

### En Timeline de Trayectoria
```html
<div class="timeline-icon">
    <i class="bi bi-briefcase-fill"></i>    <!-- Para trabajos -->
    <i class="bi bi-code-square"></i>       <!-- Para proyectos de código -->
    <i class="bi bi-laptop"></i>            <!-- Para trabajo remoto -->
    <i class="bi bi-rocket-takeoff"></i>    <!-- Para startups -->
</div>
```

### En Educación
```html
<div class="education-icon">
    <i class="bi bi-mortarboard"></i>       <!-- Para universidad -->
    <i class="bi bi-book"></i>              <!-- Para cursos -->
    <i class="bi bi-award"></i>             <!-- Para certificados -->
</div>
```

### En Sección de Habilidades
```html
<div class="skill-item">
    <i class="bi bi-code-slash"></i>        <!-- Programación -->
    <i class="bi bi-palette"></i>           <!-- Diseño -->
    <i class="bi bi-database"></i>          <!-- Bases de datos -->
    <i class="bi bi-cloud"></i>             <!-- Cloud computing -->
</div>
```

## 🔗 Recursos

- **Sitio oficial**: https://icons.getbootstrap.com/
- **Búsqueda**: Busca iconos específicos en el sitio oficial
- **Descargar**: Todos los iconos están disponibles como SVG o fuentes

## 📝 Notas

- Los iconos con `-fill` tienen fondo sólido
- Los iconos sin `-fill` tienen solo contorno
- Puedes combinar con clases de Bootstrap: `text-primary`, `text-danger`, etc.
- También funciona con utilidades de Bootstrap: `me-2` (margen derecha), `ms-3` (margen izquierda)

Ejemplo completo:
```html
<i class="bi bi-envelope-fill text-primary me-2"></i>
<span>contacto@email.com</span>
```

# 🏛️ Turismo por Extremadura

Proyecto web de guía turística sobre Extremadura, diseñado con enfoque en SEO, accesibilidad y experiencia de usuario.

## 📋 Descripción

Portal informativo que ofrece una guía completa para descubrir Extremadura: sus localidades históricas, rutas naturales, actividades de ocio y los mejores restaurantes de la región. El proyecto está optimizado para buscadores y cumple con estándares de accesibilidad web.

## ✨ Características principales

- **Diseño responsive**: Adaptado a dispositivos móviles, tablets y ordenadores
- **SEO optimizado**: Meta tags, Open Graph, Twitter Cards y datos estructurados (JSON-LD)
- **Accesibilidad**: Uso de etiquetas semánticas, atributos ARIA y navegación por teclado
- **Tema claro/oscuro**: Selector de tema para mejorar la experiencia del usuario
- **Favicon personalizado**: Icono de cigüeña negra (símbolo de la fauna extremeña)
- **Contenido estructurado**: 
  - 8 localidades destacadas
  - 4 actividades de ocio
  - Top 10 restaurantes
  - Sección FAQ
  - Formulario de contacto

## 🗂️ Estructura del proyecto

```
proyecto-seo/
├── index.html              # Página principal
├── css/
│   ├── base.css           # Estilos base y variables
│   ├── header.css         # Estilos del header y navegación
│   ├── sections.css       # Estilos de las secciones
│   └── responsive.css     # Media queries y adaptaciones
├── js/
│   └── script.js          # JavaScript para interactividad
├── img/                   # Imágenes del proyecto
│   ├── banderaExtremadura.jpeg
│   ├── Guadalupe.jpg
│   ├── caceres.jpeg
│   ├── teatroRomanoMerida.jpeg
│   └── ... (más imágenes)
└── README.md             # Este archivo
```

## 🛠️ Tecnologías utilizadas

- **HTML5**: Estructura semántica del contenido
- **CSS3**: Estilos, variables CSS y diseño responsive
- **JavaScript**: Interactividad y funcionalidades dinámicas
- **Google Fonts**: Tipografía Poppins
- **Schema.org**: Datos estructurados (Organization, FAQPage)

## 🔍 SEO implementado

### Meta tags básicos
- Title optimizado
- Meta description descriptiva
- Meta keywords relevantes
- Canonical URL
- Meta robots (index, follow)

### Open Graph
- og:title, og:description, og:image
- og:url, og:type
- Optimizado para compartir en redes sociales

### Twitter Cards
- twitter:card, twitter:title
- twitter:description, twitter:image
- Vista previa mejorada en Twitter

### Datos estructurados (JSON-LD)
- Schema Organization
- Schema FAQPage
- Mejora la aparición en resultados de búsqueda

## 🎨 Funcionalidades

### Navegación
- Menú de navegación con enlaces internos
- Botón flotante con cigüeña guía
- Smooth scroll entre secciones

### Interactividad
- Selector de tema claro/oscuro
- Elementos `<details>` para "leer más"
- Formulario de contacto
- Efectos hover en tarjetas

### Contenido organizado
- Galería de localidades con imágenes
- Cards de actividades de ocio
- Lista ordenada de restaurantes (Top 10)
- Sección FAQ expandible
- Información de contacto detallada

## 🚀 Cómo ejecutar el proyecto

1. **Clonar o descargar** el repositorio
2. **Abrir** el archivo `index.html` en tu navegador
3. O usar un **servidor local**:
   ```bash
   # Con Python 3
   python -m http.server 8000
   
   # Con Node.js (http-server)
   npx http-server
   
   # Con Live Server en VS Code
   Clic derecho > Open with Live Server
   ```
4. Acceder a `http://localhost:8000` en tu navegador

## 📱 Responsive Design

El diseño se adapta a diferentes tamaños de pantalla:
- **Móviles**: < 768px
- **Tablets**: 768px - 1024px
- **Desktop**: > 1024px

## ♿ Accesibilidad

- Etiquetas semánticas (header, nav, main, section, footer)
- Atributos `aria-label` y `aria-labelledby`
- Contraste de colores adecuado
- Navegación por teclado
- Textos alternativos en imágenes
- Enlaces descriptivos

## 📞 Secciones del sitio

1. **Hero**: Presentación con imagen destacada
2. **Sobre Extremadura**: Introducción al destino
3. **Localidades**: 8 lugares imprescindibles
4. **Actividades de ocio**: Senderismo, gargantas, aves, astroturismo
5. **Gastroturismo**: Top 10 restaurantes
6. **FAQ**: Preguntas frecuentes
7. **Contacto**: Formulario de contacto

## 👨‍💻 Autor

Proyecto desarrollado para el módulo de **Desarrollo Web en Entorno Cliente** y **SEO**.

**Alumno**: Gabriel  
**Curso**: 2º DAW  
**Centro**: [Tu centro educativo]  
**Año**: 2025

## 📄 Licencia

Este proyecto es de uso educativo.

---

**🦅 Descubre Extremadura - Tu guía turística completa**

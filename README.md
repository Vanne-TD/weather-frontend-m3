# 🌤️ Aplicación de Clima - Mi Proyecto

Una aplicación web moderna que muestra información del clima en diferentes ciudades de la región de Biobío, Chile.

## 📋 Descripción

**Proyecto Clima** es una aplicación web desarrollada con HTML, CSS y JavaScript que proporciona información "actualizada" (es la idea a futuro) del clima para múltiples ciudades. La aplicación cuenta con una interfaz intuitiva y responsive, permitiendo a los usuarios consultar detalles específicos del clima de cada localidad.

La temática se centra en lugares urbanos y localidades de la región de Biobío en Chile, ofreciendo datos climáticos para ciudades como Concepción, Talcahuano, Los Ángeles, entre otras.

## 🎨 Metodología de Estilos

La aplicación utiliza la metodología **BEM (Block, Element, Modifier)** para la nomenclatura de clases CSS, lo que facilita la mantenibilidad y escalabilidad del código de estilos.

## 🏗️ Estructura SASS

El proyecto emplea la arquitectura **7-1 de Sass**, que organiza los estilos en parciales modulares:

- **abstracts/**: Variables y mixins reutilizables.
- **base/**: Estilos base como reset, tipografía y generales.
- **components/**: Estilos para componentes específicos como botones, tarjetas de clima, etc.
- **layout/**: Estilos para el layout general (header, footer, main).
- **pages/**: Estilos específicos para páginas individuales (home, about).
- **themes/**: Temas y variaciones de color para css.
- **vendors/**: Estilos de bibliotecas externas como Bootstrap y jQuery UI.

## 🌍 Ciudades Disponibles

La aplicación incluye información sobre las siguientes ciudades:

- Antuco
- Chiguayante
- Concepción
- Coronel
- Lebu
- Los Ángeles
- Lota
- San Pedro de la Paz
- Santa Juana
- Talcahuano
- Tomé
- Yumbel

## 🏗️ Estructura del Proyecto

```
proyecto-clima/
├── home.html                      # Página principal
├── about.html                     # Página acerca del proyecto
├── detalles-*.html                # Páginas de detalles por ciudad
├── assets/
│   ├── css/
│   │   └── style.css              # Estilos compilados desde Sass
│   ├── img/
│   │   └── cielo-azul-fondo-clima-nubes_261642-70.avif
│   └── js/
│       └── script.js              # Lógica de la aplicación
├── sass/                          # Código Sass fuente
│   ├── abstracts/
│   ├── base/
│   ├── components/
│   ├── layout/
│   ├── pages/
│   ├── themes/
│   └── vendors/
└── README.md                      # Este archivo
```

## 🚀 Características

- ✨ Interfaz responsiva y moderna
- 🎨 Diseño atractivo con imágenes de fondo
- 📱 Compatible con dispositivos móviles
- 🔍 Búsqueda de ciudades
- 📊 Información detallada del clima por localidad
- 🎯 Navegación intuitiva

## 💻 Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos y diseño responsivo
- **Sass** - Preprocesador CSS para mantener estilos modulares y escalables
- **JavaScript (Vanilla)** - Interactividad
- **Bootstrap 5.3.8** - Framework de CSS para diseño responsivo
- **AVIF** - Formato de imagen optimizado

## 📖 Cómo Usar

1. **Abrir la aplicación**
   - Haz clic en `home.html` para acceder a la página principal.

2. **Navegar**
   - Utiliza la barra de navegación para moverte entre páginas.
   - Selecciona una ciudad para ver detalles específicos del clima.

3. **Ver detalles**
   - Cada ciudad tiene su propia página con información específica. En estos momentos se modificó para integrar JavaScript para preparla para integración de API futura, por lo que sólo hay una hoja que se modificará para que la misma interactúe para cada localidad.
   - La página "About" contiene información sobre el proyecto.

## 🎯 Páginas Principales

| Página | Descripción |
|--------|-------------|
| `home.html` | Página inicio con las ciudades disponibles |
| `about.html` | Información sobre el proyecto |
| `detalles-*.html` | Detalles específicos del clima de cada ciudad incluyendo un pronóstico semanal. |

## 🔧 Instalación

No requiere instalación para usarlo en el navegador. Simplemente:

1. Descarga o clona el repositorio
2. Abre `home.html` en tu navegador web
3. ¡Disfruta explorando el clima!

> Si trabajas en el desarrollo, los estilos se mantienen en el directorio `sass/` y se compilan en `assets/css/main.css`.

## 📝 Desarrollo

El proyecto fue desarrollado como parte del Bootcamp Front End, demostrando habilidades en:

- Maquetación HTML
- Estilos CSS avanzados con Sass
- JavaScript vanilla
- Diseño responsivo
- Uso de frameworks modernos

Si editas estilos, modifica los archivos en `sass/` y vuelve a compilar para actualizar `assets/css/main.css`.

## 🤝 Contribuciones

Este proyecto fue desarrollado durante el bootcamp. Las sugerencias y mejoras son bienvenidas.

## 📄 Licencia

Este proyecto es de uso educativo.

Para acceder al repositorio en Github--> [gh Vanne-TD/weather-frontend-m3](https://github.com/Vanne-TD/weather-frontend-m3.git)


---

**Creado durante:** Bootcamp Front End Trainee
**Última actualización:** Mayo 2026

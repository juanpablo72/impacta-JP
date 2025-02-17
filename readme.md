# Impacta-JP 🚀

## Estructura del Proyecto

```plaintext
├── index.html # Punto de entrada principal
├── css/ # CSS compilado desde Sass
│ └── base.css
│ └── scss/ # Fuentes Sass
│   └──base.scss # Reset, tipografía, elementos globales
├── fonts/ # fuente descargada
├── img/ # Imágenes  (Fotos e iconos , logos, portada)
└── README.md # Documentación (estás aquí)
```

## Decisiones de Diseño 🎨

### HTML

- **Semántica Estricta**: Uso de HTML5 con etiquetas semánticas
- **Componentización**: Archivos parciales HTML reutilizables en carpetas lógicas

### Sass (SCSS)

- **Metodología 7-1**: Estructura modular escalable
- **Mobile-First**: Media queries anidados con `min-width`
- **Variables CSS**: Colores, breakpoints y tamaños centralizados

## Requisitos

- Node.js (para compilación Sass)
- Sass CLI: `npm install -g sass`

## Quick Start 🚦

```bash
sass --watch sass/main.scss:css/main.css

o

sass --watch css/scss/:css/

```

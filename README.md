# Portafolio UX/UI Designer

Portafolio personal de diseñadora UX/UI y Product Designer. Desarrollado con HTML y CSS siguiendo la metodología Atomic Design.

## Estructura del proyecto

```
portfolio/
├── index.html          # Página principal
├── sobre-mi.html       # Página sobre mí
├── proyecto-1.html     # Páginas de proyectos (1-5)
├── css/
│   ├── tokens/         # Colores, tipografía, espaciado
│   ├── atoms/          # Botones, links, iconos
│   ├── molecules/      # Cards, navegación, hero
│   ├── organisms/      # Header, footer, grid
│   └── pages/          # Estilos específicos por página
├── js/
├── assets/
│   └── images/         # Imágenes de proyectos
└── README.md
```

## Cómo usar

1. Coloca tus imágenes de proyectos en `assets/images/` (proyecto-1.jpg, proyecto-2.jpg, etc.)
2. Reemplaza `[Tu Nombre]` en todas las páginas por tu nombre
3. Actualiza los enlaces de email, LinkedIn y Behance en el footer
4. Personaliza el contenido de cada proyecto y la página sobre mí

## Ver el portafolio

Abre `index.html` en tu navegador o usa un servidor local:

```bash
# Con Python
python3 -m http.server 8000

# Con Node.js (npx)
npx serve
```

Luego visita `http://localhost:8000`

## Sistema de diseño

- **Colores**: Crema, cafés y rojo como acento (variables en `css/tokens/colors.css`)
- **Tipografía**: Sistema de fuentes escalable
- **Espaciado**: Escala consistente de 4px a 128px

## Integración con Pencil.dev

El proyecto está conectado a [Pencil.dev](https://pencil.dev) para diseñar en lienzo y mantener sincronizado el sistema de diseño.

### Archivo de diseño

- **`portfolio.pen`**: Contiene las variables del sistema de diseño (colores, tipografía, espaciado) extraídas del CSS y un hero de ejemplo.

### Uso

1. Abre Pencil (app o extensión en Cursor).
2. Abre `portfolio/portfolio.pen` o la carpeta del proyecto.
3. Las variables ya están configuradas. Al diseñar en Pencil, usa referencias como `$color.accent`, `$spacing-md`, `$font.size-lg`, etc.
4. Para sincronizar cambios entre Pencil y el CSS, pide al asistente de Cursor que actualice uno u otro según lo que modifiques.

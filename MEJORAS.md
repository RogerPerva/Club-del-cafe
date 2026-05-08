# Propuesta de mejoras para Club del Café

## 1) Accesibilidad y semántica (prioridad alta)
- Cambiar `lang="en"` a `lang="es"` en todas las páginas en español.
- Corregir textos alternativos genéricos (`alt="imagen blog"`) por descripciones reales.
- Añadir estado de foco visible (`:focus-visible`) en enlaces y botones para navegación con teclado.
- Revisar jerarquía de encabezados (evitar saltos de nivel y mantener un solo `h1` principal por página).

## 2) Calidad HTML/CSS (prioridad alta)
- Corregir typos de atributos (`rcset` -> `srcset`) y valores inválidos en CSS (`margin-bottom: none;` -> `0`).
- Eliminar atributos no aplicables en `<link rel="stylesheet">` (por ejemplo `as="font"` fuera de preload).
- Unificar consistencia de nombres y ortografía en contenido (`Tecnicas` -> `Técnicas`, etc.).

## 3) Rendimiento web (prioridad media)
- Definir dimensiones (`width` y `height`) en imágenes para reducir CLS.
- Servir formatos modernos (`webp/avif`) de forma consistente en todas las imágenes de contenido.
- Minificar CSS y usar caché con versiones/hash en archivos estáticos.

## 4) SEO básico (prioridad media)
- Personalizar `<title>` y `<meta name="description">` por página, no solo en index.
- Añadir metadatos Open Graph/Twitter para compartir en redes.
- Evaluar datos estructurados (`Article`, `Blog`, `Organization`) según el contenido.

## 5) Mantenibilidad y escalabilidad (prioridad media)
- Separar estilos en capas/módulos (`base`, `layout`, `components`, `utilities`).
- Añadir linting y formateo automático (HTML/CSS/JS) en un script de proyecto.
- Documentar convenciones en un `README.md` con cómo ejecutar, estructura y checklist de calidad.

## 6) Experiencia de usuario (prioridad baja)
- Crear página 404 y mejorar rutas internas (varios botones apuntan a `entrada.html`).
- Mejorar microcopy (beneficios concretos de cursos, CTA más claros y orientados a conversión).
- Añadir validación y feedback visual en formulario de contacto.

## Quick wins sugeridos para comenzar
1. Corregir `lang`, `srcset` y `margin-bottom: 0`.
2. Mejorar `alt` de imágenes y foco visible en navegación.
3. Optimizar títulos/descripciones por página.


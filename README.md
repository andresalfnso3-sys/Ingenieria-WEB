# Portafolio Personal — Práctica HTML5 Semántico + Flexbox Responsivo

Página de portafolio personal construida con HTML5 semántico y CSS Flexbox responsivo, sin frameworks.

## Integrantes

| Nombre | Rol / Parte asignada |
|---|---|
| Julian Andres Peñuela Alfonso | Estructura HTML semántica |
| Diego Alejandro Lopez Castellano | Formulario de contacto + accesibilidad (WAVE / W3C) |
| David Alejandro García Lozano | CSS Flexbox responsivo |

## Descripción del proyecto

Portafolio de una sola página con:
- Header con navegación
- Sección de presentación (hero)
- Sección de proyectos en cards (layout Flexbox: 1 columna en móvil, 3 en escritorio)
- Sección "Sobre mí"
- Formulario de contacto accesible
- Footer con navegación secundaria

## Tecnologías

- HTML5 semántico (`header`, `nav`, `main`, `section`, `article`, `footer`)
- CSS3 con Flexbox (sin frameworks, sin Bootstrap)
- Diseño mobile-first con 2 breakpoints (tablet y escritorio)

## Estructura de carpetas

```
/
├── index.html
├── css/
│   └── styles.css
├── screenshots/
│   ├── mobile.png
│   ├── tablet.png
│   ├── desktop.png
│   └── wave-report.png
└── README.md
```

## Cómo ejecutar

Abrir `index.html` directamente en el navegador (no requiere servidor ni build).

## Reparto de tareas

**Persona 1 — Estructura HTML semántica**
- Esqueleto con `header`, `nav`, `main`, `section`/`article`, `footer`
- Un solo `main` por página, `nav` con `aria-label` cuando hay más de uno

**Persona 2 — Formulario + accesibilidad**
- Formulario de contacto con labels asociados (`label for`)
- Validación con W3C y WAVE, corrección de errores

**Persona 3 — CSS Flexbox responsivo**
- Contenedor flex y sus propiedades (`flex-direction`, `justify-content`, `align-items`)
- Layout probado en los 3 breakpoints: móvil (<768px), tablet (~700px), escritorio (≥768px)

## Validaciones realizadas

- [ ] Validador de HTML del W3C — sin errores críticos
- [ ] Extensión WAVE — landmarks correctos, sin errores de accesibilidad
- [ ] Capturas en 3 tamaños de viewport (móvil, tablet, escritorio)
- [ ] Captura del reporte WAVE

## Licencia

Proyecto académico, sin licencia de uso comercial.

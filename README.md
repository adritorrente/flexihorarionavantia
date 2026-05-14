# 🚢 Navantia · Calculadora de Horarios — Paquete de Deploy

## Contenido del paquete

```
navantia-deploy/
├── index.html      ← aplicación completa (logo SVG oficial inline, sin dependencias externas de imágenes)
├── vercel.json     ← configuración lista para Vercel
├── netlify.toml    ← configuración lista para Netlify
└── README.md       ← este archivo
```

---

## Instrucciones para Claude (deploy automático)

### Opción A — Vercel

> "Sube la carpeta `navantia-deploy` a Vercel como sitio estático. El archivo principal es `index.html`. Usa la configuración de `vercel.json` incluida."

### Opción B — Netlify

> "Despliega la carpeta `navantia-deploy` en Netlify. El directorio de publicación es `.` (raíz). Usa `netlify.toml` incluido."

---

## Notas

- **Un solo archivo HTML** — sin dependencias de servidor, sin base de datos.
- **Logo oficial Navantia 2019** integrado como SVG inline (no requiere conexión externa).
- **Color corporativo** `#005db5` extraído del SVG oficial.
- Fuentes Google Fonts (Barlow Condensed) — se cargan al abrir; funciona offline con fuentes del sistema como fallback.
- Compatible con Chrome, Firefox, Safari, Edge modernos. Responsive (móvil y escritorio).

---

*INFRA FERROL · Sistemas Inteligentes — Navantia S.A.*

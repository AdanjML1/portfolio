# Portfolio — Adán de Jesús Moo Lugo

Portfolio personal con navegación por slides a pantalla completa. Un solo archivo HTML, sin build ni dependencias de npm.

## Características

- **5 secciones:** Inicio, Aurora UI, Verde Studio, Nebula App y Contacto
- **Scroll vertical** con trackpad o rueda para avanzar entre slides (sin scroll horizontal manual)
- **Navegación** por tabs, teclado (← →), swipe táctil y botón CTA
- **Fondo animado** que interpola colores según la posición del slide
- **Parallax** con el ratón en imágenes flotantes

## Estructura

```
portfolio/
├── index.html    # HTML, CSS y JavaScript del sitio
├── README.md
└── .gitignore
```

## Desarrollo local

Desde la raíz del proyecto:

```bash
python3 -m http.server 8080
```

Abre [http://localhost:8080](http://localhost:8080) en el navegador.

## Deploy

Sitio estático. No requiere paso de build.

**Cloudflare Pages**

| Campo | Valor |
|-------|-------|
| Framework preset | None |
| Build command | *(vacío)* |
| Build output directory | `/` |

Cualquier hosting de archivos estáticos (GitHub Pages, Netlify, etc.) funciona igual: sirve `index.html` en la raíz.

## Licencia

Proyecto personal. Ajusta la licencia si lo publicas con otro uso.

# Game Critic

Blog de reseñas de videojuegos realizado con html y css puro, estilos y nombre con disposición a rotar.

## Estructura

```
blog_web24/
├── index.html          ← página aterrizaje
├── css/
│   └── styles.css      ← estilos globales
├── img/                ← imágenes de los juegos y favicons
├── pages/
│   ├── review.html     ← sección de reviews (placeholder)
│   ├── galeria.html    ← galería (placeholder)
│   ├── nosotros.html   ← equipo (placeholder)
│   ├── contacto.html   ← contacto (placeholder)
│   ├── login.html      ← login/registro (placeholder)
│   └── 404.html        ← página de error (ya esta aplicada)
```

## Cómo levantar el proyecto

Seguramente se lo suba por vercel.

## Tecnologías

- HTML5
- CSS3 (variables, flexbox, grid, media queries)
- Bootstrap 5.3.3 (CDN) solo para navbar, grid y componentes base
- Bootstrap Icons (CDN)

## Estado actual

- [x] Landing page con carousel, cards de reviews, sidebar y newsletter
- [x] Página 404
- [ ] Reviews (estructura base armada, falta contenido)
- [ ] Galería
- [ ] Nosotros
- [ ] Contacto
- [ ] Login / Registro

## Notas

- Las páginas que están como placeholder tienen comentarios HTML indicando qué se puede implementar en cada una.
- El CSS tiene variables en `:root` para mantener consistencia con los colores y tipografías.
- Los favicons están en `img/favicon/`.

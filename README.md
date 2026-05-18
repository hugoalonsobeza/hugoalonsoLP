# Hugo Alonso — Landing personal

Carta de presentación digital. Freelance de desarrollo web y marketing digital desde Donostia.

**Live:** [hugoalonso.studio](https://hugoalonso.studio) *(o subdominio de Vercel mientras tanto)*

---

## Sobre este proyecto

Landing minimalista premium construida con HTML5 + Tailwind CSS (vía CDN). Sin build step, sin frameworks pesados — solo lo que hace falta para que el sitio cargue rápido, se vea bien y se mantenga fácil.

El repo incluye:

- `index.html` — la landing principal
- `aritza/` — demo concept: web de restaurante (Aritza Bistró)
- `norte/` — demo concept: portfolio de estudio creativo (Norte Studio)
- `lurra/` — demo concept: e-commerce de café (Lurra Coffee)
- `favicon.svg` — favicon vectorial
- `og-image.svg` — imagen para Open Graph / redes sociales
- `robots.txt` · `sitemap.xml` — SEO básico

## Stack

- HTML5 semántico
- Tailwind CSS (Play CDN)
- Vanilla JS (IntersectionObserver para animaciones)
- Fuentes: Inter + Instrument Serif (Google Fonts)
- Formspree para el formulario de contacto

## Estructura

```
.
├── index.html              # Portfolio principal
├── aritza/index.html       # Demo restaurante
├── norte/index.html        # Demo estudio creativo
├── lurra/index.html        # Demo e-commerce café
├── favicon.svg
├── og-image.svg
├── robots.txt
├── sitemap.xml
└── vercel.json
```

## Desarrollo local

No hace falta build — abre `index.html` directamente con doble clic, o sirve la carpeta con cualquier servidor estático:

```bash
# Con Python (preinstalado en Mac/Linux)
python3 -m http.server 8000

# Con Node
npx serve .
```

Visita `http://localhost:8000`.

## Deploy

El sitio está desplegado en Vercel. Cada push a `main` actualiza la web automáticamente.

```bash
# Primera vez:
git push -u origin main

# Cambios siguientes:
git add .
git commit -m "Update copy"
git push
```

## Contacto

- **Email** — hugoalonsobeza@gmail.com
- **LinkedIn** — [/hugo-alonso-bezanilla](https://www.linkedin.com/in/hugo-alonso-bezanilla)
- **Ubicación** — Donostia, ES · Remoto

---

© 2026 Hugo Alonso Bezanilla. Todos los derechos reservados.

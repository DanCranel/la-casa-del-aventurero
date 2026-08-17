# La Casa del Aventurero 🎲🍺

Sitio web (landing de una sola página) para **La Casa del Aventurero**, una taberna de juegos casera: juegos de mesa, rol (D&D) y videojuegos, con una cocina de salchipapas, hot dogs, café y snacks.

🔗 **Demo en vivo:** https://la-casa-del-aventurero.vercel.app

> Proyecto desarrollado por **[Cranel Studios](https://github.com/DanCranel)**.

---

## ✨ Características
- **Diseño temático** de pergamino / taberna medieval, hecho con CSS y SVG (sin imágenes pesadas para las texturas).
- **Una sola página** con navegación: Inicio, Menú, Equipamiento, Eventos, Gremio y Contacto.
- **100% responsive**, optimizado para móvil (que es donde más se usa).
- **Intro animada**: un pergamino que se abre al entrar.
- **Menú** con fotos, precios y combos.
- **Contacto** con enlaces directos a WhatsApp y Google Maps.
- **Rendimiento**: imágenes optimizadas en formato WebP, `loading="lazy"`, fuentes con `display=swap`.
- **SEO y compartir**: meta description, Open Graph y favicon.

## 🛠️ Tecnologías
- HTML5 semántico
- CSS3 (Flexbox, Grid, animaciones, variables, `mask`/SVG)
- JavaScript mínimo (intro)
- Tipografías: Cinzel, MedievalSharp, EB Garamond (Google Fonts)
- Despliegue: **Vercel** (auto-deploy desde GitHub)

## 📁 Estructura
```
├── index.html        # Toda la página (HTML + CSS + JS)
├── images/           # Logo, sello, retratos y fotos del menú (WebP)
├── PRD.md            # Documento de requisitos / roadmap
├── LICENSE           # © Cranel Studios
└── README.md
```

## 🚀 Desarrollo
Al ser un sitio estático, basta con abrir `index.html` en el navegador. Los cambios se publican solos en Vercel al hacer push a `main`.

## 📄 Licencia
© 2026 **Cranel Studios**. Todos los derechos reservados. Ver [LICENSE](LICENSE).
Publicado con fines de portafolio.

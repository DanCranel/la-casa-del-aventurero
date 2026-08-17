# PRD — La Casa del Aventurero (Sitio Web)

> **PRD** = *Product Requirements Document* (documento que resume qué es el producto, qué tiene hoy, y qué se puede agregar/mejorar).
> Última actualización: 8 de agosto de 2026.

---

## 1. Visión
La Casa del Aventurero es un espacio casero tipo taberna de juegos (montado en la cochera de casa) donde la gente va a jugar **juegos de mesa, rol (D&D) y videojuegos**, mientras consume **comida rápida, café, bebidas y snacks**. El negocio genera ingresos por la venta de comida y bebida.

El sitio web es la **carta de presentación digital**: muestra el menú, lo que se puede jugar, los eventos, quiénes atienden y cómo llegar. Debe verse genial en el celular (la mayoría escaneará un QR en el local).

## 2. Objetivos del sitio
1. Que un cliente vea el **menú** y los **precios** en segundos desde el celular.
2. Comunicar la **experiencia** (juegos, rol, eventos) para atraer visitas.
3. Facilitar el **contacto y cómo llegar** (WhatsApp + Google Maps).
4. Dar **identidad de marca** (temática aventurero/taberna, el gato mascota).

## 3. Público objetivo
- Jóvenes y adultos jóvenes gamers / jugadores de rol y mesa.
- Familias y niños (ambiente casero y sano).
- Grupos de amigos que buscan un plan diferente.

---

## 4. Lo que YA tenemos (estado actual)
- **Sitio de una sola página** con navegación (Inicio, Menú, Equipamiento, Eventos, Gremio, Contacto).
- Diseño temático de **pergamino de taberna medieval** (rollos, bordes rasgados, texturas) hecho con código (ligero, sin imágenes pesadas).
- **Responsive**: se adapta a celular, con menú hamburguesa.
- **Logo** del gato aventurero integrado.
- **Menú** con comida (salchipapas, hot dogs, tostadas), bebidas (colas, jugos, café, cerveza), snacks y combos, con espacios para fotos de cada producto.
- **Equipamiento**: lista de juegos de mesa y videojuegos.
- **Eventos**: torneos de viernes (mesa) y sábado (videojuego) por votación, y D&D a pedido.
- **Gremio (equipo)**: dos aventureros con foto, nombre y rol.
- **Contacto**: WhatsApp (098 992 3143) y ubicación en Google Maps, con horarios.
- **Publicado en internet**: GitHub + Vercel con actualización automática.

## 5. Pendientes inmediatos (para completar lo actual)
- [ ] **Precios reales** de cada producto (hoy están en blanco).
- [ ] **Fotos reales** de los platos y bebidas.
- [ ] **Nombres reales** del equipo (Gremio).
- [ ] **Instagram / redes** (falta el usuario).
- [ ] Confirmar/afinar **dirección escrita** (además del mapa).
- [ ] Generar **código QR** con el link para imprimir en las mesas.
- [ ] Considerar **dominio propio** (ej. `lacasadelaventurero.com`).

---

## 6. Lo que podemos AGREGAR (ideas de nuevas funciones)
Ordenado por impacto/esfuerzo aproximado.

### Corto plazo (fácil, alto valor)
- **Botón flotante de WhatsApp** siempre visible para escribir/reservar rápido.
- **Sección de precios visible** y bien formateada.
- **Galería de fotos** del local y del ambiente (para dar confianza).
- **Enlaces a redes sociales** (Instagram, TikTok, Facebook).
- **Google Business Profile** (aparecer en Google Maps y búsquedas locales).

### Mediano plazo
- **Reservas de D&D / mesas** mediante un formulario o directo a WhatsApp con mensaje prellenado.
- **Calendario/agenda de eventos** que se pueda actualizar fácil.
- **Votación de torneos** en línea (encuesta semanal del juego a jugar).
- **Menú con categorías filtrables** y etiquetas (vegetariano, picante, sin alcohol).
- **Sección de reseñas/testimonios** de clientes.

### Largo plazo
- **Programa de fidelidad** (sellos por visita, "gremio de miembros").
- **Tienda/reserva de productos** o venta de entradas a torneos.
- **Panel de administración** para editar menú/eventos sin tocar código.
- **Blog o novedades** (reseñas de juegos, guías de rol).

## 7. Lo que podemos MEJORAR (calidad de lo existente)
- **Precios y fotos** dan profesionalismo inmediato (prioridad 1).
- **Rendimiento**: optimizar tamaño de imágenes (comprimir el logo y fotos).
- **SEO local**: título, descripción, palabras clave ("juegos de mesa", ciudad), datos estructurados de negocio.
- **Accesibilidad**: textos alternativos en imágenes, contraste, tamaños de toque.
- **Compartir en redes**: imagen de vista previa (Open Graph) para que se vea bonito al enviar el link por WhatsApp.
- **Favicon** con el gato/sello.

---

## 8. Requisitos técnicos (stack actual)
- **HTML + CSS** puros (una sola página, sin framework). Muy ligero y fácil de mantener.
- **Hosting**: Vercel (gratis), conectado a **GitHub** (repo privado `DanCranel/la-casa-del-aventurero`).
- **Flujo de actualización**: editar `index.html` → subir a GitHub → Vercel publica solo.
- **Imágenes**: carpeta `images/` (logo, sello, aventureros, fotos de platos).

## 9. Métricas de éxito (cómo sabremos si funciona)
- Escaneos del QR / visitas al sitio.
- Clics al botón de WhatsApp y a "Cómo llegar".
- Aumento de visitas al local y de reservas de D&D.
- Seguidores en redes provenientes del sitio.

## 10. Roadmap sugerido (fases)
1. **Fase 1 — Lanzamiento (ahora):** precios, fotos, nombres del equipo, redes, QR. → *Sitio listo para compartir.*
2. **Fase 2 — Crecimiento:** botón WhatsApp flotante, Google Business, galería, Open Graph, SEO local.
3. **Fase 3 — Interacción:** reservas, agenda de eventos editable, votación de torneos.
4. **Fase 4 — Escala:** panel de administración, fidelidad, dominio propio consolidado.

---

*Este documento es vivo: lo iremos actualizando conforme avance el proyecto.*

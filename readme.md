# 🎮 Pacman — Mantenimiento & Sostenibilidad de Sistemas

Sitio web corporativo para **Pacman**, empresa especializada en mantenimiento y sostenibilidad de sistemas informáticos.

---

## 📁 Estructura del Proyecto

```
pacman-web/
├── index.html       → Página principal
├── contact.html     → Página de contacto
├── style.css        → Estilos globales (todas las páginas)
├── contact.css      → Estilos específicos de contacto
└── README.md        → Este archivo
```

---

## 🎨 Paleta de Colores

| Variable | Hex | Uso |
|----------|-----|-----|
| `--c1` | `#8A7650` | Dorado tierra — color principal, botones, acentos |
| `--c2` | `#8E977D` | Verde sage — íconos secundarios, badges |
| `--c3` | `#ECE7D1` | Crema claro — fondos claros, texto sobre oscuro |
| `--c4` | `#DBCEA5` | Crema dorado — fondos de sección, bordes |
| `--c5` | `#9F8383` | Rosa grisáceo — logo Pacman, acentos especiales |
| `--dark` | `#2A2720` | Casi negro — navbar, hero, secciones oscuras |

---

## 🔤 Tipografía

| Uso | Fuente |
|-----|--------|
| Títulos y encabezados | **Orbitron** (Google Fonts) |
| Cuerpo y párrafos | **Share Tech** (Google Fonts) |
| Contact.html (todo) | **Share Tech** (exclusivo) |

Ambas fuentes se cargan desde Google Fonts mediante `@import` en `style.css`.

---

## 📄 Páginas

### `index.html` — Página Principal
- **Navbar** fija con menú hamburguesa para móvil
- **Hero** con Pacman animado, fantasmas y puntos parpadeantes
- **Stats band** con métricas destacadas (clientes, uptime, años, etc.)
- **Servicios** — 8 tarjetas con animación lift al hacer clic
- **Quiénes somos** — sección informativa alternada
- **Misión** — valores y compromisos
- **Visión** — perspectiva y crecimiento futuro
- **Proceso** — 5 pasos del flujo de trabajo
- **Glosario** — tabla de 12 términos técnicos con categorías
- **CTA band** — llamada a la acción hacia contacto
- **Footer** con navegación

### `contact.html` — Página de Contacto
- **Hero** de contacto con badge animado
- **4 tarjetas de información**: teléfono, email, ubicación, horario
- **Formulario de mensaje** con campos completos y validación visual
- **Portal de login** con toggle de contraseña
- **Sección "Sobre Nosotros"** con 4 tarjetas de beneficios
- **Horarios detallados** (oficina, remoto, contacto directo)

---

## ✨ Características

### Animaciones
- Logo Pacman con boca animada (CSS `@keyframes`)
- Fantasmas rebotando con colores `#37353E`, `#44444E`, `#715A5A`, `#D3DAD9`
- Puntos parpadeantes en el hero
- **Cards con efecto lift** al hacer clic o hover (sube + sombra)
- Línea activa animada en links de navegación

### Interactividad
- Menú hamburguesa funcional con animación de apertura/cierre
- Tabs para cambiar entre formulario de mensaje y login
- Toggle para mostrar/ocultar contraseña
- Mensaje de confirmación al enviar formulario
- Resaltado de sección activa en navbar al hacer scroll

### Diseño Responsivo
- Grid adaptable con `auto-fit` y `minmax()`
- Menú móvil completo
- Formulario de 2 columnas colapsa a 1 columna en pantallas pequeñas

---

## 📞 Información de Contacto

| Canal | Detalle |
|-------|---------|
| Teléfono | 7111-1853 |
| Correo | Pacmansss1@gmail.com |
| Ubicación | San Salvador, El Salvador |
| Horario Oficina | Lun–Vie 9:00–17:00 / Sáb 9:00–12:00 |
| Soporte Remoto | Lun–Vie 8:00–18:00 / Emergencias 24/7 |

---

## 🛠️ Tecnologías

- HTML5 semántico
- CSS3 (variables, grid, flexbox, keyframes, transitions)
- JavaScript vanilla (sin frameworks)
- [Font Awesome 6.5](https://fontawesome.com/) — íconos
- [Google Fonts](https://fonts.google.com/) — Orbitron + Share Tech

---

*© 2026 Pacman — Mantenimiento & Sostenibilidad de Sistemas Informáticos*

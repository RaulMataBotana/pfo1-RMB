# PFO1 — Landing de Portafolio | Raúl Alberto Mata Botana

Landing page personal desarrollada como Práctica Formativa Obligatoria N.º 1 (PFO1).
Presenta mi perfil como desarrollador Full Stack: quién soy, mis habilidades técnicas,
mi forma de trabajar y una vía de contacto.

**Autor:** Raúl Alberto Mata Botana
**Contacto:** matabotanar@gmail.com
**Repositorio:** https://github.com/RaulMataBotana/pfo1-RMB

## 🔗 Demo en Vercel

**URL pública:** https://pfo1-rmb.vercel.app

## 📂 Estructura del proyecto

```
├── index.html          # Estructura semántica de la landing
├── css/
│   └── style.css       # Estilos propios (sin frameworks)
├── js/
│   └── script.js       # Toggle del menú mobile
├── assets/
│   ├── avatar.svg       # Ilustración del hero
│   └── workspace.svg    # Ilustración de la sección "Cómo trabajo"
└── README.md
```

## ✅ Requisitos técnicos cumplidos

- **HTML5 semántico:** `header`, `nav`, `main` (con `section` por bloque temático) y `footer`.
- **CSS propio:** hoja de estilos escrita a mano, con variables CSS (design tokens),
  sin frameworks de UI.
- **Google Fonts:** combinación de `Fraunces` (display/serif), `Manrope` (texto) e
  `IBM Plex Mono` (etiquetas y detalle "código").
- **Flexbox y Grid:** Grid para las secciones de habilidades, "sobre mí" y contacto;
  Flexbox para navegación, botones y listas internas.
- **Diseño responsive:** breakpoints en 900px, 720px (menú hamburguesa) y 560px.
- **Animación/transición:** efecto de "tipeo" (typing) con cursor parpadeante en la
  terminal del hero, animación de flotación en el avatar, y transiciones en hover
  de botones, tarjetas y enlaces.
- **Imágenes con `alt`:** dos ilustraciones SVG (`avatar.svg` y `workspace.svg`) con
  textos alternativos descriptivos.
- **Formulario con `label`:** formulario de contacto con `label` asociado a cada
  campo (`for`/`id`) para nombre, correo y mensaje.
- **Enlace a GitHub:** visible en el header (botón), en el hero, en la sección de
  contacto y en el footer, apuntando al repositorio del proyecto.

## 🎨 Decisiones de diseño

- **Concepto:** una estética "editorial de terminal" — combina la calidez de una
  tipografía serif expresiva (Fraunces) para lo humano (el nombre, la presentación)
  con el registro monoespaciado (IBM Plex Mono) para lo técnico (etiquetas, stack,
  la "terminal" del hero). Busca transmitir que soy una persona, pero también que
  pienso en código.
- **Paleta:** fondo oscuro tinta (`#0B0E12`) con paneles ligeramente más claros,
  un acento menta/verde agua (`#6EE7C8`, alude al cursor de una terminal) y un
  acento cálido dorado (`#D9A96C`) usado con moderación para el nombre y detalles
  puntuales. Se evitó deliberadamente la paleta "crema + terracota" y el
  "negro + verde ácido" por ser combinaciones muy repetidas en diseños generados
  por IA; se buscó algo con identidad propia.
- **Elemento distintivo:** la ventana de terminal animada en el hero, que "tipea"
  un objeto JavaScript con mis datos. Es el elemento que un desarrollador
  reconoce de inmediato y funciona como firma visual de la página.
- **Sección personal (sin hobbies):** en vez de una sección de hobbies, se optó
  por "Cómo trabajo", que expone tres principios de trabajo (entender antes de
  programar, priorizar código simple y mantenible, aprendizaje constante). Se
  eligió este enfoque porque aporta información relevante para quien evalúa mi
  perfil profesional.
- **Formulario:** se mantiene simple (nombre, correo, mensaje). El envío usa
  `action="mailto:..."` con `enctype="text/plain"`, por lo que al enviarlo se abre
  el cliente de correo del usuario con el mensaje ya redactado; queda preparado
  para reemplazarse por un servicio de formularios o backend propio más adelante.
- **Privacidad del correo:** la dirección de contacto no se muestra como texto
  visible en ninguna parte de la landing (ni en el hero, ni en la sección de
  contacto, ni en el footer). Solo aparece en el atributo `action` del formulario,
  necesario para que el botón "Enviar mensaje" funcione. El botón "Escribime" del
  hero lleva al formulario en vez de abrir el cliente de correo directamente.

## 🤖 Declaración de uso de Inteligencia Artificial

Este proyecto fue desarrollado con la asistencia de **Claude (Anthropic) versión gratuita**:

- El código HTML, CSS y JavaScript fue generado y ajustado con ayuda de IA a
  partir de los lineamientos y el contenido personal provistos por el autor.
- **Las dos ilustraciones (`assets/avatar.svg` y `assets/workspace.svg`) son
  gráficos vectoriales generados por la IA directamente en código SVG**
  (no son fotografías reales, ni fotos del autor, ni imágenes de stock).
  Se registran aquí conforme a lo solicitado en la consigna.
- El texto de presentación y las copias de cada sección fueron redactados con
  asistencia de IA y luego adaptados para reflejar la situación real del autor
  (estudiante en la Tecnicatura de Desarrollo de Software del IFTS 29).
- Todas las decisiones finales de diseño, estructura y contenido fueron
  revisadas por el autor antes de la entrega.

## Experiencia previa y modo de encarar el proyecto

- No poseía experiencia previa en el desarrollo en el diseño de un porfolio.
- Tenía una experiencia MUY BÁSICA en el diseño HTML.
- Probé distintas directivas hacia la IA para obtener un diseño que me resultase 
  atractivo y cumpliese con los reuisitos pedidos.
- Experimenté con distintos modelos de IA, buscando la solución que mejor se adapte
  a ño que pretendia.

## ▶️ Cómo ejecutar el proyecto localmente

1. Cloná el repositorio o descargá los archivos.
2. Abrí `index.html` en el navegador (no requiere instalación ni build).
3. Opcional: usá una extensión tipo *Live Server* para recarga automática.

# PFO2 — Prompt Engineering en Agentes de IA
### IFTS N.°29 — Ministerio de Educación CABA

---

## 📋 Datos del estudiante

| Campo | Valor |
|---|---|
| **Nombre** | Carlos Eduardo Zarate |
| **Materia** | Front-end |
| **Año** | 2026 |

---

## 🚀 Deploy unificado

> **[→ Ver proyecto en Vercel](PEGAR-AQUÍ-EL-LINK-DEL-DEPLOY)**
>
> _(El deploy todavía no está publicado. Una vez subido a Vercel, reemplazar el texto de arriba por la URL real.)_

El deploy apunta a `index.html` (portada) que contiene los 3 accesos:
- Link 1: Texto plano del prompt
- Link 2: Landing Page — Agente 1 (Claude Code)
- Link 3: Landing Page — Agente 2 (Cursor Agent)

---

## 🗂️ Estructura del proyecto

```
pfo2/
├── index.html          ← Portada con los 3 links
├── README.md
├── prompt/
│   └── prompt.txt      ← Texto plano del prompt
├── agent1/
│   └── index.html      ← Landing generada por Claude Code
└── agent2/
    └── index.html      ← Landing generada por Cursor Agent
```

---

## 🎯 Tema elegido

**SONORA BCN** — Academia de música contemporánea ubicada en Palermo, Buenos Aires. Ofrece clases de guitarra eléctrica, batería, canto, piano, producción musical y teoría. Público: jóvenes y adultos de 15–40 años.

---

## 📝 Prompt exacto utilizado

```
# PROMPT — Landing Page: Academia de Música "SONORA BCN"
# Diseñado siguiendo las guías oficiales de Anthropic y OpenAI

## ROL Y CONTEXTO

Eres un desarrollador web frontend senior especializado en diseño visual de alto impacto.
Tu tarea es crear una Landing Page completa, moderna y funcional para "SONORA BCN",
una academia de música contemporánea ubicada en el barrio de Palermo, Buenos Aires,
Argentina. La academia ofrece clases de guitarra eléctrica, producción musical, canto,
batería y piano. Su público objetivo son jóvenes y adultos de 15 a 40 años con pasión
por la música urbana, el rock, el pop y la música electrónica.

## TAREA PRINCIPAL

Genera un único archivo HTML autocontenido (index.html) con CSS embebido en la
etiqueta <style> y JavaScript mínimo embebido en la etiqueta <script>. No uses
frameworks externos ni librerías adicionales salvo Google Fonts. El resultado debe
ser una Landing Page completa, responsive (mobile-first), visualmente memorable y
lista para producción.

## ESPECIFICACIONES DE DISEÑO

Paleta de colores:
- Fondo principal: #0D0D0D (negro profundo)
- Acento primario: #E8FF00 (amarillo eléctrico neón)
- Acento secundario: #FF3C5F (rojo vibrante)
- Texto principal: #F5F5F5 (blanco suave)
- Texto secundario: #9A9A9A (gris medio)
- Fondo de secciones alternadas: #141414

Tipografía:
- Display/Títulos: "Space Grotesk" (Google Fonts) — peso 700
- Cuerpo: "Inter" (Google Fonts) — peso 400/500

Estética: Diseño oscuro, urbano y enérgico. Bordes afilados (border-radius: 0 o 2px),
líneas de acento en amarillo neón, tipografía bold grande de alto impacto.

## SECCIONES REQUERIDAS

1. HEADER — Navegación fija (logo, menú, hamburguesa mobile)
2. HERO SECTION — H1 impactante "TU MÚSICA. TU IDENTIDAD.", CTA "EMPEZÁ AHORA"
3. SOBRE NOSOTROS — Texto descriptivo + 4 stats grandes en amarillo neón
4. SERVICIOS — Grid 3col con 6 tarjetas (Guitarra, Batería, Canto, Piano, Producción, Teoría)
5. TESTIMONIOS — 3 cards con texto, autor, instrumento y 5 estrellas
6. CONTACTO — Formulario visual (nombre, email, select instrumento, mensaje) + info de contacto
7. FOOTER — 4 columnas + íconos SVG de redes sociales + copyright

## REQUISITOS TÉCNICOS

1. Un solo archivo index.html, sin frameworks
2. Responsive mobile-first, breakpoints 768px y 1024px
3. Smooth scroll + navegación funcional con anclas
4. Menú hamburguesa funcional con JS vanilla
5. Header sticky con cambio de fondo al hacer scroll
6. Animaciones fade-in con IntersectionObserver
7. Hover states con transiciones suaves
8. Meta tags de viewport y description
9. HTML semántico (header, nav, main, section, footer)

## RESTRICCIONES

- NO usar Bootstrap, Tailwind, jQuery ni ningún framework
- NO usar imágenes externas (usar gradientes y SVGs inline)
- NO dejar Lorem ipsum ni secciones vacías
- NO usar border-radius mayor a 4px

## OUTPUT

Entregar únicamente el código completo del archivo index.html,
comenzando con <!DOCTYPE html> y terminando con </html>.
Sin explicaciones adicionales.
```

---

## 🤖 Agentes utilizados

| | Agente 1 | Agente 2 |
|---|---|---|
| **Herramienta** | Claude Code | Cursor Agent |
| **Modelo** | claude-sonnet-4-6 (Anthropic) | GPT-5.5 (OpenAI) |
| **Modificaciones manuales** | Ninguna | Ninguna |

---

## 📸 Capturas de pantalla

### Agente 1 — Claude Code
> [Agregar capturas aquí]

### Agente 2 — Cursor Agent
> [Agregar capturas aquí]

---

## 📚 Referencias

- [Anthropic Prompt Engineering Guide](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)
- [OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering)

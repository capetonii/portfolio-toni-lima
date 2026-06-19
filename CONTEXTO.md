# TONI LIMA PORTFOLIO — MASTER CONTEXT DOCUMENT
Version: 1.0 | Last updated: current session

---

## 👤 PROJECT OWNER DATA

- Real name: José Antônio Lima
- Site name: TONI LIMA
- Age: 27 | Brazilian
- Profession: Senior Graphic Designer + Developer
- Email: josealima.15@gmail.com
- WhatsApp: +55 (61) 99675-3348
- Experience: 8+ years in the audiovisual industry
- Specialties: video editing, motion graphics,
  visual identity, iGaming banners, thumbnails

---

## 💼 WORK EXPERIENCE

### LOCENT TECHNOLOGY (iGaming)
- Role: Senior Graphic Designer
- Period: October/2022 – present
- Activities:
  • Banners for iGaming platforms and social media
  • Interactive animations for engagement
  • Institutional and promotional videos
  • Strategic content aligned with iGaming market

### FREELANCER
- Role: Graphic Designer
- Period: February/2018 – October/2022
- Clients:
  • Los Frango — visual identity + marketing + paid traffic
  • Bellys Brechó — social media content
  • Point do Crepe — menus and digital materials
  • Outthe Clouds — visual identity and communication
  • Planeta Celular e Lima Imports — artwork and graphics

---

## 🎓 COURSES AND CERTIFICATIONS

- Technical Course in Marketing and Social Media
- Educational Robotics for Educators
- Drone Piloting (UAV)

---

## 🛠️ TECHNICAL SKILLS

- Adobe Photoshop
- Adobe Illustrator
- Adobe Premiere Pro
- Adobe After Effects
- Banner and promotional material design
- Motion graphics and animations
- Photography and image composition
- Digital tablet
- Drone Piloting (UAV)
- Web development (HTML, CSS, JS)

---

## 🎨 SITE VISUAL IDENTITY — ABSOLUTE RULES

### Color palette (NEVER CHANGE)
- Main background:   #F5F0E8  (warm beige)
- Dark green:        #2D6A4F  (primary accent)
- Medium green:      #52B788  (secondary accent)
- Primary text:      #1A1A1A
- Secondary text:    #6B6B6B
- Glassmorphism:     rgba(255,255,255,0.05)
- Footer bg:         #1A1A1A

### Typography (NEVER CHANGE)
- Headings:   Playfair Display (Google Fonts)
- Body:       Inter (Google Fonts)
- Hero:       72px | letter-spacing: -0.03em
- Sections:   48px
- Subtitle:   24px
- Body:       16px | line-height: 1.7

---

## 📐 COMPLETE SITE STRUCTURE

### 1. NAVBAR
- Logo "TONI LIMA" in Playfair Display
- Links: About | Skills | Portfolio | Experience | Contact
- PT | EN toggle button (dynamic language switch)
- "Hire Me" button with green border + fill on hover
- Behavior: transparent → frosted glass on scroll
- Active section indicator with animated underline

### 2. HERO
- Oversized title mixing normal and italic weight
- Typewriter effect on subtitle
- Animated "Available for projects" badge
- Primary button: "View Projects"
- Secondary button: "WhatsApp me"
- Floating decorative geometric shapes
- Soft mouse parallax effect
- Animated SVG path drawing on screen
- Aurora effect (animated radial gradient background)

### 3. ABOUT
- Asymmetric 60/40 layout
- Real photo: toni lima.jpeg (already integrated)
- Photo with border-radius 24px and deep shadow
- Full professional summary
- Animated counters on scroll enter:
  • 8+ Years of experience
  • 50+ Projects delivered
  • 10+ Clients served
- "Download CV" button with icon

### 4. SKILLS
- Cards grid with icon + tool name
- Animated progress bar on scroll enter
- Green gradient fill (#2D6A4F → #52B788)
- Tools: Photoshop, Illustrator, Premiere,
  After Effects, HTML, CSS, JS, Figma

### 5. PORTFOLIO — 3D COVERFLOW CAROUSEL
- 3 cards visible simultaneously
- Center card: 260x360px, fully visible
- Side cards: 200x280px, rotateY 3D, opacity 0.6
- Far cards: opacity 0.3
- CSS perspective: 1000px
- Glowing border on center card:
  1px solid rgba(82,183,136,0.5)
- Dark gradient overlay at card base
- Project name + category in card footer
- < > arrows with glassmorphism
- Position dot indicators
- Mobile swipe support (touch events)
- Autoplay every 4 seconds (pause on hover)
- Infinite loop
- Elegant green/beige gradient placeholders
- Code comments showing where to swap images

### 6. SERVICES — GLASSMORPHISM CARDS
- Background: rgba(45, 106, 79, 0.6)
- Glassmorphism: backdrop-filter blur(16px)
- Border: 1px solid rgba(82, 183, 136, 0.25)
- Border-radius: 24px | Padding: 28px
- Green top line: border-top 2px solid #52B788
- Glossy 3D icon with green glow (48-56px)
- Title: white, Playfair Display, bold, 22px
- Text: white opacity 0.7, Inter, 14px
- Circular arrow at bottom right (#52B788)
- Hover: translateY -6px + brighter border +
  box-shadow 0 20px 60px rgba(45,106,79,0.4)

### 7. EXPERIENCE
- Vertical timeline with central green line
- Alternating left/right cards
- Pulsing green dot on current role
- Company + role + period + description
- Scroll entrance animation

### 8. TESTIMONIALS
- Cards with circular photo, name, role, stars
- Testimonial text in italic
- Smooth autoplay carousel
- Placeholders ready for real testimonials

### 9. CONTACT
- Animated float label inputs
- Fields: Name, Email, Service, Message
- Submit button with animated loading state
- Direct WhatsApp link: +55 (61) 99675-3348
- Email: josealima.15@gmail.com
- Social media icons with colored hover

### 10. FOOTER
- Dark background: #1A1A1A
- Green gradient top divider
- Toni Lima copyright
- Quick links to sections
- Social icons

---

## ✨ IMPLEMENTED VISUAL EFFECTS

### Global
- Custom cursor (smooth trailing circle)
- Subtle noise texture (SVG filter)
- Scroll reveal: fade + translateY(30px) via
  Intersection Observer
- Blurred light orbs behind sections
- Subtle dot grid pattern on background
- Organic SVG wave dividers between sections
- Section divider: transparent→green→transparent gradient

### Cards
- Glassmorphism: backdrop-filter blur(20px) saturate(180%)
- Subtle green rgba borders
- Green inner glow
- 3D hover lift with deep shadow

### Buttons
- Shimmer (light sweep) on hover
- Pulsing border glow on primary buttons
- Colored shadow: green rgba box-shadow
- Soft internal gradient

### Typography
- Numbers/stats with subtle green glow
- Badges with dark background + green border

---

## 🌐 PT/EN TRANSLATION SYSTEM

- PT | EN toggle in navbar
- All strings in JSON object in JavaScript
- Dynamic swap without page reload
- Preference saved in localStorage
- Default language: Portuguese
- ALL new changes must include PT and EN versions

---

## ⚙️ TECHNICAL REQUIREMENTS

- Single file: index.html
- CSS custom properties (--color-*, --font-*)
- Vanilla JavaScript (no frameworks)
- Intersection Observer for scroll animations
- Mobile-first responsive
- Google Fonts only (no external CDN)
- No jQuery, React, Vue or similar

---

## 📋 RULES FOR NEXT SESSIONS

1. ALWAYS read this file before any change
2. NEVER change colors, fonts or base structure
3. ALWAYS maintain responsiveness
4. ALWAYS add PT and EN versions for new text
5. NEVER create separate files (everything in index.html)
6. ALWAYS test hover, animations and mobile before finishing
7. When adding new section, follow existing visual pattern

---

## 🚧 PLANNED IMPROVEMENTS

- [ ] Add real project images to the carousel
- [ ] Fill testimonials with real client reviews
- [ ] Add more projects to the portfolio
- [ ] Create individual project page (modal or new page)
- [ ] Integrate contact form with backend or EmailJS
- [ ] Add custom favicon
- [ ] Optimize performance (lazy loading on images)
- [ ] Add complete SEO meta tags
- [ ] Create optional dark mode

---

## 🎬 INTRO / TELA DE ABERTURA (recurso opcional e reversível)

Overlay em tela cheia que toca um vídeo ao abrir o site, começa mudo (com botão
de som), e some com fade quando o vídeo termina. É uma ADIÇÃO isolada — o site
funciona 100% com ela desligada ou removida.

- Vídeo: `imagem inicial/Retro_computer_idle_animation_202606191622.mp4` (~10s)
  - No HTML o caminho usa `%20` nos espaços: `imagem%20inicial/...`
  - A pasta `imagem inicial/` precisa ir junto no commit/deploy (senão dá 404 →
    a rede de segurança revela o site mesmo assim).
- Tudo vive em 3 blocos marcados em `index.html`:
  - HTML: `<!-- INTRO START -->` … `<!-- INTRO END -->` (logo após `<body>`)
  - CSS:  `/* INTRO START */` … `/* INTRO END */` (no fim do `<style>`)
  - JS:   `/* INTRO START */` … `/* INTRO END */` (no fim do `<script>`)

### Como DESLIGAR (mantendo o código)
No bloco JS da intro, troque o interruptor:
`const INTRO_ENABLED = true;`  →  `const INTRO_ENABLED = false;`
O overlay nasce `display:none`; com o interruptor em false ele nunca aparece e o
site abre direto. Nada mais precisa ser mexido.

### Como REMOVER de vez
Apague os 3 blocos entre os marcadores `INTRO START`/`INTRO END` (HTML, CSS e JS).
Opcionalmente, apague a pasta `imagem inicial/`. O site continua idêntico.

### Trocar enquadramento do vídeo
No CSS `.intro-video`, a propriedade `object-fit: contain` (mostra o vídeo
inteiro, centralizado, sem cortes — pode deixar faixas) pode virar `cover`
(preenche a tela, mas corta as bordas). É a única linha a mudar.

O fundo do overlay e das faixas é `#DFDBD2` (bege claro amostrado do próprio
fundo do vídeo), para as faixas ficarem imperceptíveis e o vídeo parecer
flutuando centralizado.

Observação: `#DFDBD2` é usado SOMENTE no fundo da intro — não faz parte da paleta
do site (que permanece inalterada).

---

## 🎥 VÍDEO 3D NO CABEÇALHO (hero) — reversível

O objeto decorativo SVG do hero (grade + curvas, à direita do título) foi
SUBSTITUÍDO por um vídeo em loop, na MESMA posição. É reversível.

- Vídeo: `video 3d cabeçario/video para o cabeçario.mp4` (760×600, ~19 MB)
  - No HTML o caminho é codificado: `video%203d%20cabe%C3%A7ario/...`
  - Poster (1º frame): `video 3d cabeçario/poster.jpg`
  - A pasta `video 3d cabeçario/` (vídeo + poster) precisa ir junto no commit/deploy.
- Atributos: `muted autoplay loop playsinline preload="metadata"`.
- O container `.hero-video-wrap` usa `aspect-ratio: 760/600` e o vídeo usa
  `object-fit: contain` → mostra o quadro INTEIRO, sem cortar e sem distorcer.
  `background: transparent` → objeto flutuando, sem card/borda.
- Responsivo: mesma regra do elemento antigo (420px no desktop, 280px no mobile).
- O parallax do mouse continua agindo sobre `#hero-visual` (intocado).

### Marcadores
- HTML: `<!-- HERO VIDEO START -->` … `<!-- HERO VIDEO END -->` (dentro de `#hero-visual`)
- CSS:  `/* HERO VIDEO START */` … `/* HERO VIDEO END */` (logo após `.hero-svg`)
- JS: nenhuma alteração foi necessária.

### Como VOLTAR ao objeto decorativo antigo
Dentro de `<!-- HERO VIDEO START/END -->` no HTML: descomente o bloco
`<div class="hero-svg-wrap">…</div>` (que está logo acima do vídeo) e apague o
`<div class="hero-video-wrap">…</div>`. A CSS antiga do SVG foi mantida intacta,
então o original volta a funcionar na hora. (Opcional: apagar o bloco CSS
`/* HERO VIDEO START/END */` e a pasta `video 3d cabeçario/`.)

Nota de performance: o vídeo tem ~19 MB e fica acima da dobra (autoplay) → pode
reduzir um pouco a nota de Performance até ser recomprimido.

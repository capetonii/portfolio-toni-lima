# TONI LIMA PORTFOLIO — MASTER CONTEXT DOCUMENT
Version: 2.0 (REDESIGN) | Last updated: 09/10/2026 — branch `redesign`

> O código (`index.html`) é sempre a fonte da verdade. Este documento descreve o
> estado após o redesign de out/2026.

---

## 👤 PROJECT OWNER DATA

- Real name: José Antônio Lima
- Site name: TONI LIMA
- Age: 27 | Brazilian
- Profession: Senior Graphic Designer + Developer
- Email: josealima.15@gmail.com
- WhatsApp: +55 (61) 99675-3348
- Experience: 8+ years in the audiovisual industry
- Projects delivered: 67
- Specialties: video editing, motion graphics, visual identity, iGaming banners, thumbnails

### Links oficiais (sempre https, target="_blank", rel="noopener noreferrer")
- LinkedIn: https://www.linkedin.com/in/jos%C3%A9-ant%C3%B4nio-lima-7a75862a3 (texto: linkedin.com/in/josé-antônio-lima)
- Behance: https://www.behance.net/eduardavesoarto
- Instagram: https://www.instagram.com/cybertoni.com.br/
- Portfólio externo: https://tonilimaelesbao.myportfolio.com/work

---

## 💼 WORK EXPERIENCE (no site: mais recente primeiro)

### SEEDS COMPANY — Set/2025 – presente
- Graphic Designer — Tráfego Pago & Conversão

### LOCENT TECHNOLOGY (iGaming) — Ago/2024 – Set/2025
- Senior Graphic Designer · iGaming

### FREELANCER — Fev/2018 – Set/2025
- Los Frango · Bellys Brechó · Point do Crepe · Outthe Clouds (uma linha só) ·
  Planeta Celular & Lima Imports · BBC (Boff Boy Chique) · BRDF Energia Solar ·
  Chef Ale Monteiro | APP COMERBEM LABS

---

## 🎓 COURSES AND CERTIFICATIONS (ainda NÃO exibidos no site)

- Technical Course in Marketing and Social Media
- Educational Robotics for Educators
- Drone Piloting (UAV)

---

## 🛠️ SKILLS (no site, agrupadas — SEM porcentagens)

- a. Software: Photoshop, Illustrator, Premiere Pro, After Effects, Blender
- b. Ofício: Design de Banners, Motion Graphics, Fotografia & Composição, Pilotagem de Drone (UAV)
- c. IA aplicada: Manipulação com IA, Programando com IA, Sites com IA
- d. Áreas de atuação: Identidade visual & branding, iGaming, Thumbnails, Edição de vídeo, Sites

---

## 💬 DEPOIMENTOS (todos reais — manter texto, nomes e cargos exatos)

1. Henrique Brandão — Sócio-fundador, Seeds Company (EN: Co-founder, Seeds Company)
   ⚠️ aguardando aprovação do Henrique antes do merge para produção
2. Hellen Elesbão — Sócia-fundadora, Seeds Company (EN: Co-founder, Seeds Company)
3. Ana Monteiro — CEO, Verdura Studio
4. Cibele Haddad — Diretora de Produto, Archē

---

## 🎨 IDENTIDADE VISUAL (redesign 2026)

A regra antiga "paleta/fontes travadas" foi RELAXADA no redesign, mas a identidade
continua: verde profundo + acento lima + papel creme + computador retrô 3D + intro.

### Tokens (CSS custom properties em `:root`)
| Token | Valor | Uso |
|---|---|---|
| `--paper` | `#FBF8EE` | fundo principal (creme) |
| `--paper-2` | `#F2EEDF` | fundo alternado (Sobre, Serviços) |
| `--ink` | `#0B231D` | texto principal |
| `--ink-2` | `#3F544D` | texto de apoio (sólido, sem transparência) |
| `--ink-3` | `#5B6B64` | metadados |
| `--deep` | `#06231D` | seções escuras, rodapé, botão escuro |
| `--forest` | `#0C342C` | verde escuro auxiliar |
| `--green` | `#076653` | acento verde (itálicos, números, linhas) |
| `--lime` | `#E3EF26` | acento lima — com parcimônia (CTA, "Atual", detalhes no escuro) |

- `#DFDBD2` é usado SOMENTE no fundo da intro e da moldura do vídeo do hero.
- Lima NUNCA como cor de texto sobre fundo claro (contraste insuficiente).

### Tipografia (Google Fonts)
- Display/títulos: **Fraunces** (serifa com eixo óptico; itálico leve em verde)
- Texto: **Inter**
- Metadados: **JetBrains Mono** (índices "01", datas, categorias — eco da tela
  `c:\designer\toni_lima` do computador retrô)

---

## 📐 ESTRUTURA DO SITE (ordem atual)

1. **NAV** — "Toni Lima." · links · PT / EN · "Me Contrate". Translúcida ao rolar. Mobile: menu em tela cheia verde.
2. **HERO** — "O que eu crio / fala antes de você ler." (sem efeito de digitação; as palavras
   entrega/performa/inspira/conecta viraram uma linha estática em mono), apresentação,
   "Disponível para projetos" discreto, botões Ver Projetos + WhatsApp, vídeo do computador
   retrô 3D com legenda `c:\designer\toni_lima`.
3. **01 PORTFÓLIO** — (a) 9 DESTAQUES em linhas justificadas (mesma altura por linha, largura
   proporcional ao formato real → nada é cortado); (b) ARQUIVO COMPLETO com filtros por categoria
   (contagem em cada filtro), grade em colunas, prévia de vídeo no hover, lightbox com
   setas/teclado/swipe. "Todos" mostra 16 itens intercalando categorias + botão "Ver todos (58)".
4. **02 SOBRE** — foto, textos, 2 números (8+ anos · 67 projetos), faixa tipográfica
   "Marcas com quem trabalhei" (só nomes reais, sem logos).
5. **03 HABILIDADES** — seção escura, 4 grupos.
6. **04 EXPERIÊNCIA** — linhas editoriais (data · empresa/cargo · atividades), mais recente primeiro.
7. **05 SERVIÇOS** — lista numerada 01–05; clicar pré-seleciona o serviço no formulário.
8. **06 DEPOIMENTOS** — seção escura, 4 depoimentos em 2 colunas.
9. **07 CONTATO** — canais diretos (e-mail, WhatsApp, LinkedIn, Behance, Instagram, portfólio
   externo) + formulário que ABRE O WHATSAPP com a mensagem pronta (nome, serviço, mensagem, e-mail opcional).
10. **RODAPÉ** — assinatura grande, links, copyright, voltar ao topo.

### Removido no redesign (era decoração, não informação)
Cursor customizado, barras de porcentagem, faixas "marquee" (as palavras foram para
"Áreas de atuação"), contadores animados, contadores "10 clientes" e "100% satisfação"
(removidos a pedido do dono), aurora/partículas/brilhos pulsantes, carrossel em leque,
ondas SVG, estrelas e avatares de iniciais nos depoimentos, 4 camadas de CSS com `!important`.
Não existe botão "Download CV" (o documento antigo citava, mas nunca existiu no site).

---

## ✨ MOVIMENTO (poucos e intencionais)

- Reveal sutil ao rolar (opacidade + 16px), uma vez só.
- Prévia de vídeo ao passar o mouse nas peças (só com mouse).
- Sublinhado animado na navegação e nos filtros.
- Parallax leve no computador 3D (só mouse).
- `prefers-reduced-motion`: sem reveal, sem prévias, sem loop do vídeo do hero e SEM intro.

---

## 🌐 PT/EN TRANSLATION SYSTEM

- Objeto `const t` no JS. **PT e EN completos, paridade obrigatória** (mesmas chaves).
- ES / 繁中 / 简体 continuam no dicionário mas estão OCULTOS (`LANGS_ON = ['pt','en']`)
  até a tradução completa. Para reativar: adicionar os botões no seletor e o código em `LANGS_ON`.
- Atributos: `data-i18n` (texto), `data-i18n-html`, `data-i18n-ph` (placeholder), `data-i18n-aria` (aria-label).
- Preferência salva em localStorage. Padrão: português.

---

## ⚙️ TECHNICAL REQUIREMENTS

- Arquivo único: `index.html` (CSS + JS embutidos). Vanilla JS, sem frameworks.
- Mídias do portfólio: array `MEDIA` (antigo `cfAllData`) com `src` (original, usado no
  lightbox), `thumb` (JPG leve em `thumbs/`, usado na grade e como capa do vídeo) e `w/h` reais.
- Destaques: `FEATURED_ROWS` (chaves sem o prefixo `pf.`).
- Nenhum vídeo do portfólio é baixado até o visitante passar o mouse ou abrir o lightbox.
- Capas geradas com o ffmpeg local: `F:\artes pessoais\hylo\video e projeto\tools\ffmpeg.exe`.
- Ver `INVENTARIO-IMAGENS.md` → "Como adicionar novas mídias".

---

## 📋 RULES FOR NEXT SESSIONS

1. ALWAYS read this file before any change.
2. Redesign: trabalhar SÓ no branch `redesign`; produção (`main`) só muda quando o dono disser "merge".
3. NUNCA apagar informação do site sem perguntar ao dono.
4. ALWAYS add PT and EN versions for new text.
5. NEVER create separate CSS/JS files (everything in index.html). Pastas de mídia são permitidas.
6. ALWAYS test desktop + mobile (390px), filtros, lightbox, PT/EN e 404 antes de finalizar.
7. Depoimentos são reais — manter texto, nomes e cargos exatos.

---

## 🚧 PLANNED IMPROVEMENTS

- [ ] Títulos reais nas peças (hoje muitos são genéricos: "Cassino 08", "Odontologia 02")
- [ ] Traduzir ES / 繁中 / 简体 por completo e reativar no seletor
- [ ] Recomprimir vídeos muito pesados (tour_solar_BRDF ~99 MB, Chef Ale ~85 MB cada)
- [ ] Renomear arquivos com nomes de ferramenta ("ChatGPT Image…", "Gemini_Generated…")
- [ ] Considerar exibir os cursos/certificações
- [ ] SEO: og:image dedicada (hoje usa o poster do hero), canonical

---

## 🎬 INTRO / TELA DE ABERTURA (recurso opcional e reversível)

Overlay em tela cheia que toca um vídeo ao abrir o site, começa mudo (com botão de som
PT/EN) e some com fade após ~3,3 s. O site funciona 100% com ela desligada.
Visitantes com "reduzir movimento" ativado no sistema entram direto (sem intro).

- Vídeo: `imagem inicial/Retro_computer_character after 2.mp4` (~3,2 s)
  - Poster: `imagem inicial/intro-poster.jpg`
  - No HTML os espaços viram `%20`.
- Blocos marcados em `index.html`:
  - HTML: `<!-- INTRO START -->` … `<!-- INTRO END -->` (logo após `<body>`)
  - CSS:  `/* INTRO START */` … `/* INTRO END */` (no fim do `<style>`)
  - JS:   `/* INTRO START */` … `/* INTRO END */` (no fim do `<script>`)

### Como DESLIGAR
`const INTRO_ENABLED = true;` → `false` no bloco JS da intro.

### Como REMOVER de vez
Apagar os 3 blocos entre os marcadores (e, opcionalmente, a pasta `imagem inicial/`).

### Enquadramento
`.intro-video { object-fit: contain }` → `cover` para preencher cortando as bordas.

---

## 🎥 VÍDEO 3D NO CABEÇALHO (hero)

- Vídeo: `video 3d cabeçario/video para o cabeçario.mp4` (760×600, ~19 MB) + `poster.jpg`.
- Só começa a baixar após o `load` da página e quando está visível (LCP = poster).
- Moldura `.hero-video-wrap` com `aspect-ratio: 760/600`, fundo `#DFDBD2`, `object-fit: contain`.
- Marcadores: HTML `<!-- HERO VIDEO START/END -->`, CSS e JS `/* HERO VIDEO START/END */`.
- O antigo objeto SVG decorativo saiu no redesign (continua no histórico do git, branch `main`).

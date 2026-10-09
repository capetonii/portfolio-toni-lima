# TONI LIMA PORTFOLIO — MASTER CONTEXT DOCUMENT
Version: 2.0 | Last updated: 09/10/2026 — em PRODUÇÃO (merge do branch `content-update` na `main`)

> O código (`index.html`) é a fonte da verdade. Este documento descreve o site
> como está NO AR. Backup da produção anterior: tag `backup-before-merge-2026-10-09`.

---

## 👤 PROJECT OWNER DATA

- Real name: José Antônio Lima
- Site name: TONI LIMA
- Age: 27 | Brazilian
- Profession: Senior Graphic Designer + Developer
- Email: josealima.15@gmail.com
- WhatsApp: +55 (61) 99675-3348
- Experience: 8+ years in the audiovisual industry
- Projects delivered: 67 (contador "Projetos Concluídos" e card flutuante "Projetos entregues")
- Specialties: video editing, motion graphics, visual identity, iGaming banners, thumbnails

### Links oficiais (https, nova aba, rel="noopener noreferrer")
- LinkedIn: https://www.linkedin.com/in/jos%C3%A9-ant%C3%B4nio-lima-7a75862a3 (texto exibido: linkedin.com/in/josé-antônio-lima)
- Behance: https://www.behance.net/eduardavesoarto (rodapé)
- Instagram: https://www.instagram.com/cybertoni.com.br/ (rodapé)
- Portfólio externo: https://tonilimaelesbao.myportfolio.com/work

---

## 💼 WORK EXPERIENCE (como está no site)

### SEEDS COMPANY — Set/2025 – presente (EN: Sep/2025 – Present)
- Graphic Designer — Tráfego Pago & Conversão

### LOCENT TECHNOLOGY (iGaming) — Ago/2024 – Set/2025
- Senior Graphic Designer · iGaming

### FREELANCER — Fev/2018 – Set/2025
- Los Frango · Bellys Brechó · Point do Crepe · Outthe Clouds (uma linha só, `exp.free.i4`) ·
  Planeta Celular & Lima Imports · BBC (Boff Boy Chique) · BRDF Energia Solar ·
  Chef Ale Monteiro | APP COMERBEM LABS

---

## 🎓 COURSES AND CERTIFICATIONS (ainda NÃO exibidos no site)

- Technical Course in Marketing and Social Media
- Educational Robotics for Educators
- Drone Piloting (UAV)

---

## 🛠️ TECHNICAL SKILLS (seção Habilidades — barras de porcentagem)

Photoshop, Illustrator, Premiere Pro, After Effects, Blender, Manipulação com IA,
Design de Banners, Motion Graphics, Fotografia & Composição, Pilotagem de Drone (UAV),
Programando com IA, Sites com IA.

---

## 💬 DEPOIMENTOS (todos reais — manter texto, nomes e cargos exatos)

1. Ana Monteiro — CEO, Verdura Studio
2. Hellen Elesbão — Sócia-fundadora, Seeds Company (EN: Co-founder, Seeds Company)
3. Cibele Haddad — Diretora de Produto, Archē
4. Henrique Brandão — Sócio-fundador, Seeds Company (EN: Co-founder, Seeds Company)
   ⚠️ publicado em 09/10/2026 sem confirmação registrada da aprovação do Henrique — confirmar com ele.

Layout: grid 2×2 no desktop, 1 coluna ≤900px. Cards em vidro fosco (ver estrutura).

---

## 🎨 IDENTIDADE VISUAL

Valores efetivamente aplicados (o `:root` ainda guarda `--bg/--green-dark/--green-mid`
da versão original; camadas de override no CSS definem o resultado final):

| Uso | Valor |
|---|---|
| Fundo (creme) | `#FFFDEE` |
| Texto principal | `#06231D` |
| Texto de apoio | `rgba(7,102,83,0.75)` |
| Verde escuro (sidebar, rodapé, depoimentos) | `#06231D` / `#0C342C` |
| Acento verde | `#076653` / `#52B788` |
| Acento lima | `#E3EF26` |
| Fundo da intro / moldura do vídeo do hero | `#DFDBD2` (só ali) |

Tipografia: Playfair Display (títulos) · Inter (texto). Google Fonts.

---

## 📐 ESTRUTURA DO SITE (ordem atual)

1. **SIDEBAR (desktop)** — pílula vertical flutuante à esquerda (72px, margem 16px,
   raio 24px, `#06231D`): logo "TL.", 6 ícones (Sobre, Habilidades, Portfólio,
   Experiência, Serviços, Contato) com scroll-spy em lima e tooltip PT/EN; embaixo,
   PT/EN compacto, botão redondo lima "Me Contrate" com **anel cromático girando**
   (conic-gradient ciano→magenta→amarelo→branco, 4s, pseudo-elementos; parado com
   `prefers-reduced-motion`) e avatar (`toni lima.jpeg`). O conteúdo é deslocado por
   `--sb-offset` (104px) via `body{padding-left}`.
   **Mobile (≤900px)**: barra de abas inferior com os mesmos ícones + barra fina no
   topo (logo, PT/EN, "Me Contrate"). Sem hambúrguer.
   Marcadores: CSS `/* ═══ SIDEBAR NAV START/END ═══ */`, HTML `<!-- NAV — SIDEBAR START/END -->`.
2. **HERO** — título com efeito de digitação (entrega./performa./inspira./conecta.),
   badge "Disponível para projetos", botões Ver Projetos + WhatsApp, vídeo 3D do
   computador retrô (ver seção própria).
3. **SOBRE** — foto, textos, contadores (8 anos · 67 projetos · 10 clientes · 100 %), card
   flutuante "67 Projetos entregues".
4. **HABILIDADES** — barras de porcentagem.
5. **PORTFÓLIO** — filtros em **vidro fosco** (`rgba(255,255,255,.35)`, blur 16px) com 2
   manchas desfocadas atrás (`.pf-blobs`); ativo em lima com brilho. Carrossel em leque
   (fan deck) + lightbox. Regras de dados no JS:
   - `HIDDEN_FROM_ALL = ['cassino']` → categoria fora de "Todos", da rotação, do lightbox
     em "Todos" e do contador; o botão "Cassino" mostra tudo normalmente.
   - `FEATURED_FIRST = ['pf.b6','pf.b7']` (Hylo, Poste) → em "Todos" o 1º card é um deles
     (sorteado); no filtro da categoria vêm primeiro (ordem sorteada entre eles).
   - "Todos" roda em ordem aleatória, embaralhada uma vez por carregamento.
   - Rótulo = filtro ativo + total ("Todos · 42 trabalhos" / "All Work · 42 works").
   - Campo opcional `poster:'posters/<id>.jpg'` nos vídeos (capa JPG leve).
   - Ritmo: 2000 ms parado + 800 ms de deslize (`CARD_HOLD_MS`, `CARD_TRANSITION_MS`).
   Contagem atual: 63 peças · Todos 42 · Cassino 21 · Odontologia 10 · Blender 9 ·
   Arte Pessoal 6 · Esportes 5 · UI de Sites 4 · Vídeos 3 · Lives 2 · Chef Ale 2 · Seeds 1.
   Inventário completo: `INVENTARIO-IMAGENS.md` (baseline 09/10/2026).
6. **EXPERIÊNCIA** — timeline vertical com **linha luminosa** (2px lima, brilho em 3
   camadas + sombra escura deslocada) e nós com núcleo claro, brilho e pulso lento de
   3s (desligado com `prefers-reduced-motion`). Cards verde-escuro alternados.
7. **SERVIÇOS** — lista em linhas (ícone, título, descrição, seta).
8. **DEPOIMENTOS** — fundo `#0C342C` com 3 manchas desfocadas (lima + verde) derivando
   devagar (`.tst-blobs`, sem animação com `prefers-reduced-motion`); cards em vidro
   fosco (`rgba(255,255,255,.08)`, blur 24px saturate 1.2, borda `.18`, raio 28px,
   realce interno no topo); grid 2×2.
9. **CONTATO** — canais (e-mail, WhatsApp, LinkedIn, portfólio externo) + formulário
   (⚠️ o envio é simulado: mostra "Mensagem Enviada" sem enviar nada).
10. **RODAPÉ** — logo, copyright, Behance · LinkedIn · Instagram · Portfólio ↗.

---

## 🌐 PT/EN TRANSLATION SYSTEM

- Objeto `const t` no JS. **PT e EN completos — paridade obrigatória** (mesmas chaves).
- Seletor mostra só PT / EN (sidebar e barra do topo). ES / 繁中 / 简体 continuam no
  dicionário, incompletos e sem botão.
- Atributos: `data-i18n`, `data-i18n-html`, `data-i18n-ph`. Preferência em localStorage.

---

## ⚙️ TECHNICAL REQUIREMENTS

- Arquivo único `index.html` (CSS + JS embutidos). Vanilla JS, sem frameworks.
- Mídias do carrossel: array `cfAllData` (`src` com `%20` nos espaços).
- Capas de vídeo em `posters/` (geradas com o ffmpeg local:
  `F:\artes pessoais\hylo\video e projeto\tools\ffmpeg.exe`).
- Vídeos do carrossel só baixam quando o card entra na janela visível (`fanEnsureMedia`).
- ⚠️ `blender/tour_solar_BRDF_v1_1.mp4` tem ~99 MB — o GitHub rejeita arquivos ≥ 100 MiB.

---

## 📋 RULES FOR NEXT SESSIONS

1. ALWAYS read this file before any change.
2. Trabalhar em branch novo a partir da `main`; produção só muda quando o dono disser "merge".
3. Escopo travado por tarefa: alterar SÓ os blocos pedidos e provar com diff por seção.
4. NUNCA apagar informação do site sem perguntar ao dono.
5. ALWAYS add PT and EN versions for new text.
6. NEVER create separate CSS/JS files (everything in index.html). Pastas de mídia são permitidas.
7. ALWAYS test desktop + tablet + mobile (1440/820/390), filtros, lightbox, PT/EN e 404.
8. Depoimentos são reais — manter texto, nomes e cargos exatos.
9. Branches mantidos no GitHub para histórico: `redesign` (experimento rejeitado — não usar),
   `text-fixes`, `sidebar-nav`, `ui-polish`, `content-update`.

### Rollback da produção para antes do merge de 09/10/2026
```
git checkout main
git reset --hard backup-before-merge-2026-10-09
git push --force origin main
```

---

## 🚧 PLANNED IMPROVEMENTS

- [ ] Formulário de contato: envio real (WhatsApp pré-preenchido ou Formspree)
- [ ] Títulos reais nas peças genéricas ("Cassino 09", "Sports Design 02"…)
- [ ] Traduzir ES / 繁中 / 简体 por completo e reativar no seletor
- [ ] Recomprimir vídeos muito pesados (tour_solar_BRDF ~99 MB, Chef Ale ~85 MB cada)
- [ ] Renomear arquivos com nomes de ferramenta ("ChatGPT Image…", "Gemini_Generated…")
- [ ] Scroll-spy da sidebar no celular não acende em seções muito altas (Experiência)
- [ ] Considerar exibir os cursos/certificações

---

## 🎬 INTRO / TELA DE ABERTURA (recurso opcional e reversível)

Overlay em tela cheia que toca um vídeo ao abrir o site, começa mudo (com botão de som)
e some com fade aos ~3,3 s. O site funciona 100% com ela desligada. Cobre a sidebar
(z-index 99999).

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
- `.hero-video-wrap` com `aspect-ratio: 760/600`, `object-fit: contain`.
- Marcadores: HTML `<!-- HERO VIDEO START/END -->`, CSS e JS `/* HERO VIDEO START/END */`.
- O antigo objeto SVG decorativo está comentado dentro do bloco HTML (reversível).

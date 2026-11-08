---
name: Porto Farrô
description: Cafés especiais, arte urbana e gastronomia afetiva em Porto Alegre
colors:
  primary: "#e10600"
  secondary: "#ffc7c6"
  surface-wine: "#260212"
  surface-burgundy: "#4f0423"
  neutral-dark: "#000000"
  neutral-light: "#ffffff"
  accent-green: "#25d366"
  accent-gold: "#f5b300"
typography:
  display:
    fontFamily: "'Anton', 'Barlow Condensed', Impact, sans-serif"
    fontSize: "clamp(4.25rem, 16vw, 13.75rem)"
    fontWeight: 400
    lineHeight: 0.76
    letterSpacing: "0.05em"
  headline:
    fontFamily: "'Anton', 'Barlow Condensed', Impact, sans-serif"
    fontSize: "clamp(3rem, 7vw, 5.75rem)"
    fontWeight: 400
    lineHeight: 0.8
    letterSpacing: "0.03em"
  title:
    fontFamily: "'Anton', 'Barlow Condensed', Impact, sans-serif"
    fontSize: "clamp(2rem, 4.5vw, 2.875rem)"
    fontWeight: 400
    lineHeight: 0.95
    letterSpacing: "0em"
  body:
    fontFamily: "'Barlow Condensed', ui-sans-serif, system-ui, -apple-system, sans-serif"
    fontSize: "1.125rem"
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: "0.02em"
  label:
    fontFamily: "'Barlow Condensed', ui-sans-serif, system-ui, -apple-system, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "0.03em"
rounded:
  sm: "10px"
  md: "12px"
  btn: "15px"
  pill: "20px"
  feature: "38px"
  full: "9999px"
spacing:
  xs: "8px"
  sm: "12px"
  md: "16px"
  lg: "24px"
  xl: "36px"
  2xl: "48px"
  section: "72px"
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral-light}"
    rounded: "{rounded.btn}"
    padding: "10px 18px"
  button-primary-hover:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.surface-wine}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.neutral-light}"
    rounded: "{rounded.btn}"
    padding: "10px 18px"
  button-whatsapp:
    backgroundColor: "{colors.accent-green}"
    textColor: "{colors.neutral-dark}"
    rounded: "{rounded.btn}"
    padding: "10px 18px"
  card-default:
    backgroundColor: "{colors.surface-burgundy}"
    textColor: "{colors.neutral-light}"
    rounded: "{rounded.md}"
    padding: "26px"
  card-feature:
    backgroundColor: "{colors.surface-burgundy}"
    textColor: "{colors.neutral-light}"
    rounded: "{rounded.feature}"
    padding: "36px"
---

# Design System: Porto Farrô

## Overview

**Creative North Star: "O Pavilhão Urbano do Café" (The Urban Coffee Pavilion)**

O sistema visual do Porto Farrô traduz a pulsação cultural de Porto Alegre e o convívio em torno do Parque Farroupilha (Redenção). Trata-se de um design de atitude urbana e estética industrial acolhedora, onde murais expressivos de arte urbana dialogam com a precisão artesanal de microlotes de café especial e uma hospitalidade gaúcha vibrante.

O ambiente gráfico apoia-se em superfícies densas e profundas em tons de vinho e borgonha, contrastadas pelo calor imediato do Vermelho Farrô e pela delicadeza iluminada do Rosa Blush. A composição transmite a sensação física de estar dentro do pavilhão: tetos altos, paredes grafitadas, aroma de espresso fresco e mesas comunitárias cheias de vida.

O sistema rejeita conscientemente o minimalismo frio e asséptico das cafeterias corporativas genéricas em tons de cinza e branco, bem como os clichês bucólicos de fazenda colonial. Aqui a presença é contemporânea, cultural e assumidamente urbana.

**Key Characteristics:**
- Fundo cromático imersivo em camadas tonais de vinho café profundo e caixas borgonha.
- Tipografia de manchete monumental e ultra-condensada em caixa alta.
- Contraste afiado e deliberado entre vermelho elétrico e rosa blush suave.
- Geometria calculada combinando cantos funcionais (12px/15px) com raios arquitetônicos generosos (38px).
- Elementos táteis interativos com resposta imediata e micro-interações expressivas.

## Colors

A paleta fundamenta-se na riqueza sensorial do grão torrado e na intensidade dos pigmentos de arte de rua, equilibrando gravidade e energia.

### Primary
- **Vermelho Farrô** (`#e10600`): O pulso de energia do sistema. Utilizado para direcionar o olhar do visitante aos botões de ação prioritários (CTAs), manchetes de grande escala, monogramas de logotipo e selos de validação.

### Secondary
- **Rosa Blush Aveludado** (`#ffc7c6`): O contraponto doce e iluminado. Empregado em subtítulos, linhas de apoio, contornos de badges e estados de hover dos botões principais, garantindo legibilidade perfeita sobre fundos escuros.

### Neutral
- **Vinho Café Profundo** (`#260212`): A base tonal primária do canvas. Um matiz quase negro enriquecido pela densidade do café extraído e do vinho tinto, acolhendo todo o conteúdo do site sem recorrer ao preto digital desbotado.
- **Borgonha Quente** (`#4f0423`): Superfície de cartões, caixas de receitas e blocos de conteúdo. Estabelece a primeira camada de elevação dimensional sobre o fundo vinho.
- **Preto Noite** (`#000000`): Reservado para a barra de navegação superior, rodapé e contornos divisórios nítidos de 1px.
- **Branco Puro** (`#ffffff`): Texto de alta prioridade, títulos de itens de cardápio e citações de clientes.

### Named Rules
**The Rarity of Red Rule.** O Vermelho Farrô (`#e10600`) é a voz mais alta da página; por isso, nunca deve ocupar mais de 15% da área visual de uma tela. Seu poder reside no isolamento e na precisão de foco.
**The Tonal Canvas Rule.** Telas e seções nunca usam cinza ou branco para preenchimento de fundo. O universo é integralmente noturno, quente e construído sobre a sobreposição de `#260212` e `#4f0423`.

## Typography

**Display Font:** Anton (fallback Impact, 'Barlow Condensed', sans-serif)  
**Body Font:** Barlow Condensed (fallback ui-sans-serif, system-ui, -apple-system, sans-serif)  
**Label/Button Font:** Barlow Condensed (peso 600, caixa alta)

**Character:** Uma combinação marcante de cartaz urbano europeu com a agilidade compacta de embalagens editoriais. O peso maciço e monolítico de Anton ancora o impacto imediato, enquanto a flexibilidade condensada de Barlow acomoda descrições de grãos e métodos com alta densidade de leitura sem poluição.

### Hierarchy
- **Display** (Anton, 400, `clamp(68px, 16vw, 220px)`, line-height 0.76, letter-spacing 0.05em): Manchete principal da hero e nomes de impacto monumental. Sempre em CAIXA ALTA.
- **Headline** (Anton, 400, `clamp(48px, 7vw, 92px)`, line-height 0.8, letter-spacing 0.03em): Títulos de seções primárias (`#recipes`, `#mission`, `#reviews`, `#hours`). Sempre em CAIXA ALTA.
- **Title** (Anton, 400, `clamp(32px, 4.5vw, 46px)`, line-height 0.95): Títulos secundários de impacto e chamadas de blocos destacados. Sempre em CAIXA ALTA.
- **Body** (Barlow Condensed, 400/500, 18px, line-height 1.4, letter-spacing 0.02em): Parágrafos descritivos, depoimentos e narrativas institucionais. Limite visual recomendado de 60-68 caracteres por linha.
- **Label / Micro-copy** (Barlow Condensed, 600/700, 13px a 15px, letter-spacing 0.03em a 0.08em): Eyebrows de seção, botões de ação, badges e filtros de cardápio.

### Named Rules
**The Monolithic Header Rule.** Títulos em Anton operam com entrelinha ultra-curta (0.76 a 0.95) e caixa alta obrigatória. O objetivo é que as palavras formem blocos arquitetônicos coesos, como letras pintadas em murais urbanos.

## Layout

O espaço visual organiza-se através de um grid container de largura máxima de 1280px centralizado com margens internas de 24px nas bordas.

- **Ritmo Vertical:** Seções alternam respiro generoso com espaçamento padronizado de 72px (`padding: 72px 0`).
- **Composição em Grade:**
  - Grade de especialidades/cardápio: 4 colunas em desktop (min-width 961px) com gap de 16px.
  - Ajuste intermediário (tablets até 960px): transiciona para 2 colunas com gap de 24px.
  - Mobile compacto (até 520px): colapsa em coluna única fluida (1fr).
- **Trilho de Carrossel:** As linhas de produtos operam em container horizontal rolável com encaixe suave (`scroll-snap-type: x mandatory`), cartões flexíveis com largura mínima de `min(420px, 85vw)` e scrollbar oculta.

## Elevation & Depth

O sistema rejeita sombras difusas padrão em prol de **camadas tonais sobrepostas (Tonal Layering)**. A sensação de profundidade decorre do contraste luminoso entre a lona de fundo e as placas de conteúdo.

### Shadow Vocabulary
- **Flat at Rest:** Cartões de produtos, grades e caixas institucionais não possuem sombra em repouso. A separação é feita pela cor de fundo Borgonha (`#4f0423`) delimitada por borda sólida de 1px (`#000000` ou `rgba(255,199,198,0.15)`).
- **Hover Lift:** Em interação do mouse, cartões realizam leve elevação física via `transform: translateY(-3px)` com transição suave de 0.2s.
- **Suspended Widget Shadow** (`box-shadow: 0 12px 36px rgba(0,0,0,0.6)`): Reservada exclusivamente para a janela interativa do Google Maps para destacar sua profundidade e recorte fotográfico.
- **Floating Badge Glow** (`box-shadow: 0 8px 24px rgba(225,6,0,0.5)`): Sombra difusa colorida aplicada unicamente ao pin de localização pulsante.

### Named Rules
**The Tonal Depth Rule.** A interface ganha profundidade por luz e cor, não por sombras cinzas artificiais. Cartões descansam planos sobre o canvas; sombras existem apenas para simular janelas suspensas (como o mapa) ou emanação de luz (como o pin).

## Shapes

O sistema adota uma gramática geométrica deliberada de **raio duplo contextual**:

- **Bordas Operacionais (12px / 15px):** Elementos de interação rápida — cartões de pratos na grade (`12px`), botões de ação e campos de entrada (`15px`) — recebem cantos moderadamente suavizados que transmitem firmeza e agilidade.
- **Bordas Arquitetônicas / Feature (38px):** Grandes blocos narrativos e contêineres de destaque (Quadro de Reputação, Tabela Semanal de Horários, Moldura do Google Maps) utilizam o raio de 38px, remetendo aos arcos e recortes industriais do galpão físico.
- **Cápsulas e Pílulas (20px / 30px / 9999px):** Filtros de categorias e badges de avaliação operam em formato pílula totalmente arredondado.

## Components

### Buttons
- **Shape:** Borda arredondada suave (15px), caixa alta, peso 600, letter-spacing 0.03em.
- **Primary:** Fundo Vermelho Farrô (`#e10600`), borda de 1px correspondente, texto branco, padding `10px 18px`.
  - *Hover:* Inversão elegante para fundo Rosa Blush (`#ffc7c6`) com texto Vinho (`#260212`).
- **Ghost:** Fundo transparente, borda de 1px branca, texto branco. Hover com fundo Blush e texto Vinho.
- **WhatsApp:** Fundo oficial `#25D366`, sem borda, texto preto puro `#000000` em peso 700. Hover com tom levemente escurecido `#1ebb5b`.

### Chips & Pills
- **Filtros de Cardápio:** Pílulas de padding `9px 18px`, raio de 15px, borda de 1px Borgonha, tipografia Blush em caixa alta.
  - *Ativo (`aria-pressed=true`):* Fundo preenchido em Vermelho Farrô (`#e10600`) com texto branco puro.
- **Badge de Prova Social:** Cápsula semi-translúcida `rgba(225,6,0,0.15)` com borda vermelha fina, estrelas douradas (`#f5b300`) e texto branco.

### Cards / Containers
- **Card Padrão de Produto:** Fundo Borgonha (`#4f0423`), borda de 1px preta, raio de 12px, padding interno de 26px. Imagem interna com `aspect-ratio: 1.2` e zoom suave no hover (`scale(1.05)`).
- **Feature Box (Reputação / Horários):** Fundo translúcido `rgba(38,2,18,0.75)` com borda fina borgonha, raio de 38px e padding de 36px a 40px.

### Navigation
- Barra sticky de 64px no topo, fundo preto sólido (`#000000`), alinhamento horizontal com distribuição entre logotipo, links centrais em caixa alta com micro-setas e botões de ação rápida à direita (WhatsApp e Como Chegar).

### Signature Component: Google Maps Embed Hub
- Iframe interativo oficial do Google Maps integrado diretamente ao contêiner de raio feature (38px) com borda suave, centralizado na localização real do Porto Farrô (Av. Venâncio Aires, 1031), permitindo zoom, navegação tátil e visualização de rotas em tempo real.

### Signature Component: Monumental Bottom Banner (Estilo Impossible Foods)
- Banner final abaixo do rodapé com tipografia monumental condensada (`PORTO FARRÔ`) em Vermelho Farrô (`#e10600`) preenchendo o campo visual sobre fundo escuro (#1a020c).
- Sobreposição centralizada da xícara de café latte art recortada, ancorada na base com sombra de profundidade (`drop-shadow(0 20px 45px rgba(0,0,0,.88))`) e elevação suave ao hover (`translateY(-14px) scale(1.04)`). Em dispositivos móveis (≤768px/480px/360px), a xícara escala proporcionalmente (130px → 92px → 80px) ancorada à base inferior, garantindo que a tipografia permaneça amplamente visível e legível sem ser obstruída.
- Menção legal de copyright em Rosa Blush no canto inferior esquerdo com tipografia legível e contraste validado.

## Do's and Don'ts

### Do:
- **Do** manter a hierarquia de fundo escuro: vinho café (#260212) na base e borgonha (#4f0423) nos cards.
- **Do** manter todos os títulos principais e de seções em Anton e em CAIXA ALTA rigorosa com entrelinha densa (≤0.95).
- **Do** reservar o raio de 38px apenas para grandes contêineres de destaque e usar 12px/15px para componentes cotidianos.
- **Do** vincular todos os pontos de contato aos canais reais confirmados: WhatsApp oficial e rota no Google Maps.
- **Do** respeitar as diretrizes de movimento reduzido (`prefers-reduced-motion: reduce`) preservando a integridade visual sem animações que causem desconforto.

### Don't:
- **Don't** aplicar fundos brancos genéricos ou estética estéril e desprovida de cor de cafeterias convencionais.
- **Don't** utilizar clichês rústicos ou motivos campestres de fazenda — a proposta é industrial, artística e urbana.
- **Don't** espalhar o Vermelho Farrô indiscriminadamente; ele perde força se cobrir grandes planos de fundo de seções inteiras.
- **Don't** inventar sombras difusas arbitrárias em cartões comuns; a interface é plana por padrão com camadas tonais.
- **Don't** substituir ou alterar os dados reais de prova social (4.7★, 730+ avaliações no Google).


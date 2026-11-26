# Manual Operacional: Passo a Passo Para Produzir Cada Previsão Diária (YouTube Shorts + TikTok + Facebook Reels)

Guia prático clique por clique para produzir o **Vídeo Diário #01** em ~45 minutos (criando o molde definitivo no CapCut) e os próximos em **15 a 25 minutos cada**, com **custo zero** e qualidade de estúdio.

---

## PASSO 1 — Pasta de Produção Local (Fora do Git)

Crie uma pasta dedicada fora do repositório Git, em `D:\producao_rose_grimoire\`, contendo:
- `biblioteca_fixa/` → artes de `D:\therosegrimoire\assets\`, trilha neoclássica/mística da Biblioteca de Áudio do YouTube e SFX padrão (carta batendo na mesa, página virando, sino sutil)
- `short_01/` (e `02/`, `03/`...):
  - `01_audio/` → voz gerada no Gemini TTS (`voz_pt.wav`, e depois `voz_es.wav` / `voz_en.wav`)
  - `02_visuais/` → imagens da carta de Tarot / Baralho Cigano do dia, glifo/mapa celeste e 3–5 B-rolls verticais do Pexels
  - `03_export/` → `.mp4` final sem marca d'água para subir nas 3 redes!

---

## PASSO 2 — Gerar a Voz Oficial no Google AI Studio (Gemini TTS — Custo Zero)

1. Acesse **`aistudio.google.com`** → **Generate Media → Speech / Gemini TTS** (**Gemini Flash TTS**, modo *Single-speaker*).
2. Copie o **Prompt de Direção Vocal** oficial de [`docs/biblia_da_persona.md`](./biblia_da_persona.md) no campo *Style instructions*.
3. Cole apenas o **Texto Limpo** do roteiro no campo de texto.
4. **No Short #01 (uma única vez):** Teste 2–3 vozes femininas de timbre grave-médio, firme e elegante (nunca aguda nem infantil). Escolha a que melhor traduz a **Guerreira Aristocrata** e anote o nome exato dela em `docs/biblia_da_persona.md` — ela será para sempre a voz oficial de **`The Rose Grimoire`**.
5. Ouça com fone de ouvido (verifique dicção de signos, termos astrológicos e duração entre `1min35s` e `1min55s` — teto de 2 minutos) e baixe o `.wav` em `01_audio/`.

---

## PASSO 3 — Montar o Molde 9:16 no CapCut PC (1 Edição = 3 Redes)

1. Novo Projeto → Proporção **`9:16`** (`1080 × 1920`) → Fundo sólido **`#1E1815`** (Nogueira Aristocrática).
2. **Áudio cirúrgico:**
   - Voz: **`0 dB`** (normalizada); corte qualquer silêncio morto em `0:00` e exatamente na última sílaba do loop; preserve micro-pausas de `0,3s` antes das frases de corte.
   - Música (violoncelo/cordas/cravo suave ou dark-warm ambient da Biblioteca do YouTube): **`-24 dB` a `-28 dB`**.
   - SFX (carta na mesa, virar de página): **`-12 dB` a `-16 dB`**.
3. **Visual (Regra dos 2–4 Segundos — Estética Luminosa e Nobre):**
   - **Frame #01 (0:00–0:03):** Retrato dela (`avatar_the_rose_grimoire_1024x1024.png` ou cena do gabinete iluminado) com zoom suave (*Ken Burns* `105% → 118%`) + Headline curta em `Cinzel` ou `Montserrat ExtraBold` cor **`#CFA65B`** (Ouro Latão) com sombra `#1E1815`.
   - **Cartas e Astros:** Mostrar a Carta de Tarot / Baralho Cigano do dia com moldura dourada fina `#CFA65B` e movimento suave.
   - **Fechamento (últimos 4s):** Inserir `emblema_the_rose_grimoire_1024x1024.png` com baixa opacidade/brilho quente antes de emendar o loop no frame `0:00`.
4. **Legendas Cinéticas (Zona Segura Universal — YouTube Shorts + TikTok + Facebook Reels):**
   - Fonte: `Montserrat ExtraBold`, MAIÚSCULAS, cor base **`#F2E9D8`** (Pergaminho Marfim) + traço `#1E1815` (espessura ~12).
   - Destacar palavras de impacto em **`#CFA65B`** (Ouro — prosperidade/poder/astros) e **`#8C3343`** (Rosa Veludo — cortes/alertas/amor).
   - Posicionar no **centro-baixo seguro** (deixar `28%` livres embaixo e `20%` livres na direita para nunca colidir com os botões do TikTok, YouTube Shorts ou Facebook Reels!).
5. **Exportar:** `1080p`, `60fps`, `MP4 (H.264)` — **sem marca d'água**.
6. **Duplicar o projeto** no CapCut como `MOLDE_THE_ROSE_GRIMOIRE_9X16` para produzir os próximos dias em 15 minutos!

---

## PASSO 4 — Publicação Tripla (5 Minutos por Dia)

1. **YouTube Shorts:** Suba o `.mp4` limpo, preencha Título + Descrição SEO, conecte o **Vídeo Relacionado** ao Vídeo Longo da semana e fixe o comentário provocativo na voz dela.
2. **TikTok:** Suba o **mesmo `.mp4` limpo** (nunca baixe de uma rede com marca d'água para subir na outra!), use a legenda curta com 4–5 hashtags direcionadas (`#astrologia #tarot #baralhocigano #previsaododia #therosegrimoire`).
3. **Facebook Reels:** Suba o **mesmo `.mp4` limpo** na Página oficial de **`The Rose Grimoire`** com texto acolhedor + convite para salvar e comentar o signo/energia do dia.

---

## PASSO 5 — Padrão Oficial de Estúdio Automatizado v3 (VALIDADO & TRAVADO em 26/11/2026)

Em vez de editar do zero no CapCut, o estúdio local em `D:\producao_rose_grimoire\` já tem pipeline cinematográfico próprio em Python + FFmpeg (`compose_audio_v3_cosmos.py` + `render_teste_piloto_v2.py`) aprovado no Mini-Piloto v3:

1. **Voz Oficial (`gemini-3.8-flash-tts`):** **`Aoede`**, sempre higienizada automaticamente com `faster-whisper` (para remover qualquer leitura acidental de instruções) e alinhada palavra por palavra em JSON (`aligned_*.json`).
2. **Dramaturgia Obrigatória:** **Modo Consulta Particular** — Dona Rosa sentada à mesa falando olho no olho com o espectador como seu **consulente** (zero palestra/aula impessoal; 100% Astrologia Tradicional dos 7 Astros + vitrine plural blindada).
3. **Trilha Sonora Oficial (100% Autoral, 0% Copyright / Content ID):** **Suíte Cósmica *Strobe (Deadmau5) × Interstellar (Hans Zimmer)*** (`48 kHz Estéreo` — arpejo hipnótico de piano abafado em relógio cósmico + *plucks* analógicos quentes com delay *ping-pong* estéreo + órgão de tubos crescendo nas viradas de ato + reverb de catedral + sino de bronze europeu sincronizado à vinheta).
4. **Mixagem Travada (Ponto Doce Aprovado):**
   - Voz da **`Aoede`** centralizada em **`~ -14,0 dBFS RMS`**;
   - Trilha Cósmica Estéreo em **`~ -26,7 dBFS RMS`** (**gap de `12,5–13,5 dB`** abaixo da voz);
   - EQ de bolso vocal (`-4,5 dB` suave em `2,25 kHz`) + *mid-side ducking* aveludado (recua no centro durante a fala e respira para cima nas pausas dramáticas).
5. **Direção Visual Dinâmica (`16:9` e `9:16` nativos com hash distinto para blindagem TikTok):**
   - Cortes cinematográficos rápidos (`~3–4s` por batida visual) entre cenas limpas sem texto/sem crânios, com transições de clarão dourado de vela, respiração suave de câmera, luz volumétrica e partículas em 2 camadas de *parallax*;
   - **`16:9` (Vídeo Médio `~10 min`, estreia `19:45 BRT` D-1):** Fólio Dourado com **Astrolábio Monumental Vivo** (12 casas romanas + 7 Astros + feixes de aspecto desenhando-se ao vivo), **Relógio Celeste do Dia (`00h–24h`)**, **Live Voice Waveform**, citações editoriais e **Vinheta Animada Lower-Third** (`Curtir` + `Inscrever-se → Inscrito • Ativo` + Sino dourado balançando + `Salve & Compartilhe`);
   - **`9:16` (Shorts até `2 min`, TikTok 15 min antes de YT/FB):** Legendas cinéticas com *spring-pop* + *glow* real (sem tarja cinza quadrada), **Live Voice Waveform** acima da legenda e selo CTA com sino na zona segura inferior.

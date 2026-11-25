# The Rose Grimoire

> *"Os astros marcam a maré. As cartas mostram o fio oculto. Mas quem segura o leme — ou corta as correntes — é você."*

Repositório central de arquitetura intelectual, identidade de marca, engenharia vocal, pesquisa histórica e espiritual, metodologia oracular diária, calendário editorial, artes de vitrine e roteiros do projeto multiplataforma **The Rose Grimoire** (**YouTube**, **TikTok** e **Facebook**).

> **Marca, Pluralidade & Idiomas (Ordem de Expansão):** O projeto opera sob a marca global unificada **`The Rose Grimoire`** (`@therosegrimoire`), em homenagem íntima (*sub rosa*) à **Dona Rosa Caveira** — porém com **vitrine pública 100% plural, erudita, luminosa e acolhedora** (estética *Warm Heritage Esoteric* / Biblioteca Aristocrática Ibérica Iluminada), sem estética de horror nem fechamento sectário. O idioma **inicial/primário é Português do Brasil (`pt-br/`)**, seguido imediatamente por **Espanhol (`es/`)**, depois **Inglês (`en/`)** e, no futuro, **Francês (`fr/`)**.

---

## 1. O Que É Este Projeto

**The Rose Grimoire** é um ecossistema de mídia digital (formato **canal dark / faceless** com identidade visual autoral fixa no **YouTube**, **TikTok** e **Facebook**, operando com **previsões diárias** em vídeo curto + **leituras completas e dossiês profundos semanais**) dedicado a unir:

1. **Previsões Diárias e Semanais Reais (Zero Horóscopo Genérico):**
   - **Astrologia Real** (efemérides astronômicas exatas do dia, Lua, aspectos planetários e astrologia tradicional/mundial) cruzada com **Tarot** e **Baralho Cigano (Petit Lenormand)**;
   - Aplicadas diretamente aos campos reais da vida: **Política & Mundo**, **Finanças & Prosperidade**, **Amor & Vínculos**, **Família & Casa** e **Saúde & Energia**.
2. **Dossiês Profundos de Sabedoria Antiga & Magia Histórica:**
   - **Feitiçaria Ibérica Ancestral** (ervas, pedras, tradições populares de Portugal, Galiza e Espanha), **Magia Cerimonial e Grimorial** (*Picatrix*, *Lapidario* de Afonso X, *Clavícula de Salomão*, *Livro de São Cipriano*, horas planetárias), **Cabala**, **História das Mulheres Eruditas e Rebeldes** e **Espiritualidade Prática Plural**.
3. **Uma Persona Inconfundível no Microfone (A Guerreira Aristocrata):**
   - Inspirada *sub rosa* na visão pessoal da **Dona Rosa Caveira**: uma aristocrata polímata de ascendência ibérica/espanhola (1500–1716), aventureira da magia natural e grimorial, versada em ciência, astronomia, ervas, pedras, tarot, cabala e filosofia, de **ideais políticos fortíssimos**, **personalidade que "bate o pau na mesa"**, próspera, libertária (que libertava escravizados às escondidas em canoas à noite) e iniciada nas práticas magistas do Congo/Quimbanda por **Tata Caveira** — reverberando o arquétipo primordial de **Qalmana / Calmana** (*Witch-Mother*).

---

## 2. Mapa Completo do Repositório

```text
therosegrimoire/
├── README.md                                  # Este guia mestre (visão geral, arquitetura e retomada)
├── .gitignore                                 # Ignora mídias pesadas (.mp4, .wav, .mp3, projetos de edição)
├── docs/
│   ├── status_e_roadmap.md                    # Registro de decisões, status atual e plano passo a passo
│   ├── biblia_da_persona.md                   # Bíblia definitiva da voz (3 camadas + prompts TTS PT/ES/EN)
│   ├── manual_forense_de_discurso.md          # Engenharia frasal, léxico plural/quimbandeiro/ibérico e anti-clichês
│   ├── identidade_visual_e_canais.md          # Paleta calibrada, tipografia, specs de artes e Bios (YT/TT/FB — PT/ES/EN)
│   ├── metodo_oracular_diario.md              # Motor de previsões diárias (Astrologia + Tarot + Cigano + 5 Campos)
│   ├── estrategia_trilingue_e_crescimento.md  # Playbook 2025–2026 (YT/TT/FB, Nicho em T, PT/ES/EN e Blindagem YPP)
│   ├── passo_a_passo_producao.md              # Manual clique por clique (Gemini TTS → CapCut → YT/TikTok/FB)
│   ├── calendario_editorial_mes1.md           # Grade completa do Mês 1 (28 Curtos Diários + 8 Vídeos Longos)
│   ├── pesquisa_rosa_caveira.md               # Dossiê completo (Quimbanda → Umbanda → Candomblé → Demais Cultos)
│   └── tratado_historico_cientifico.md        # Pesquisa acadêmica (Santo Ofício, Arqueologia Congo/BR, Filologia, 14 Mulheres)
├── templates/
│   ├── template_short_diario.md               # Molde de Previsão Diária (45–60s — Shorts, TikTok e Reels)
│   ├── template_longo_previsao.md             # Molde de Vídeo Longo (Previsão Semanal/Mensal pelos 5 Campos)
│   └── template_longo_dossie.md               # Molde de Vídeo Longo (Feitiçaria Ibérica, Grimórios, Ervas, Pedras & Oráculos)
├── pt-br/
│   ├── shorts/                                # Roteiros diários em Português do Brasil (principal)
│   └── longos/                                # Leituras completas e dossiês em PT-BR
├── es/
│   ├── shorts/                                # Guiones diarios en Español
│   └── longos/                                # Lecturas completas y dossiers en Español
├── en/
│   ├── shorts/                                # Daily forecast scripts in English (Onda 2)
│   └── longos/                                # Deep-dive readings & dossiers in English (Onda 2)
├── fr/
│   ├── shorts/                                # Prévisions quotidiennes en Français (Onda 3)
│   └── longos/                                # Tirages complets et dossiers en Français (Onda 3)
└── assets/
    ├── avatar_the_rose_grimoire_1024x1024.png    # Avatar oficial (estudando c/ cigarrilha, taça de vinho e rosa)
    ├── avatar_alternativo_sem_fumo_1024x1024.png # Avatar alternativo sem cigarrilha (backup p/ filtros TikTok)
    ├── banner_youtube_2560x1440.jpg              # Banner YouTube (área segura mobile 1546x423 validada, <6MB)
    ├── capa_facebook_1640x624.png                # Capa Página Facebook (canto inf. esq. livre)
    ├── watermark_rose_150x150.png                # Marca-d'água YouTube PNG transparente
    ├── emblema_the_rose_grimoire_1024x1024.png   # Emblema oficial em alta resolução
    ├── arte_biblioteca_thumbnail_1920x1080.png   # Arte 16:9 de gabinete p/ vídeos longos e thumbnails
    └── referencias/                              # As 4 imagens originais de referência da persona
```

---

## 3. Guia Rápido de Leitura

- **Vai configurar os canais (YouTube, TikTok e Facebook)?** Leia [`docs/identidade_visual_e_canais.md`](./docs/identidade_visual_e_canais.md) — todas as bios (PT-BR, ES e EN) e especificações das artes em `assets/` estão prontas.
- **Vai escrever um roteiro diário ou vídeo longo?** Consulte [`docs/biblia_da_persona.md`](./docs/biblia_da_persona.md), [`docs/manual_forense_de_discurso.md`](./docs/manual_forense_de_discurso.md) e [`docs/metodo_oracular_diario.md`](./docs/metodo_oracular_diario.md), utilizando os moldes de [`templates/`](./templates/).
- **Vai produzir um dossiê histórico ou mágico com lastro acadêmico?** Use [`docs/tratado_historico_cientifico.md`](./docs/tratado_historico_cientifico.md) e [`docs/pesquisa_rosa_caveira.md`](./docs/pesquisa_rosa_caveira.md).
- **Quer ver o status exato e o próximo passo?** Consulte [`docs/status_e_roadmap.md`](./docs/status_e_roadmap.md).

---

## 4. Esteira de Produção (Custo Zero)

| Etapa | Ferramenta / Método |
| :--- | :--- |
| **Efemérides, Pesquisa & Roteiros** | Efemérides astronômicas reais + Tiragem estruturada (Tarot / Baralho Cigano) + Repositório Git |
| **Narração (Voz Neural Comercial Gratuita)** | **Google AI Studio (Gemini TTS)** com direção vocal PT-BR / ES / EN *(principal)* ou **Kokoro-82M** local *(Apache 2.0)* |
| **Visuais & Cartas** | Ilustrações autorais consistentes da personagem, cartas de Tarot/Lenormand, mapas celestes, B-roll Pexels/Pixabay |
| **Edição Multiplataforma** | **CapCut PC** (1 molde 9:16 reutilizado em YouTube Shorts + TikTok + Facebook Reels) e **CapCut/DaVinci** (16:9 longos) |
| **Áudio & Thumbnails** | **Biblioteca de Áudio do YouTube Studio** (zero copyright) + **Canva / Photopea** |

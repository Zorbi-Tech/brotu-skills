<div align="center">

[![Instagram](https://img.shields.io/badge/@brotu.app-E4405F?style=flat&logo=instagram&logoColor=white)](https://www.instagram.com/brotu.app/) [![TikTok](https://img.shields.io/badge/@brotu.app-000000?style=flat&logo=tiktok&logoColor=white)](https://www.tiktok.com/@brotu.app) [![X](https://img.shields.io/badge/@brotuApp-000000?style=flat&logo=x&logoColor=white)](https://x.com/brotuApp) [![LinkedIn](https://img.shields.io/badge/brotuapp-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/brotuapp)

<br />

<img src="./header.webp" width="680" alt="Brotu — Crie conteúdo com IA" />

<br />

# Brotu Skills

**[🌐 brotu.app](https://www.brotu.app)** — Crie conteúdo com IA em minutos

</div>

---

Brotu é uma plataforma de criação de conteúdo com IA para criadores e marcas. Com fluxos visuais intuitivos, você conecta modelos de imagem, vídeo e texto, como Chat-gpt-imagen, Flux 2, Sora, Wan 2.6, **Nano Banana** (pro & 2), para automatizar campanhas completas sem escrever uma linha de código. De imagens de produto a vídeos para redes sociais, tudo em um único fluxo.

Este repositório contém Claude Code skills que replicam os fluxos internos da Brotu, incluindo o sistema de otimização de prompts usado em produção.

---

## Skills disponíveis

### `optimize-prompt`

Otimiza prompts brutos para modelos de geração de imagem e vídeo usando o sistema de três camadas do Brotu:

- **Tier 1** — Reescrita visual completa: sujeito, ambiente, composição, iluminação, paleta, mood
- **Tier 2** — Detecção de estilo + sufixo de qualidade (thumbnail, photo, 3D, UGC, cinematic...)
- **Tier 3** — Formatação específica por modelo (Nano Banana · Nano Banana 2 · Nano Banana Pro · Flux 2 · Midjourney · DALL-E · Sora · Veo · Wan · Runway · Stable Diffusion...)

Suporta imagens de referência, preservação de identidade visual e copy de marketing com tom configurável.

---

## Como usar

Adicione as skills ao seu projeto Claude Code:

```bash
cp -r skills/ /seu-projeto/.claude/skills/
```

Ou referencie em seu `CLAUDE.md`:

```markdown
## Skills

- optimize-prompt: [caminho]/skills/optimize-prompt.md
```

Então invoque com `/optimize-prompt` no Claude Code.

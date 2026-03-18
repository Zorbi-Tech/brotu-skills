# Brotu Skills

Claude Code skills que replicam os fluxos internos da plataforma Brotu.

## Skills disponíveis

### `optimize-prompt`

Otimiza prompts brutos para modelos de geração de imagem e vídeo usando o sistema de três camadas do Brotu:

- **Tier 1** — Reescrita visual completa: sujeito, ambiente, composição, iluminação, paleta, mood
- **Tier 2** — Detecção de estilo + sufixo de qualidade (thumbnail, photo, 3D, UGC, cinematic...)
- **Tier 3** — Formatação específica por modelo (Flux 2, Midjourney, DALL-E, Sora, Veo, Wan, Runway, Stable Diffusion...)

Suporta imagens de referência, preservação de identidade visual, e copy de marketing com tom configurável.

## Como usar

Adicione as skills ao seu projeto Claude Code:

```bash
# Copie a pasta skills/ para seu projeto
cp -r skills/ /seu-projeto/.claude/skills/
```

Ou referencie diretamente em seu `CLAUDE.md`:

```markdown
## Skills
- optimize-prompt: [caminho]/skills/optimize-prompt.md
```

Então invoque com `/optimize-prompt` no Claude Code.

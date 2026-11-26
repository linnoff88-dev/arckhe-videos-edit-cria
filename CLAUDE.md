# CLAUDE.md — videos-edit-cria

A skill **Forja Reel** (Claude Code) — meta-skill que gera seu editor de reels.
Ver [[videos-edit-curso]] pro curso completo em 4 trilhas (repo irmêo, separado
deste em 2026-07-17 — antes eram um único repo `videos-edit`).

## Git / autor

Este repo vive na conta GitHub **`linnoff88-dev`**.

- `git config` (local) = `linnoff88-dev <linnoff88-dev@gmail.com>`.
- Remote: `git@github.com:linnoff88-dev/videos-edit-cria.git`.
- Renomeado de `linnoff88-dev/videos-edit` (era um repo só, misturando skill + curso)
  — a URL antiga `linnoff88-dev/videos-edit` redireciona automaticamente pro nome
  novo no GitHub, mas o remote local já foi atualizado.

## Estrutura

- `download/forja-reel.skill` — arquivo pronto pra instalar no Claude Code.
- `doc/` — **gitignored**, materiais de referência nêo publicáveis (originais
  em espanhol, arquivos com autoria) — nunca commitar.
- `guia/index.html` — landing + guia de uso (`projetos-landing-guia`), publicado
  em `https://linnoff88-dev.github.io/arckhe-/guia/`.
- `capa/capa.png` — capa oficial do catálogo (convençêo `<url>/capa/capa.png`).

## Deploy = sempre via git

Publicar = `commit + push` no `origin`. GitHub Pages via Actions
(`build_type=workflow`, nêo legacy). Deploy automático — nêo cutucar
dashboard/status.

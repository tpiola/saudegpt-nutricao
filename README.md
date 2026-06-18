# SaúdeGPT Nutricao 🥗

Plataforma EAD multi-tenancy para **Nutricao** — parte do ecossistema tpiola.

## Stack

- **Frontend:** Next.js 14 (App Router) + TypeScript
- **Design System:** Navy + Gold, glassmorphism (via `@saudegpt/core`)
- **Auth:** Supabase
- **AI Tutor:** OmniRoute + Gemini
- **Gamificação:** XP, badges, streaks, leaderboard

## Órgão Regulador

- **CRN — Conselho Regional de Nutrição**

## Começando

```bash
pnpm install
pnpm dev
```

## Estrutura

```
src/
  app/          # App Router pages
  components/   # UI components (course-specific)
  lib/          # Utilities
  styles/       # Theme overrides
```

## Dependências

Este projeto depende de `@saudegpt/core` para componentes compartilhados.

# Scaffold

Create files only after GO (or Josh says "scaffold anyway").

## Location

Prefer:

```text
ventures/<slug>/
```

If already inside a product repo, use repo root and skip nesting.

`<slug>` = lowercase kebab-case product name.

## Required files

| Path | Purpose |
|---|---|
| `README.md` | What it is + how to run |
| `VENTURE.md` | Full research, scores, citations, loops |
| `SPEC.md` | Product spec |
| `PLAN.md` | 30-day milestones |
| `REVENUE.md` | Pricing + channels |
| `YC.md` | Optional; yc mode or YC score ≥ 6 |
| `AGENTS.md` | How coding agents should behave here |
| `department/handoff.md` | Packet for Shua Department |
| `.cursor/rules/venture.mdc` | Always-on project rule |
| `apps/web/` or `src/` | Minimal stubs for chosen stack |

## Default Next.js tree (consumer / web)

```text
apps/web/
  package.json          # stub or real if user asks to init
  app/layout.tsx        # stub
  app/page.tsx          # stub hero + CTA
  app/globals.css       # CSS variables placeholder
  components/.gitkeep
  lib/.gitkeep
docs/
  decisions/.gitkeep
```

## Default agent/CLI tree

```text
src/
  main.py | index.ts
  agent/
  tools/
tests/
pyproject.toml | package.json
```

## AGENTS.md minimum

- Product one-liner
- Do / don't
- Link to SPEC.md + department handoff
- Prefer `/forge` for code, `/form` for UI, `/proof` before "done"
- No secrets in repo

## Init commands

If network and tooling allow, offer (do not force):

```bash
# example
npx create-next-app@latest apps/web --ts --app --tailwind --eslint --src-dir=false --import-alias "@/*"
```

Only run package managers if Josh confirms or already asked to scaffold for real.

## Quality bar

Stubs should compile conceptually. Prefer real small files over empty noise.
Do not generate 40 placeholder components.

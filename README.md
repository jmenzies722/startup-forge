# Startup Forge

Cursor skill that runs a **full venture pipeline** for Shua Labs:

idea → live market research → adversarial edge → Go/Pivot/Kill score → clear product → scaffold → Shua Department handoff.

Not a vibe generator. Not a 40-page fake business plan.

## Install

### This repo

Open in Cursor. Skill path:

```text
.cursor/skills/startup-forge/
```

### Every project (user skills)

```bash
git clone https://github.com/jmenzies722/startup-forge.git
cp -R startup-forge/.cursor/skills/startup-forge ~/.cursor/skills/
```

Reload Cursor → confirm under **Settings → Skills**.

### Invoke

```text
/startup-forge
```

```text
/startup-forge
validate: interactive AI skill coach for adults, solo, YC track
```

```text
/startup-forge
generate me a cool consumer subscription under Shua Labs
```

```text
/startup-forge
micro: something I can sell in two weeks on Gumroad
```

## Modes

| Mode | Use |
|---|---|
| `validate` | You have an idea |
| `generate` | You need an idea |
| `micro` | Small paid product / cashflow |
| `yc` | Optimize for YC narrative |
| `scaffold` | Already decided — make the folders |

## What you get

1. Market Card with cited sources
2. Edge loop (for/against)
3. Score /100 + **GO | PIVOT | KILL**
4. Clear SPEC (loop, MVP, pricing)
5. Local `ventures/<slug>/` scaffold ready for `/forge`
6. Department handoff packet

## Pair with

- `generate-project-ideas` — weekend toys / portfolio sparks
- `shua-department` — Pilot / Scope / Pitch / Form / Forge / Proof
- Context.dev MCP — live web research inside the skill

## Product note

See `PRODUCT.md` for the Go/No-Go on packaging this skill itself as a SaaS.

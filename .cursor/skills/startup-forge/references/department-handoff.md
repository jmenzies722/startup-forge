# Department + harness handoff

Shua Department (`jmenzies722/shua-department`) is the coding crew.
Grok bots stay in chat for strategy/brainstorm; they are **not** ported into the department repo.

## After scaffold

1. If department not installed in the venture repo:

```bash
# from a checkout of shua-department
./scripts/install.sh --repo /path/to/ventures/<slug>
```

2. Suggested route (Director):

| Step | Agent | Job |
|---|---|---|
| 1 | `/pilot` | Lock definition of done from SPEC.md |
| 2 | `/scope` | Challenge Market Card; demand citations |
| 3 | `/pitch` | Name, brand, landing copy |
| 4 | `/axis` | Architecture ADR for MVP |
| 5 | `/form` | Visual system (follow design-bar) |
| 6 | `/forge` | Implement MVP |
| 7 | `/ward` | Auth, env, deploy basics |
| 8 | `/proof` | Independent verify before "shipped" |

3. Write `department/handoff.md` using:

```markdown
# Handoff — <product>

## Outcome wanted
...

## Files
- SPEC.md
- VENTURE.md
- ...

## Evidence so far
- Market Card citations
- Verdict + score

## Status
ready_for_build | needs_pivot | blocked

## Next allowed move
/pilot → ...

## Do not
- Rewrite the wedge without Josh
- Expand scope beyond MVP in
```

## Cursor / Claude / Codex

- Cursor: skill via `/startup-forge`; agents via department install
- Claude Code / Codex: follow venture `AGENTS.md`
- Keep one source of truth: `SPEC.md`

## Grok team

Use Grok for: messy brainstorming, long adversarial debates, alternate narratives.
Bring conclusions back into `VENTURE.md` so the coding crew stays grounded.

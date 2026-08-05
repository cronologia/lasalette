# Our Lady of La Salette — Cronologia

An open, source-referenced chronology of the Marian apparition reported at
La Salette-Fallavaux (French Alps, diocese of Grenoble) on 19 September 1846,
of the Church's judgments on it, and of the controversy over the "Secrets of
La Salette".

**Site:** https://cronologia.github.io/lasalette/ (English, Spanish and
Portuguese; the root URL redirects to the visitor's locale.)

## What this project records — and how

The apparition is recorded as a **reported** event with Church judgments: the
dataset states who reported what and when, and what the Church ruled and when,
citing the ruling document. It never asserts the supernatural claim as fact,
and never denies it.

The spine:

- **19 Sep 1846** — two shepherd children, Mélanie Calvat (14) and Maximin
  Giraud (11), report a weeping "Beautiful Lady" and a public message on
  blasphemy and Sunday observance, delivered partly in French, partly in the
  local Occitan dialect.
- **1846–1851** — Bishop Philibert de Bruillard's investigation; **19 Sep
  1851**, his doctrinal pronouncement declares the apparition worthy of
  belief; **1 May 1852**, his pastoral decrees the sanctuary and founds the
  Missionaries of Our Lady of La Salette.
- **The secrets, carried as a recorded controversy** — written and sent sealed
  to Pius IX in July 1851; Mélanie's expanding later versions culminating in
  the 1879 Lecce booklet (imprimatur of the Bishop of Lecce); the Holy Office
  decree of **21 Dec 1915** ordering the faithful not to discuss the secret
  under its various forms (verified against AAS 7 (1915) 594–595), and the
  decree of **9 May 1923** placing the booklet's 1922 reprint on the Index
  (verified against AAS 15 (1923) 287–288). The 1851 approval and the later
  disciplinary acts are **separate judgments about separate objects** — the
  apparition vs. the expanded secrets — and this dataset keeps them separate.

## Repository layout

- `data/chronology.json` — the single source of truth (English, hand-edited)
- `data/i18n/{es,pt}.json` — exact-key translation dictionaries (hand-authored)
- `build.js` — zero-dependency compiler → `docs/{en,es,pt}/`
- `docs/` — compiled static site, served by GitHub Pages (committed)
- `scripts/validate-data.js` — schema and citation gate (run before every commit)
- `KEYWORDS.md` — naming variants for searching sources
- `AGENTS.md`, `context.md` — working rules and domain background

## Working on the data

```
node scripts/validate-data.js && node --test && node build.js
```

All three must pass, and the regenerated `docs/` is committed **with** the data
in the same change. Every fact carries `sources[]`; uncertain dates carry
`dateVerified: false` and a `dateNote` recording the disagreement instead of
resolving it. See `AGENTS.md` and the `sourcing-rules` skill in
`cronologia/core`.

Corrections against primary sources are welcome via pull request.

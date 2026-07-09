# ESSAI 2026 — Industry Challenges

A static microsite that displays the partner industry challenges for the ESSAI 2026 summer school. Each challenge is rendered as a homogeneous card so students can browse, filter by domain, and expand for full details.

## Contents

- [`challenges.html`](challenges.html) — single-file microsite (HTML + CSS + a few lines of JS). No build step.

## Partners featured

- **OptiKonf FlexCo** — Manufacturing / Symbolic AI configurators
- **SAP** — Business process simulation (Signavio)
- **Algoryx & cleAIr** — Physical AI, multi-agent systems, AI governance (WASP)
- **Graphwise** — Hybrid AI, knowledge graphs, ontology optimisation for LLMs

## Logos

Logo files live in [`assets/`](assets/) — see [`assets/README.md`](assets/README.md) for the expected filenames.

## Local preview

Just open the file in a browser:

```sh
open challenges.html
```

Or serve the directory:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000/challenges.html
```

## Publishing

The page is self-contained and can be dropped onto any static host (GitHub Pages, Netlify, the school website, etc.).

### GitHub Pages

Enable Pages on the `main` branch (root) — the site will be available at `https://<owner>.github.io/<repo>/challenges.html`.

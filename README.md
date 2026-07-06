# Replication with Language Models — SICSS Istanbul Slides

A short talk on LLM-based replication in social science, synthesizing two
papers: a diagnostic tool for prompt stability, and an empirical audit of
LLM replication fragility over time. Companion coding exercises are at
[sicss_istanbul_exercises](https://github.com/cjbarrie/sicss_istanbul_exercises).

## View the slides

**[Open the slides](https://cjbarrie.github.io/sicss_istanbul_slides/)**
(served via GitHub Pages).

Press `S` to open speaker notes in a separate window. Use arrow keys or
click to advance through fragments.

## Re-rendering locally

Requires [Quarto](https://quarto.org):

```bash
quarto render llm_replication_presentation.qmd
```

This regenerates `llm_replication_presentation.html`, which is self-contained
(`self-contained: true`) — all figures and styles are embedded, so it can be
opened directly or served as a static file with no other dependencies.

## Files

- `llm_replication_presentation.qmd` — Quarto revealjs source
- `llm_replication_presentation.html` — rendered, self-contained slides (what GitHub Pages serves)
- `theme-template.scss` — slide theme
- `references.bib` — citations for both papers
- `figures/` — source images (real figure crops from both papers, plus outputs from the companion exercises)
- `index.html` — redirects the repo's Pages root to the slides

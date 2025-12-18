# UKFin+ Showcase Slides (GitHub Pages)

This repository hosts the **public, rendered HTML** for the UKFin+ 10-minute showcase slide deck via **GitHub Pages**.

- **Live deck:** https://quinfer.github.io/ukfin-showcase-slides/
- **Rendered artifact:** `index.html`

## What is this?

The deck summarises UKFin+ findings on evaluating AI architectures for regulatory rule extraction (structure, terminology, and reliability/calibration), with an emphasis on responsible deployment.

## Source (editable)

The source Quarto file is maintained in the main UKFin+ project repo:

- `presentations/showcase/UKFin_Showcase_10min_10_slides.qmd`

This Pages repo is intentionally kept minimal and only stores the rendered `index.html` for sharing.

## How the deck is updated

From the main UKFin+ project, run:

```bash
bash presentations/publish_to_github.sh
```

That script:
- renders the Quarto RevealJS deck
- copies it to this repo as `index.html`
- commits and pushes to GitHub

## Contact

Professor Barry Quinn (Ulster University Business School) — `b.quinn1@ulster.ac.uk`

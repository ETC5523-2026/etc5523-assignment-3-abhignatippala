
# Abhigna Tippala | Data Made Simple

Personal website and blog created for **ETC5523: Communicating with Data** (Assignment 3), Monash University.

**Live website:** https://etc5523-2026.github.io/etc5523-assignment-3-abhignatippala/

## Intended audience

This blog post is written for community water-monitoring volunteers and interested members of the public who care about their local streams but have no training in statistics.

## About the blog post

The post *"Can cheaper sensors keep an eye on nitrate in our streams?"* adapts my Assignment 2 technical report on Kermorvant et al. (2023) for a general audience. It explains whether low-cost water-quality sensors can help estimate nitrate levels in freshwater streams, using plain language, a redesigned figure and a simplified table.

## Repository structure

| Path | Description |
|---|---|
| `posts/nitrate-sensors/` | Blog post (`index.qmd`) and references (`references.bib`) |
| `index.qmd` | Homepage listing of posts |
| `about.qmd` | About page |
| `styles.scss` | Custom theme |
| `_quarto.yml` | Website settings |
| `_freeze/` | Stored R output used when rendering |
| `docs/` | Rendered website published with GitHub Pages |

## Reproducing the website

Requires R (with `ggplot2`, `dplyr`, `tidyr` and `knitr`) and Quarto. From the project folder, run:

    quarto render

The rendered site is written to `docs/`.

## Generative AI declaration

 I used Claude (Anthropic) to help improve the wording of my blog post and website content, refine my ideas, and troubleshoot some technical issues with Quarto and Git. I reviewed and edited the suggestions in my own words and checked the final content and code.



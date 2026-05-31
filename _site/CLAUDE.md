# Extraordinary Engineer

Personal essay site inspired by paulgraham.com. Vestal statue / classical sketch aesthetic.

## Stack
- Static site built with Jekyll (GitHub Pages)
- No frameworks, no JS — just HTML/CSS/SVG + Markdown essays
- Hosted at: https://rupa99.github.io/ordinaryengineer/

## Design
- Sans-serif font (Inter), no italics
- Warm parchment background (#f4f0e8) with subtle gradients
- Etched line details: double rules, diamond bullets, ornamental dividers
- Inline SVG line-art of veiled vestal figure on homepage
- Sidebar with column sketch and /// ornament
- Drop cap on first paragraph of essays
- Double etched margin lines on essay body text

## Structure
- `_essays/` — Markdown essay files. Each auto-appears on the homepage list.
- `_about/` — About section pages in Markdown.
- `_layouts/` — Jekyll layout templates (default shell, home page, essay page).
- `inspiration/` — Reference images for the visual design.
- `index.md` — Homepage entry point.
- `_config.yml` — Jekyll config.

## Adding an essay
Create a file in `_essays/` with frontmatter:
```yaml
---
layout: essay
title: Your Essay Title
date: 2026-06-15
---
```
Then write markdown. It auto-lists on the homepage.

## Running locally
```
bundle exec jekyll serve
```

# Kobayashi Laboratory Website

Source code for the [Kobayashi Laboratory website](https://isct-koba-lab.github.io/).

## Overview

This repository contains the source files for the Kobayashi Laboratory website, built with [Zensical](https://zensical.org/) and hosted on GitHub Pages.

## Structure

- `docs/` - Source Markdown files
- `_data/` - Data files (e.g., news)
- `_templates/` - Jinja2 templates for auto-generated pages
- `generate.py` - Script to generate `docs/news.md` and update `docs/index.md` from `_data/news.yml`

## Adding News

Edit `_data/news.yml` and push. GitHub Actions will automatically regenerate `docs/news.md` and update the news section in `docs/index.md`.

## Development

```bash
pip install zensical jinja2 pyyaml
python generate.py
zensical build --clean
```
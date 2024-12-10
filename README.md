# _brand.yml

This repository contains a `_brand.yml` configuration file defining colours, typography, and logos consistent with the UK Centre for Ecology & Hydrology branding guidelines.

> [!IMPORTANT]
> This is a work in progress and should be considered _unofficial_.

## About

In the [`_brand.yml` documentation](https://posit-dev.github.io/brand-yml/) Posit state that

> _"Our goal is to support unified, branded theming for all of Posit’s open source tools—from web applications to printed reports to dashboards and presentations—with a consistent look and feel."_

In principle, `_brand.yml` provides a way to single-source this information and seamlessly integrate it into documents, dashboards, presentations etc.
However, the project is under active development and many things do not quite work out of the box yet (e.g. R Shiny, dark mode).

## Usage

In many cases it is sufficient to simply download `_brand.yml` and place it in the root directory of your project.


## FAQ

### Relationship with Quarto templates

The [UKCEH Quarto templates](https://github.com/ukceh-rse/quarto-templates) _should_ source `_brand.yml`, and the logos contained here.
However, I am so far not clear of the best way to do this.


## Inspiration

- https://github.com/stanford-brand-yml/brand-yml
- https://github.com/nhs-r-community/assets/tree/main/brand

# _brand.yml

> [!IMPORTANT]
> This is a work in progress and should be considered _unofficial_.

The [`_brand.yml` configuration file](https://posit-dev.github.io/brand-yml/) by Posit defines colours, typography, logos and layouts for maintaining consistent branding across formats.

In principle, `_brand.yml` provides a way to single-source this information and seamlessly integrate it into documents, dashboards, presentations etc.
However, the project is under active development and many things do not quite work out of the box yet (e.g. R Shiny, dark mode).

## Usage

In many cases it is sufficient to simply download `_brand.yml` and place it in the root directory of your project.


## Relationship with Quarto templates

The [UKCEH Quarto templates](https://github.com/ukceh-rse/quarto-templates) _should_ source `_brand.yml`, and the logos contained here.
However, I am so far not clear of the best way to do this.

## Inspiration

- https://github.com/stanford-brand-yml/brand-yml

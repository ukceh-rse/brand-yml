# brand.yml

This repository contains a `brand.yml` configuration defining colours, typography, and logos consistent with the UK Centre for Ecology & Hydrology branding guidelines.

To see the effect of the branding on a standard Quarto document (`template.qmd`), take a look at the [Pages site](https://ukceh-rse.github.io/brand-yml/).

## About

In the [`brand.yml` documentation](https://posit-dev.github.io/brand-yml/) Posit state that

> _"Our goal is to support unified, branded theming for all of Posit’s open source tools—from web applications to printed reports to dashboards and presentations—with a consistent look and feel."_

In principle, `brand.yml` provides a way to single-source this information and seamlessly integrate it into documents, dashboards, presentations etc.
However, the project is under active development and many things do not quite work out of the box yet (e.g. R Shiny, dark mode).

## Requirements

- **Quarto version 1.8** or higher.


## Usage

Run the following command in the root directory of your quarto project.

```bash
quarto add ukceh-rse/brand-yml
```

This will install the extension under the `_extensions` subdirectory.
If you're using version control, you will want to check in this directory.

> [!WARNING]
> This will only work for _projects_, i.e. when there is a `_quarto.yml` file containing the `project` field.
> However, there is no real downside to upgrading stand-alone documents to projects.
> Simply create a `_quarto.yml` file with the following contents:
> ```yaml
> project:
>   type: default
> ```


### Without installing an extension

An alternative is to simply download the contents of `_extensions/brand/` and manually place them in your quarto project. 

Rename `brand.yml` -> `_brand.yml` so that it is picked up automatically. This will work for non-projects.


### As a starter template

This extension also serves as a starter template for stand-alone documents and presentations.

To create a new project based on this template, run the following:

```sh
quarto use template ukceh-rse/brand-yml
```

There are currently 5 formats provided out of the box.

- `html`
- `typst`
- `typst-dark`
- `revealjs`
- `revealjs-dark`

You will need to specify the desired format when you render.

```sh
quarto render --to FORMAT
```

If you plan to render to multiple formats with the same file extension you will also need to specify an output file (`--output FILE`) so that they don't overwrite each other.

## Looking for templates?

In progress.

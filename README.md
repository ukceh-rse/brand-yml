# brand.yml

This repository contains a `brand.yml` configuration defining colours, typography, and logos consistent with the UK Centre for Ecology & Hydrology branding guidelines.

> [!IMPORTANT]
> This is a work in progress and should be considered _unofficial_.


## About

In the [`brand.yml` documentation](https://posit-dev.github.io/brand-yml/) Posit state that

> _"Our goal is to support unified, branded theming for all of Posit’s open source tools—from web applications to printed reports to dashboards and presentations—with a consistent look and feel."_

In principle, `brand.yml` provides a way to single-source this information and seamlessly integrate it into documents, dashboards, presentations etc.
However, the project is under active development and many things do not quite work out of the box yet (e.g. R Shiny, dark mode).


## Usage

### Apply to an existing project

Run the following command in the root directory of your quarto project.

```bash
quarto add ukceh-rse/brand-yml
```

This will install the extension under the `_extensions` subdirectory.
If you're using version control, you will want to check in this directory.

> [!WARNING]
> This will only work with Quarto version 1.8 or higher. As of 20/08/2025 this is still in pre-release, but it can be downloaded [here](https://prerelease.quarto.org/docs/download/prerelease.html).

### As a starter template

This extension also serves as a starter template for stand-alone documents of the following formats:

- HTML
- Typst (light and dark)
- Revealjs

To create a new project based on this template, run the following:

```sh
quarto user template ukceh-rse/brand-yml
```


### Without installing an extension

An alternative is to simply download the contents of `_extensions/brand/` and manually place them in your quarto project. Rename `brand.yml` -> `_brand.yml` so that it is picked up automatically.

## Screenshots

<img width="1314" height="891" alt="image" src="https://github.com/user-attachments/assets/1f501f7c-948b-4711-b698-3e8da5d6626b" />

<img width="1314" height="891" alt="image" src="https://github.com/user-attachments/assets/fff93355-ba92-4afe-b66e-6c9de05f8eaa" />


## Looking for templates?

See [github.com/ukceh-rse/quarto-templates](https://github.com/ukceh-rse/quarto-templates).

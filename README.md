# chatur-docs

[![Publish docs via GitHub](https://github.com/ua-data7/chatur-docs/actions/workflows/gh-pages.yml/badge.svg)](https://github.com/ua-data7/chatur-docs/actions/workflows/gh-pages.yml)

MKDocs Material pages for CyVerse Chatur

# Development

## Testing locally

Follow the [Material for MKDocs instructions](https://squidfunk.github.io/mkdocs-material/getting-started/)

```
$ git clone https://github.com/tyson-swetnam/chatur-docs
$ cd chatur-docs
$ pip install -r requirements
$ mkdocs serve
```

## Action with ReadTheDocs Theme

This is a template that uses the [MkDocs deploy](https://github.com/marketplace/actions/deploy-mkdocs) GitHub action.

We are using the `@nomaterial` branch for the [Action](.github/workflows/main.yml) to produce the ReadTheDocs style layout with the `theme: readthedocs` in the [mkdocs.yml](./mkdocs.yml):

```
theme:
  name: readthedocs
```

## Action with Material Theme

To change to [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) theme, change [Action](./github/workflows/main.yml) to `@master` and set `theme: material` in the [mkdocs.yml](./mkdocs.yml):

```
theme:
  name: material
```

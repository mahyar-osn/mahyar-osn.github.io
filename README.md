# [My personal website](https://mahyar-osn.github.io)

Personal website built with [Hugo](https://gohugo.io/) using the [Wowchemy Academic](https://github.com/wowchemy/starter-hugo-academic) theme (via Hugo Modules). Deployed to GitHub Pages from `main` via the workflow in `.github/workflows/deploy.yml`.

## Local development

Requires Hugo extended `0.91.2` and Go (for fetching theme modules).

```sh
hugo server
```

## Build

```sh
hugo --gc --minify
```

Output goes to `public/`.

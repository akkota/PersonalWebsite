# Akhil Kota — Personal Website

Polished personal site built with [Hugo](https://gohugo.io/) and the [Blowfish](https://blowfish.page/) theme.

**Live:** https://akkota.github.io/PersonalWebsite/

## Local development

```bash
git clone --recurse-submodules https://github.com/akkota/PersonalWebsite.git
cd PersonalWebsite
hugo server -D
```

Open http://localhost:1313/PersonalWebsite/

## Production build

```bash
hugo --minify
```

## GitHub Pages

This repo deploys via GitHub Actions (`.github/workflows/hugo.yml`).

1. Push to `main`
2. In the GitHub repo: **Settings → Pages → Source → GitHub Actions**
3. The site publishes at `https://akkota.github.io/PersonalWebsite/`

## Theme

Blowfish is included as a git submodule under `themes/blowfish`. Update with:

```bash
git submodule update --remote --merge
```

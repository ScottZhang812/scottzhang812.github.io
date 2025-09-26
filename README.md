# Xuteng Zhang – Academic Homepage

This is the repo of the academic page of Xuteng Zhang. Forked from `RayeRen/acad-homepage.github.io`.

- Live site: https://scottzhang812.github.io
- Tech stack: Jekyll + GitHub Pages

## Features

- Minimal, responsive academic homepage
- Easy content editing via `_pages/about.md`
- Configurable metadata via `_config.yml`
- Asset pipeline with SCSS and static JS/CSS under `assets/`

## Project Structure

- `_pages/` — Main page content (e.g., `about.md`)
- `_layouts/`, `_includes/`, `_sass/` — Theme templates and styles
- `assets/` — CSS, JS, fonts, and images
- `_config.yml` — Site-wide configuration
- `CNAME` — Custom domain (optional)

## Getting Started

### Prerequisites
- Ruby (>= 2.7), Bundler, Jekyll

### Local Development
```bash
bundle install
bundle exec jekyll serve
```
Then open `http://127.0.0.1:4000`.

## Customize

- Site metadata: edit `_config.yml`
- Homepage content: edit `_pages/about.md`
- Styles: edit `assets/css/main.scss` or `_sass/` variables and partials
- Navigation: edit `_data/navigation.yml`
- Images: place under `images/` and reference relatively

## Deployment

- Push changes to the default branch (e.g., `main`)
- Enable GitHub Pages in repository Settings → Pages (use `GitHub Actions` or `Deploy from a branch`)
- If using a custom domain, set `CNAME` and configure DNS accordingly

## Acknowledgements

- Template forked from [`RayeRen/acad-homepage.github.io`](https://github.com/RayeRen/acad-homepage.github.io)

---

## TODO

- [ ] 减小h1标题高度，避免重叠
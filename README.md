# Yuxiang Peng's academic website

This repository contains the source for [pickspeng.github.io](https://pickspeng.github.io), a Jekyll site hosted by GitHub Pages.

## Content

- `_pages/about.md` — homepage, biography, teaching, and news
- `_pages/publications.md` — publication-page renderer
- `_data/publications.yml` — publication metadata, links, and abstracts
- `_pages/talks.md` — talks and presentations
- `_pages/cv.md` — CV page
- `files/` — downloadable CV, papers, and slides
- `images/pic.jpg` — profile photo
- `_config.yml` — site metadata and author links
- `_data/navigation.yml` — top navigation

The remaining `_includes`, `_layouts`, `_sass`, and `assets` directories implement the Academic Pages/Minimal Mistakes theme.

## Local preview

Install Ruby and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve
```

Open <http://localhost:4000>. The generated `_site/` directory is ignored by Git.

## License

The underlying theme is distributed under the MIT license; see `LICENSE`.

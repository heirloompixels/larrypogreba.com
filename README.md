# Larry Pogreba

Zola site for Larry Pogreba.

## Local development

```sh
zola serve
```

## Build

```sh
zola build
```

## Deployment

- Source repo: `git@github.com:heirloompixels/larrypogreba.com.git`
- GitHub Actions builds on pushes to `main`
- Published branch: `gh-pages`
- Public URL: `https://larrypogreba.com`

## Project structure

- `content/`: Zola content sections and page content
- `templates/`: Zola templates for shared layout and page rendering
- `static/`: static assets copied directly into the built site
- `images/`: local source images used for gallery content
- `config.toml`: Zola site configuration
- `.github/workflows/main.yml`: GitHub Actions build and deploy workflow

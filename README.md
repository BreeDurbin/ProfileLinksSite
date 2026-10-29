# ProfileLinksSite
A Liketree style page with links to various projects and socials

Built with [Hugo](https://gohugo.io) and the [LucentLink](https://github.com/cx48/LucentLink-Hugo) theme (git submodule in `themes/`).

## Editing

- Links, name, tagline, and images: `content/_index.md`
- Images: `static/images/`
- Page layout (overrides the theme's): `layouts/index.html`

## Local preview

```bash
git submodule update --init --recursive
hugo server
```

## Deployment

`.github/workflows/deploy.yml` builds and deploys to GitHub Pages on every push to `main`.
One-time setup: in the repo's **Settings → Pages**, set **Source** to **GitHub Actions**.

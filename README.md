## arkdr.org — Arkansas Baptist Disaster Relief

Website for Arkansas Baptist Disaster Relief providing volunteer information, IMT tools, and field assets. Deployed to [arkdr.org](https://arkdr.org) via GitHub Pages.

## Stack

- [Astro](https://astro.build/) static site generator
- GitHub Pages hosting with custom domain
- GitHub Actions deploy workflow

## Local Development

```bash
npm install
npm run dev
```

Preview at `http://localhost:4321`.

## Deployment

Pushes to `main` trigger the GitHub Actions deploy workflow. The site is served from the `gh-pages` branch with HTTPS enforced.

## License

Content is licensed under [CC-BY-4.0](LICENSE).

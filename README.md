# Engineering Deck - WebGL Deployment

This repository contains the WebGL build files for the Engineering Deck game, deployed via Cloudflare Pages.

## Live Site
🎮 [Play Engineering Deck](https://your-site.pages.dev) _(will be updated after deployment)_

## About
This is an **automated deployment repository** containing only the built WebGL files. The source code is maintained separately in the main Engineering Deck repository.

## Updates
This repository is automatically updated when new builds are pushed. Cloudflare Pages automatically deploys changes within 1-2 minutes.

## Structure
```
/
├── Build/          # Unity WebGL build files (.wasm, .data, .js, .br)
├── TemplateData/   # Unity template assets
├── index.html      # Main entry point
└── _headers        # Cloudflare configuration for Brotli & caching
```

## Build Info
- **Engine**: Unity (URP)
- **Compression**: Brotli
- **Target Platform**: WebGL
- **Hosting**: Cloudflare Pages

---

*Last updated: Auto-deployed via Cloudflare Pages*

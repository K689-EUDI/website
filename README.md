<p align="center">
  <img src="public/icon.webp" width="80" alt="IdentID" />
</p>

# identid-website

The marketing website for [IdentID](https://github.com/K689-EUDI/IdentID) — an Android EUDI wallet built at KTU.  
Deployed at [identid.linux123123.com](https://identid.linux123123.com).

## Build

```sh
pnpm install
pnpm dev       # dev server at localhost:4321
pnpm build     # production build → ./dist/
pnpm preview   # preview the production build locally
```

The `dist/` folder is a fully static site, ready to deploy.

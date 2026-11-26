# akos.gg

Personal site. Astro (static) + Tailwind + three.js, hosted on Cloudflare Pages.

```sh
pnpm install
pnpm dev     # http://localhost:4321
pnpm build   # -> dist/
```

Node version is pinned in `.node-version` (Cloudflare Pages and mise both read it).

## Cloudflare Pages settings

- Framework preset: Astro
- Build command: `pnpm build`
- Build output directory: `dist`

# KNA Systems website

Astro static website, Macedonian first, ready for Cloudflare Pages.

## Before publishing

1. Open `src/pages/index.astro` and replace `REPLACE_WITH_YOUR_EMAIL` with your actual business email. Until then, the contact button is a placeholder and will not work.
2. Review portfolio descriptions to ensure they accurately reflect work you may publicly showcase.
3. Add your real domain when available.

## Local development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Cloudflare Pages deployment

1. Upload all project files to your GitHub repository (do not upload the enclosing ZIP as a single file).
2. In Cloudflare dashboard choose Workers & Pages > Create > Pages > Connect to Git.
3. Select the repository.
4. Framework preset: Astro; build command: `npm run build`; build output directory: `dist`.
5. Deploy. You will receive a `pages.dev` address.

The website is static and needs no paid hosting or database. The contact link uses `mailto:` and is not a contact form.

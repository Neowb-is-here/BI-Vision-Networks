# BI-Vision Networks Website

Marketing website for BI-Vision Networks, a CCTV installation and support business serving Negros Occidental.

## Local development

```sh
npm install
npm run dev
```

Open the local address printed by Astro.

## Production build

```sh
npm run build
npm run preview
```

The production files are generated in `dist/`.

## Publish with GitHub and Vercel

1. Create an empty GitHub repository.
2. Upload the contents of this `BI-Vision-Networks` folder to that repository.
3. In Vercel, choose **Add New → Project** and import the GitHub repository.
4. Vercel should detect **Astro** automatically. Keep the default build command (`npm run build`) and output directory (`dist`).
5. Deploy. Later pushes to the main branch will update the live website automatically.

The website is a static Astro build and does not require a Vercel adapter.

## Contact form behavior

The assessment form prepares an email in the visitor's default email app. This avoids storing visitor data or requiring a paid form service. A hosted form endpoint can be added later if BI-Vision needs submissions to work without an installed email app.

## Content notes

- The supplied shield is intentionally treated as a placeholder logo.
- Project claims are limited to details verified from BI-Vision's public Facebook page.
- Replace project photographs only with BI-Vision-owned images and keep `public/images/ASSET-SOURCES.md` updated.

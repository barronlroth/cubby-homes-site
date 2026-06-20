# Cubby Homes Site

Marketing site and SEO blog for [Cubby](https://cubby.homes), the iOS home inventory app for remembering what you own and exactly where it lives.

## Stack

- Astro static site
- Markdown blog posts in `src/content/blog`
- RSS and sitemap output
- Vercel production deploy at `https://cubby.homes`

## Development

```bash
npm install
npm run build
npm run preview -- --host 127.0.0.1 --port 4321
```

## Content

- Blog posts live in `src/content/blog/*.md`
- Blog illustrations live in `public/blog/illustrations/`
- App Store links point to Cubby app ID `6751732388`

## Deploy

The Vercel project is `cubby-homes` under `barronlroths-projects`.

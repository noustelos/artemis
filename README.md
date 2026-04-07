# Artemis Landing Page

A premium, conversion-focused static site for DogWithin, built around The 7 Day Nervous System Reset for Dogs and its interactive pre-funnel experiences.

The project includes three localized landing pages and three localized interactive experiences:

- English landing page
- Norwegian landing page
- Greek landing page
- English interactive experience
- Norwegian interactive experience
- Greek interactive experience

## Files

- `index.html` — English version
- `norwegian.html` — Norwegian version
- `greek.html` — Greek version
- `interactive-dog-conversation.html` — English interactive experience
- `interaktiv-hundesamtale.html` — Norwegian interactive experience
- `interactive-dog-conversation-el.html` — Greek interactive experience
- `robots.txt` — crawl rules for search engines
- `sitemap.xml` — submitted URL inventory for indexing
- `assets/og/` — social share images in SVG and PNG formats
- `.gitignore` — ignores macOS metadata files

## Tech Stack

- Static HTML
- Custom CSS and vanilla JavaScript for landing pages
- TailwindCSS via CDN for interactive experiences

## Features

- Mobile-first responsive layout
- Premium editorial visual style
- Localized landing pages and interactive experiences
- Smooth scrolling navigation
- Fade-in scroll animations
- Interactive dog behavior conversation flow
- FAQ accordion
- Mobile sticky CTA
- SEO metadata, structured data, canonical tags, and hreflang
- Open Graph and Twitter card support with dedicated share images
- `robots.txt` and `sitemap.xml` for indexing control

## Local Preview

Open the HTML files directly in a browser:

- `index.html`
- `norwegian.html`
- `greek.html`
- `interactive-dog-conversation.html`
- `interaktiv-hundesamtale.html`
- `interactive-dog-conversation-el.html`

## Deployment Notes

- The current SEO setup assumes production runs at `https://www.dogwithin.com/`.
- If the site is deployed to a different domain or subfolder, update canonical URLs, hreflang links, `robots.txt`, and `sitemap.xml`.
- Keep `robots.txt` and `sitemap.xml` at the site root when deploying.
- The `/pdf/` folder is intentionally blocked in `robots.txt` so the sold PDF is not indexed directly.
- Replace the `checkoutHref` constant in the landing pages when the real checkout URL is available.
- Social preview assets are available in both SVG and PNG inside `assets/og/`, but metadata now points to PNG for broader crawler compatibility.

## Repository

GitHub: https://github.com/noustelos/artemis
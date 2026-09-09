# Muhammad Aqib Javed | Portfolio

Personal portfolio site. Vanilla HTML/CSS/JS, no framework, no build step.

**Live:** https://portfolio-muhammad-aqibjaved.netlify.app/

## Sections

- **Home** — intro, profession rotator, social links, resume link.
- **About** — bio, resume link.
- **Delivered Work** — real client project (Perth Dynamic Solutions), with client quote + proof-of-review lightbox.
- **Projects** — practice builds, Swiper.js carousel, 8 cards.
- **Work Experience / Education** — tabbed timeline (JS tab switcher).
- **Services** — Frontend Development + WordPress Development, expandable cards.
- **Contact** — click-to-copy email, WhatsApp link, social links.
- **Footer** — auto-updating year via JS.

## Tech

- HTML5, CSS3
- Vanilla JavaScript (tabs, custom cursor, blob animations, lightbox, copy-email, footer year)
- [ScrollReveal](assets/js/scrollreveal.min.js) — scroll animations
- [Anime.js](https://cdn.jsdelivr.net/npm/animejs/lib/anime.iife.min.js) — CDN
- [Swiper.js](assets/js/swiper-bundle.min.js) — projects carousel
- Self-hosted RemixIcon subset (`assets/css/remixicon-subset.css`, 9 icons used)
- Fonts: Big Shoulders Display, IBM Plex Sans, IBM Plex Mono (Google Fonts)

## Structure

```
index.html
assets/
  css/
    styles.css
    remixicon-subset.css
    swiper-bundle.min.css
  js/
    main.js
    scrollreveal.min.js
    swiper-bundle.min.js
  img/
    home-perfil.webp
    favicon.png
    PerthDynamicSolutions.webp
    pds-review-proof.webp
    Real Home (clone).webp
    CV Maker clone.webp
    Metal Defence(clone).webp
    CAYUGA LAKE(clone).webp
    Anthony Medina(Clone).webp
    Houzez(Clone).webp
    Focal Point Homes(Clone).webp
    mc-duffers.webp
```

## Usage

Open `index.html` in browser, or deploy to static host (Netlify, GitHub Pages, Vercel).

To add/update projects: duplicate a `.projects__card.swiper-slide` block inside `#projects .swiper-wrapper`, update image, title, tags, description, and live link.

To add delivered work: duplicate `.delivered__card` block inside `#delivered .delivered__container`.

## Deployment

Netlify: `portfolio-muhammad-aqibjaved.netlify.app`

## Contact

- Email: maqibjaved.dev@gmail.com
- WhatsApp: https://api.whatsapp.com/send?phone=923136610068&text=Hello
- LinkedIn: linkedin.com/in/muhammad-aqibjaved-webdev
- GitHub: github.com/aqibarbi
- Location: Bahawalpur, Pakistan

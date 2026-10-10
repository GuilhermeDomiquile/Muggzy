# Muggzy

The party mug that hangs on you.

Muggzy is a light insulated mug with a lid and a swappable strap. You wear it across your chest, let go, and it hangs upright, so your drink stays with you and both hands stay free. This repository holds the brand's website, used both as a pitch and as the storefront for customers.

## Status

The product is in testing. The site shows v1 targets, not final specs, and every "buy" button opens WhatsApp so people can reserve a mug or ask for a group kit.

## What the site includes

- Hero with the Muggzy logo and a short product brief
- Six product differentials
- How it works, in three steps
- Shop section: mug with lid and strap ($29), extra strap ($10), custom group kit
- Occasions: graduation, frats and sororities, bachelorette, tailgates
- Specifications (v1 targets) and a 90 day roadmap
- FAQ and a closing contact section

## Project structure

```
index.html   The whole site: HTML, CSS, and JavaScript in one file
README.md    This file
```

## Run it locally

No build step. Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

Then go to http://localhost:8000.

## Deploy

**GitHub Pages:** in the repository, go to Settings, then Pages, choose the `main` branch and the root folder, and save.

**Vercel:** import the repository. No framework or build command is needed.

## Editing

- **WhatsApp number:** every contact link uses `https://wa.me/5511982026040`. Search for `5511982026040` in `index.html` and replace it to change the number.
- **Prices, specs, and roadmap:** edit the text directly in `index.html`. The numbers come from the Design Brief v0.1 and should change as tests come in.
- **Colors and fonts:** all design tokens are in the `:root` block at the top of the `<style>` tag.
- **Product photos:** the site currently has no photos. Add them as `<img>` tags (compressed, with descriptive `alt` text) in the hero and shop sections.

## Tech

Plain HTML and CSS, with [GSAP](https://gsap.com) and ScrollTrigger loaded from cdnjs for scroll animations. Fonts (Archivo, Inter, Fredoka) load from Google Fonts. The page is responsive and respects the reduced motion setting.

## Copy guidelines

Never say the lid "protects" a drink or "prevents" tampering. Always say it is designed to "help make it harder" for anyone to tamper with a drink.

## Contact

WhatsApp: (11) 98202-6040

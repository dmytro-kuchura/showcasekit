# ShowcaseKit

Website, support portal and privacy policy for **ShowcaseKit** — a native macOS app for designing App Store and Google Play marketing screenshots, MacBook mockups and product page artwork, 100% offline.

- **Website:** <https://dmytro-kuchura.github.io/showcasekit/>
- **Support:** <https://dmytro-kuchura.github.io/showcasekit/support.html>
- **Privacy Policy:** <https://dmytro-kuchura.github.io/showcasekit/privacy.html>
- **Issues & Feedback:** <https://github.com/dmytro-kuchura/showcasekit/issues/new>

## About ShowcaseKit

ShowcaseKit turns raw app captures into store-ready marketing visuals on macOS 15.0+ and exports at exact store pixel dimensions:

- **14 device models** across iOS, macOS and Android (iPhone 17 Pro, iPhone 15 Pro, iPhone 14, iPhone SE, iPad Pro, iPad Air, iPhone Duo, MacBook Pro, MacBook Air, Pixel 9 Pro, Pixel 8, Galaxy S24, Pixel Tablet and Galaxy Tab S9).
- **Exact @3x exports:** iPhone (`1284 × 2778 px`), iPad (`2232 × 2976 px`), iPhone Duo inner (`2007 × 2853` / `2853 × 2007 px`) & cover (`1398 × 2034` / `2034 × 1398 px`), and Mac (`2880 × 1800`, `2560 × 1600`, `1440 × 900`, `1280 × 800 px`).
- **App Store Creative assets:** 21:9 product page headers (`3840 × 1646 px`), 3:2 search results artwork (`3840 × 2560` / `1920 × 1280 px`) and universal 16:9 (`5244 × 2950 px`) exported as opaque PNGs.
- **Four layouts & typography:** Text Top, Text Bottom, Device Only and List Popout (with an 8-handle crop selector), sRGB gradients, solid fills and 11 typefaces.
- **Offline & private:** Zero accounts, zero analytics and zero network access. Portable `.showcasekit.json` project files are compatible with PreviewKit.

## Repository Structure

This repository hosts the static site deployed via GitHub Pages directly from `main` (no build step required):

| File | Purpose |
| --- | --- |
| `index.html` | Product landing page with features, workflow, privacy summary, FAQ and SEO metadata |
| `support.html` | Support contact info and troubleshooting FAQ |
| `privacy.html` | Privacy policy |
| `style.css` | Shared stylesheet for all pages |
| `icon.png` | App icon (`256 × 256 px`) |
| `og.png` | Open Graph / social preview card (`1200 × 630 px`) |
| `robots.txt` | Search engine crawler directives |
| `sitemap.xml` | XML sitemap for search engines |
| `site.webmanifest` | Web app manifest |

## Local Preview

Serve the directory with any static HTTP server:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Support

If you run into an issue or have a feature request, please [open an issue](https://github.com/dmytro-kuchura/showcasekit/issues/new) and include your macOS version, the ShowcaseKit version and build (`ShowcaseKit › About ShowcaseKit`), and for export problems, the device type and size you were exporting.

---

© 2026 Dmytro Kuchura

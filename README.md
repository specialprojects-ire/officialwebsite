# Trinethra — Official Website

Corporate website for **Trinethra Global Healthcare Technology Solutions Pvt Ltd**
(*Trinethra — Global Healthcare Technology Solutions*).

A single static page (`index.html`) with no build step. Open it in a browser or host it on any static host (GitHub Pages, Netlify, S3, etc.).

## Logo

Three leaves growing from one root: one for each of our commitments (clinical accuracy, financial clarity, compliance). The wordmark is set in Plus Jakarta Sans ExtraBold and the tagline in Inter SemiBold, both converted to shapes, so the files look the same everywhere without fonts installed.

| File | Use |
| --- | --- |
| `assets/logo/trinethra-logo.svg` | Main logo for white or light backgrounds |
| `assets/logo/trinethra-logo-white.svg` | For the primary green or other dark backgrounds |
| `assets/logo/trinethra-logo-stacked.svg` | Mark above the name, for documents and square layouts |
| `assets/logo/trinethra-mark.svg` | Leaves only, for small spaces |
| `assets/logo/trinethra-icon.svg` | App icon, favicon and social profile picture |

## Brand colors

| Role | Hex | Used for |
| --- | --- | --- |
| Primary | `#3F752B` | Headings, dark sections, buttons, footer (Tailwind `navy-*` scale) |
| Secondary | `#FF8C00` | Highlights, icons, primary call-to-action, logo eye (Tailwind `brand-*` scale) |
| Tertiary | `#7AC44B` | Small accents such as the logo's third-eye dot (Tailwind `saffron-*` scale) |

The color scales are defined once, in the `tailwind.config` block at the top of `index.html`.

## Before going live

All contact details are set in one place: the `SITE` object near the bottom of `index.html`.

| Setting | Current value | Action |
| --- | --- | --- |
| `email.contact` | `contact@trinethra.com` | Replace with the real business inbox (placeholder: confirm you own the domain) |
| `email.careers` | `careers@trinethra.com` | Replace with the real HR inbox |
| `phone` | empty (hidden) | Add a number to show it |
| `address` | `India` | Add the full registered office address |
| `social.*` | empty (hidden) | Add LinkedIn / X / YouTube URLs to show the icons |

Also review these items:

- **Claims:** the "95%+ accuracy benchmark", "24–48 hrs turnaround" and the AAPC/AHIMA team credentials should match what the company can contractually support. Security wording says controls are *aligned with* ISO 27001 / SOC 2. Change it to "certified" only once audits are complete.
- **Forms:** the contact form and job "Apply" links open the visitor's email app (`mailto:`). To collect submissions on a server, connect a form service such as Formspree or a backend.
- **Legal pages:** add a Privacy Policy and Terms of Use before launch.
- **Production CSS:** the page uses the Tailwind Play CDN. For production, consider compiling Tailwind to a static CSS file.

## Sections

Hero · Commitments · About · Services · Who we serve · Technology · Global delivery · Quality & people · Security & compliance · Engagement process · Free tools (7 calculators) · Careers · Contact · Footer

# Institute of Digital Risk — Brand & Homepage

A complete brand identity and responsive homepage for the **Institute of Digital Risk (IDR)**, an industry-led training and deployment institute focused on digital and AI risk.

---

## Deliverables

| File | Description |
|---|---|
| `idr-homepage.html` | Full responsive single-page website |
| `idr-logo-icon.svg` | Icon-only logo variant |
| `idr-logo-full.svg` | Full lockup — icon + wordmark |

---

## Homepage Sections

1. **Hero** — Headline, subheading, dual CTAs, animated grid background, and stat bar
2. **About IDR** — Two-column layout with brand pillars (university partnership, industry delivery, deployment-ready graduates)
3. **Service Pillars / Model** — Train → Hire → Innovate → Deploy pipeline + three service cards (Academy, Innovation & Incubation, Advisory Services)
4. **Community** — Audience grid (students, early-career, practitioners, organisations) with sector callout
5. **Contact / Register Interest** — Validated interest form with success state + contact details

---

## Technical Specs

- **Vanilla HTML5 / CSS / JS** — zero frameworks or dependencies
- **Responsive** — CSS Grid + Flexbox, tested at mobile (375px) and desktop (1280px)
- **Sticky navigation** with backdrop-blur and smooth scroll
- **Scroll-reveal animations** via IntersectionObserver
- **Mobile hamburger drawer** with accessible `aria-expanded` state
- **Form validation** — required fields, email format check, success feedback
- **Google Fonts** — Barlow Condensed (display) + Outfit (body), loaded via `<link>`
- **Semantic HTML5** — `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
- **Accessible** — ARIA labels, `sr-only` utility, sufficient colour contrast

---

## Colour Palette

| Token | Hex | Usage |
|---|---|---|
| `--orange` | `#F46012` | Primary brand, CTAs, accents |
| `--orange-dim` | `#B84A0D` | Hover states |
| `--black` | `#080B10` | Page background |
| `--dark` | `#0E1118` | Section backgrounds |
| `--text` | `#FAFAFA` | Body text |
| `--text-muted` | `#9AA0B0` | Secondary text |

---

## Typography

| Role | Font | Weight |
|---|---|---|
| Display / Headings | Barlow Condensed | 700–900 |
| Body / UI | Outfit | 300–600 |

---

## Logo Design Notes

- **Symbolism** — The isometric cube represents structure, layered complexity, and resilience. Its three visible faces mirror the multi-dimensional nature of risk: technical, organisational, and human.
- **Colour** — Orange signals alertness and innovation at the apex; near-black grounds the mark with authority appropriate to high-consequence sectors.
- **Typography** — The IDR monogram uses Barlow Condensed at weight 900 for maximum legibility at small sizes. The full wordmark stacks "INSTITUTE OF" and "DIGITAL RISK" in spaced caps.
- **Scalability** — The icon reduces cleanly to 16×16 favicon dimensions. The full lockup separates cleanly at mobile header widths.

---

## Usage

Open `idr-homepage.html` directly in any modern browser — no build step or server required.

```bash
open idr-homepage.html        # macOS
start idr-homepage.html       # Windows
xdg-open idr-homepage.html    # Linux
```

---

## Browser Support

Chrome 90+, Firefox 88+, Safari 14+, Edge 90+

# Vyager Digital — Site Reference

## Purpose

Marketing website for **Vyager**, a digital agency that builds integrated client-acquisition systems for expert-service businesses (consultants, medical professionals, advisors, B2B providers). The core offering is a three-phase system combining website builds, sales funnels, and ad campaigns — positioned as a cohesive system rather than individual services.

**Tagline:** "Websites, Funnels & Campaigns That Bring You Clients"
**Value prop:** "We connect your positioning, pages, and ads into one system — built to attract the right clients and convert them consistently."

The site is a single `index.html` file with all CSS and JS inline.

---

## Page Structure

| Section | ID / Class | Background |
|---|---|---|
| Nav | `#nav` | Transparent → sticky dark on scroll |
| Hero | `#hero` | Cosmic background image with dark overlay |
| Pillars strip | `.pillars-strip` | Navy (`--navy`) |
| Portfolio | `.sec-portfolio` | Navy |
| Problem | `.sec.sec-navy` | Navy |
| Three Phases | `#phases .sec-light` | Off-white (`--off`) |
| Outcomes | `.sec.sec-nav2` | Navy 2 (`--navy2`) |
| Testimonial | `.sec-light` | Off-white |
| Who We Work With | `.sec.sec-navy` | Navy |
| Team | `#team .sec-light` | Off-white (split layout with photo) |
| CTA | `#cta` | Black (`--black`) |
| Footer | `footer` | Black |

**Nav links:** How It Works, Team
**Primary CTA:** "Schedule a Discovery Call" (free consultation)

---

## Brand Colours

Defined as CSS custom properties in `:root`:

| Variable | Hex / Value | Usage |
|---|---|---|
| `--black` | `#080c14` | Page background, CTA section |
| `--navy` | `#0d1321` | Section backgrounds, pillars strip |
| `--navy2` | `#111827` | Outcomes section background |
| `--teal` | `#0ecfb0` | Primary accent — headings `em`, icons, labels, buttons, borders |
| `--teal-dim` | `rgba(14,207,176,0.1)` | Teal background tints |
| `--teal-border` | `rgba(14,207,176,0.2)` | Teal border treatments |
| `--white` | `#ffffff` | Primary text on dark backgrounds |
| `--off` | `#f4f6fa` | Light section backgrounds |
| `--text-dim` | `rgba(255,255,255,0.5)` | Subdued body text on dark |
| `--text-mid` | `rgba(255,255,255,0.75)` | Mid-weight body text on dark |
| `--border` | `rgba(255,255,255,0.07)` | Subtle dividers and card borders |
| `--dark-text` | `#1a2035` | Body/heading text on light sections |
| `--dark-dim` | `rgba(26,32,53,0.5)` | Subdued text on light sections |

**Teal on light sections** uses a darker variant: `#059c85`

---

## Fonts

- **Typeface:** [Inter](https://fonts.google.com/specimen/Inter) — loaded from Google Fonts
- **Weights used:** 300, 400, 500, 600, 700, 800, 900
- **Icon library:** Phosphor Icons (Bold style, CDN)

### Type scale

| Element | Size | Weight | Notes |
|---|---|---|---|
| `h1` | `clamp(2.8rem, 5.5vw, 5.2rem)` | 800 | Italic `em` in teal |
| `h2` | `clamp(1.9rem, 3.5vw, 2.9rem)` | 800 | Italic `em` in teal |
| CTA `h2` | `clamp(2rem, 4vw, 3.2rem)` | 800 | |
| Section labels | `0.68rem` | 700 | Uppercase, letter-spacing `.18em`, teal |
| Body / descriptions | `0.95rem` | 400 | Line-height 1.75 |
| Buttons | `0.82–0.88rem` | 600 | |
| Nav links | `0.82rem` | 500 | |

---

## Company Info (Footer)

- **Locations:** São Paulo, Brazil & Somerset West, Cape Town, South Africa
- **Phone:** +55 11 99205-7443
- **Domain context:** `vyager.com.br`

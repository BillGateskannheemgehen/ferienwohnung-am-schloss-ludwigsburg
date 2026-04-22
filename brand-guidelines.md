# Ferienwohnung am Schloss Ludwigsburg — Brand Guidelines
## Reverse-Engineered from: https://www.ferienwohnung-am-schloss-ludwigsburg.de
## CSS Source: https://u.jimcdn.com/cms/o/scb58beaea0e27c39/layout/dm_a2ba871db2f6b71147b8a4341e3cc2f2/css/layout.css

---

## 1. Color Palette

### Primary Colors
| Role | Hex | RGB | Usage |
|:---|:---|:---|:---|
| Primary Blue | #3689b2 | rgb(54, 137, 178) | Links, buttons, CTAs (Jimdo default) |
| Deep Blue | #1e4d64 | rgb(30, 77, 100) | Hover state for buttons and links |
| Green Accent | #367714 | rgb(54, 119, 20) | H2 headings, tertiary CTAs |
| Gold/Yellow | #c09100 | rgb(192, 145, 0) | Link hover color in content |

### Neutral Colors
| Role | Hex | Usage |
|:---|:---|:---|
| Background | #fafafa | Main section background |
| Content Card | #fdfdfd | White content box background |
| Navigation BG | rgba(255,255,255,0.9) | Semi-transparent white nav bar |
| Footer | #6da7de | Steel blue footer background |
| Body Text | #444 | Main content text color |
| Muted/Sidebar | #666 | Sidebar text color |
| Borders | #999 | Section borders, dividers |
| Dark Overlay | rgba(51,51,51,0.5) | Navigation overlay on desktop |

### Brand Accent Colors
| Role | Hex | Usage |
|:---|:---|:---|
| Sidebar Yellow | #ffda5b | Sidebar background box (flex-background-options) |
| Footer Blue | #6da7de | Footer background |
| Lime Accent | #c6e070 | Button hover border/text on dark BG |

### Gradient Usage
- No gradients used. The site relies on flat colors with transparency overlays.
- Navigation bar: `rgba(255, 255, 255, 0.9)` — white semi-transparent
- Background areas use `rgba(51, 51, 51, 0.5)` for dark overlays on nav

---

## 2. Typography

### Font Families
| Role | Font | Weight(s) | Source |
|:---|:---|:---|:---|
| Headlines (H1) | Source Sans Pro | Bold (700) | Google Fonts (via fonts.jimstatic.com) |
| Headlines (H2) | Source Sans Pro | Bold (700) | Google Fonts |
| Headlines (H3) | Source Sans Pro | Bold (700) | Google Fonts |
| Body Text | Source Sans Pro | Regular (400) | Google Fonts |
| Navigation | Source Sans Pro | Bold (700) | Google Fonts |
| Fallback | "Helvetica Neue", Helvetica, Arial, sans-serif | 300 | System |
| Sidebar | Source Sans Pro | Regular (400) | Google Fonts |

### Type Scale (from CSS)
| Element | Size | Weight | Transform | Color |
|:---|:---|:---|:---|:---|
| H1 | 48px (38px on site) | Bold | UPPERCASE | #000 |
| H2 | 32px (30px on site) | Bold | none | #367714 (green) |
| H3 | 24px (on site) | Bold | none | #000 |
| Body | 20px | Regular | none | #444 |
| Nav Links | 20px | Bold | UPPERCASE | #000 |
| Sidebar | 28px | Regular | none | #000 |
| Footer | 16px | Regular | none | #fff |
| Small/Caption | 13px | Regular | none | – |

### Notes
- H1 is uppercase, centered
- H2 is green (#367714), centered, not uppercase
- Line height: 1.5 for body text
- All font sizes use both px and rem units

---

## 3. Logo Usage

- **Primary logo:** Site title text used as logo ("Ferienwohnung am Schloss Ludwigsburg")
- **Logo type:** Text/Wordmark only — no graphic icon or emblem detected
- **Logo font:** Source Sans Pro, Bold
- **Logo color:** #ffffff (white) — displayed over the map background header
- **Background usage:** Used on the dark/image header area
- **Logo file:** No separate image logo file detected — title is CSS text

> [!NOTE]
> The site does not use a graphical logo. The brand identity relies entirely on the text title. A logo should be created for the redesign.

---

## 4. Visual Style

### Photography Style
- **Background/Hero:** Aerial street-map view of Ludwigsburg (not a photo, but a map tile)
- **Apartment images:** Interior shots showing furnished rooms (warm lighting, residential feel)
- **Style:** Functional/informational — photos show the spaces clearly rather than aspirationally styled
- **Color treatment:** Natural, no heavy filtering

### Iconography
- No custom icon set detected
- Google Maps embed used for location
- No SVG icons or custom illustration system

### Spacing & Layout Patterns
- **General feel:** Moderate — not overly tight or airy
- **Layout pattern:** Fixed-width sidebar (29% on desktop) + main content (68%) + small gutter — classic 2-column blog/info layout
- **Max content width:** 1280px
- **Section dividers:** Horizontal borders `1px solid #999`
- **Section padding:** 40px bottom per section
- **Content card:** 20px internal padding with subtle box shadow

### UI Components Observed
- **Buttons:** Rounded corners (border-radius: 2–4px), flat color fill, 200ms transition
- **Cards/Content box:** White (`#fdfdfd`) background, subtle perspective shadow effect, border-radius: 2px
- **Navigation:** Semi-transparent white bar (rgba 90%), sticky/fixed at top, desktop horizontal + mobile hamburger
- **Sidebar:** Fixed 29% width on desktop, stacks below on mobile. Yellow background box (#ffda5b) for contact info
- **Forms:** Simple input fields with 1px solid #e0e0e0 border, 10px padding
- **Gallery:** Uses Jimdo's built-in gallery slider/lightbox (bxSlider)

---

## 5. Tone of Voice

- **Formality:** Semi-formal (polite German "Sie" form)
- **Person:** Direct address ("Wir bieten Ihnen..." / "Nehmen Sie...")
- **Language:** German only
- **Key phrases / taglines:**
  - "Ferienwohnungen am Schloss Ludwigsburg"
  - "Zentrale Lage"
  - "Komfortabel eingerichtet"
  - "In der Nähe des Residenzschlosses"
- **Overall impression:** Practical and friendly small-business voice. Content is informational and welcoming but not particularly polished or aspirational. Focused on location benefits and practical features (parking, proximity to train station).

---

## 6. Assessment & Improvement Notes

### Strengths of Current Brand
- Clear contact information prominently displayed in sidebar
- Consistent color usage (yellow sidebar, blue footer)
- Simple, functional navigation
- Location advantage is communicated (castle/Schloss nearby)
- Pricing is transparent and easy to find

### Weaknesses / Opportunities
- **No graphical logo** — purely text-based, no brand mark or icon
- **Jimdo platform limitations** — generic template, indistinguishable from thousands of other Jimdo sites
- **No hero imagery** — the map background is functional but not emotionally evocative
- **Typography is dated** — Source Sans Pro is clean but uninspiring for a hospitality brand
- **Yellow sidebar (#ffda5b) feels arbitrary** — not connected to any luxury or warmth concept
- **No social proof** — no reviews, testimonials, star ratings, or booking platform badges
- **No online booking** — only contact form; no calendar or instant booking
- **Mobile experience is basic** — Jimdo's responsive adaptation is functional but not optimized
- **Photos appear low-res or non-aspirational** — typical owner-taken photos vs. professional staging
- **SEO is weak** — minimal meta descriptions, no structured data for vacation rentals

### Recommended Direction for Redesign
- **New color palette:** Shift from cold blue to warm, inviting tones — consider deep cream/ivory backgrounds with a warm gold (#C9A84C) accent and forest green (#2D5016) to evoke Baroque castle gardens and the region's nature
- **New typography:** Pair a serif display font (e.g., Playfair Display, Cormorant Garamond) for headings with Source Sans Pro or Inter for body — creates a premium boutique hotel feel
- **Hero section:** Replace map background with a stunning full-screen photo of Schloss Ludwigsburg with overlay text
- **Add social proof:** Booking.com / Airbnb star ratings, guest quote testimonials
- **Logo design:** Create a simple wordmark or icon combining castle silhouette + apartment/home motif
- **Card layout for apartments:** Replace linear text list with visual grid cards showing apartment photos, key amenities icons, and price-per-night
- **Booking CTA:** More prominent call-to-action, ideally linked to a booking calendar (Smoobu, Lodgify, or direct Airbnb/Booking links)
- **Gallery:** Full-screen masonry or slider galleries for each apartment showing professional interior photos

# Frasers Hospitality UX Research & Redesign 2024

A UX research and design project conducted by **PSYKHE** for Frasers Hospitality headed by its Digital Marketing Team and Lead, aimed at improving website engagement and driving direct bookings.

---

## Live preview

https://mengliang10.github.io/frasers-hospitality-UX2024/

Published by `.github/workflows/pages.yml` on every push to `main` (Settings → Pages → Source: GitHub Actions).

---

## Typography system

The prototype uses **Manrope** for clear body copy, forms and navigation, with **DM Serif Display** for editorial hospitality headlines. Each page loads `css/typography.css` after its own embedded styles to ensure consistent typography across every section.

- Body text: **16px baseline**, with extended descriptions generally **17px** (previously 14px).
- Editorial headlines: responsive **34–66px** scale; cards and supporting headings use a smaller hierarchy.
- Form input text: **16px minimum**, reducing auto-zoom on mobile browsers.
- Navigation, labels and footer copy are enlarged, while mobile layouts retain breakpoint adjustments.
- Both families have system fallbacks. Google Fonts loading is optional for basic functionality.

## Background

Frasers Hospitality's website had not been revamped since 2022. This project was commissioned to identify friction points across the user journey and provide actionable design recommendations to increase revenue, membership sign-ups, and overall user experience.

**Mission statement:**
> "How might we better engage visitors on the Frasers Hospitality website so that we can help drive user engagement and conversion?"

---

## Research Methodology

A 14-week mixed-methods study across four research streams:

| Stream | Details |
|--------|---------|
| Analytics deep-dive | Google Analytics, Microsoft Clarity, Adobe Analytics |
| Stakeholder survey | N=64 respondents |
| Stakeholder workshops | Corporate and cluster stakeholders |
| Usability tests | N=8 participants (non-Fraser World members; UK, EUR, USA, SG, AUS nationalities) tested at Capri by Fraser Changi City |

---

## Business KPIs

Four themes guided the research and recommendations:

- **Revenue top-line improvement** — conversions, ease of booking, abandonment rate, cross/upsell, repeat customers, offer discovery
- **Fraser World membership** — member benefits discovery, sign-up rate, form completion
- **Increase mind share** — SEO traffic, eDM open rates
- **User experience** — mobile loading speed

---

## Key Findings: 6 Overarching Issues

1. Key content is hidden
2. Comparing between options is difficult
3. Navigation is cumbersome
4. Information provided misaligns with user needs
5. Booking journeys are unintuitive
6. Forms are lengthy and tedious

---

## Recommendations by User Journey Stage

### Stage 1 — Awareness

| Page | Issues | Recommendations |
|------|--------|----------------|
| Homepage | Hidden value props, weak Fraser World banner | Highlight direct booking benefits above the fold; redesign offers/property sections; redesign Fraser World banner |
| Property Homepage | Long text, hidden address, rooms section too far down | Design for scannability; show address upfront; move Rooms section higher; improve masthead |
| Extended Stay | Dense intro, unclear CTA, vague minimum stay | Concise value prop; single "Enquire" CTA; clarify minimum stay duration |
| City Guide / Explore | Scattered content, hidden CTAs | Integrate pages; improve organisation; add canonical tags for SEO |

### Stage 2 — Consideration

| Page | Issues | Recommendations |
|------|--------|----------------|
| Locations | Limited info, no brand context | Show images and prices upfront; add brand introduction pane |
| Offers | Low discoverability, insufficient content | Grid view; combine all offers; add filters and descriptors; show stay dates |
| Room Listing & Detail | Long intro, poor comparison, disorganised amenities | Reduce intro; highlight key features and price upfront; categorise amenities; add video/360° tour |
| Booking Engine | Inconsistent formatting, hard to compare rates | Standardise room details; clarify rate differences; reduce number of rates shown |
| Navigation (all pages) | Excessive clicks, non-functional icons, difficult to go back | Redesign icon components; remove repetitive pages; standardise nav bar; add breadcrumbs |
| FH25 Campaign | Confusing mechanics, misleading visuals | Creative components to explain mechanics; use more generic campaign imagery |
| Business Travel | Dense content, uninspiring design | Shorten intro; visually appealing redesign with clear benefits section |
| Facilities Listing | Dense content, poor organisation, minimal info upfront | Shorten intro; add categories; show facility details upfront |
| Booking Engine (no availability) | Uninformative error states, no alternatives suggested | Custom error states; suggest alternative properties or room types |

### Stage 3 — Conversion

| Page | Issues | Recommendations |
|------|--------|----------------|
| Offer Details | Unfamiliar booking path (checkbox), hidden Book Now CTA | Standardised booking path; pre-fill promo codes; make CTAs visible |
| Booking Engine | Fraser World pop-up disrupts booking flow; unclear member rates | Clearly indicate member rates; integrate sign-up into checkout flow instead of blocking pop-up |
| Forms (Fraser World, Extended Stay, Business Travel) | Too many fields, unintuitive error states | Remove unnecessary fields; add real-time inline error validation |

---

## Summary of Recommendations by KPI Theme

### Revenue Top-Line Improvement
- Highlight direct booking benefits on the home page
- Standardise booking paths across the site (especially via offer details pages)
- Show prices and images on the locations page to aid comparison
- Define primary CTAs clearly on Extended Stay and Business Travel pages
- Clarify rate/package differences in the booking engine
- Introduce engaging content on the home page to reduce abandonment
- Indicate member rates clearly so non-members don't click them by accident
- Incorporate Fraser World sign-up into the checkout flow
- Suggest alternative properties when current search has no availability
- Display a larger volume of offers with search and quick filters

### Fraser World Membership
- Redesign the Fraser World banner on the home page
- Front-load member benefits on the Fraser World page
- Remove unnecessary form fields to reduce sign-up friction
- Add intuitive real-time error states to all forms

### Increase Mind Share (SEO)
- Repurpose SEO-friendly copy into new visual components (preserve keywords without sacrificing design)
- Integrate Explore pages' content into City Guides; use canonical tags to de-duplicate

### User Experience (Mobile Loading Speed)
- Use JPG format; max image size 2MB; resolution 72ppi
- Use an image optimisation tool for all uploads
- Implement lazy loading on long pages (e.g. offers listing)

---

## Other Points of Discussion

- **Pop-ups and sticky banners** — raised as "overwhelming" and "against Google guidelines" by stakeholders and usability test participants alike; recommend reviewing and reducing frequency
- **Fraser World Account** — post-login experience needs improvement: points-to-next-tier visibility, gift card redemption in non-USD currencies
- **Potential new pages** — "SHOP" (corporate site), "GIFTS" (corporate site), "EXPERIENCES" (property site)

---

## Deliverables

### High-Fidelity Mobile Design Screens (35 screens)
Covers the following pages, with before/after comparisons where applicable:

| Category | Screens |
|----------|---------|
| Homepage | Current state + PSYKHE recommendation (mobile & desktop) |
| Property Homepage | Redesigned masthead, navigation, and rooms section |
| Room Listing & Detail | Key features upfront, categorised amenities |
| Offer Detail | Standardised booking path, visible CTA |
| Extended Stay | Concise value prop, single CTA |
| Business Travel | Shortened intro, visual benefits section |
| FW Form (Fraser World Sign-Up) | Reduced fields, inline validation |
| Property Facilities | Categorised listing with upfront details |
| City Guide | Integrated Explore content, improved organisation |
| Global Sales / FH25 Campaign | Clearer campaign mechanics |
| 404 Page | Helpful alternatives and navigation options |

---

## Prototype build notes

- Images are optimised JPGs (about 15.5 MB of PNGs reduced to the figure in the commit), in line with the mobile-speed recommendation above.
- Images below the masthead use native lazy loading.
- Every page has a meta description and a canonical URL, a skip link, and a keyboard-accessible menu button.
- Pages stay `noindex` while this is a prototype.

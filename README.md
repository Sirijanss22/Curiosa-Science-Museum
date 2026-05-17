# Curiosa Science Museum

An interactive science museum website for children aged 7–15 and families with young children. Built for Semester Project 1 at Noroff School of Technology and Creative Industries.

## Live Site

[curiosa-science-museum.github.io](https://sirijanss22.github.io/Curiosa-Science-Museum/)

## Project Links

| Resource | Link |
|---|---|
| Live site | https://sirijanss22.github.io/Curiosa-Science-Museum/ |
| Figma design & prototype | https://www.figma.com/design/pnSkBUCA3GZN7H7S1s17Qn/CSM-%E2%80%94-Design-System---Prototype |
| GitHub Projects planning board | https://github.com/users/Sirijanss22/projects/2 |
| GitHub repository | https://github.com/Sirijanss22/Curiosa-Science-Museum |

## About the Project

Curiosa Science Museum is a fully responsive, multi-page website designed to inspire children and families to visit an interactive science museum. The site features six exhibition zones, a full events calendar, visit planning information, membership options, a school group booking section, and an animated robot mascot named Sparky.

The name *Curiosa* comes from the Latin *curiositas* — curiosity. It is designed to be memorable, easy for children to say, and to feel like a real institution.

## Pages

| Page | File | Description |
|---|---|---|
| Home | `index.html` | Hero, exhibition cards, events preview, Young Stars membership, school visits, newsletter |
| Exhibitions | `pages/exhibitions.html` | All 6 interactive zones with gallery |
| Events | `pages/events.html` | Full calendar, workshops, special evenings |
| Visit Us | `pages/visit.html` | Opening hours, ticket prices, accessibility, getting here, FAQ |
| Get Involved | `pages/get-involved.html` | Membership plans, school visits, volunteering, donations |
| Contact | `pages/contact.html` | Accessible contact form and museum info |
| Sparky Mascot | `pages/sparky-mascot.html` | Animated SVG robot mascot with 6 moods |
| Coming Soon | `pages/coming-soon.html` | Placeholder for JS-dependent features (booking, payments) |

## Tech Stack

- Pure HTML5 — semantic markup throughout
- Pure CSS3 — custom properties, Flexbox, CSS Grid
- No JavaScript frameworks
- No CSS frameworks (no Bootstrap, no Tailwind)
- SVG for the Curiosa logo, icon mark, and Sparky mascot
- Google Fonts: Fredoka (display) and Nunito (body)

## Accessibility

- WCAG 2.1 AA compliant
- Skip-to-content link on every page
- Descriptive alt text on all images
- Sufficient colour contrast ratios throughout
- Keyboard navigable with visible `:focus-visible` states
- ARIA labels on all navigation, landmark, and interactive elements
- `aria-live` region on Sparky mascot for screen reader mood announcements
- `prefers-reduced-motion` support for all CSS animations
- Semantic HTML document outline on every page

## SEO

Every page has a unique `<title>`, unique `<meta name="description">`, and unique `<h1>`.

## Images

Photography sourced from [Unsplash](https://unsplash.com) and used free of charge under the [Unsplash License](https://unsplash.com/license). All images compressed to under 200KB using [Squoosh](https://squoosh.app).

**Photographers:** Andy Holmes, Sara Cottle, Solstice Hannan, CHUTTERSNAP, Vitaly Gariev, fan yang, Ryan Zazueta, Tofan Teodor, David Clode, James Lee.

## Project Structure

```
curiosa-science-museum/
├── index.html
├── css/
│   └── styles.css
├── images/
│   ├── curiosa-logo.svg
│   ├── curiosa-icon.svg
│   ├── hero-galaxy.jpg
│   ├── hero-exhibit.jpg
│   ├── trex-museum.jpg
│   ├── test-tubes.jpg
│   ├── science-lab.jpg
│   ├── dino-skeleton.jpg
│   ├── coloured-tubes.jpg
│   ├── dino-milan.jpg
│   ├── fossil.jpg
│   └── dino-teeth.jpg
└── pages/
    ├── exhibitions.html
    ├── events.html
    ├── visit.html
    ├── get-involved.html
    ├── contact.html
    ├── sparky-mascot.html
    └── coming-soon.html
```

## Running Locally

No build step required.

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/curiosa-science-museum.git
   ```
2. Open `index.html` in your browser — that's it.

## Copyright & Licensing

© 2025 Siri Jansson. All original code, design, and written content in this repository is the work of the author.

Photography sourced from [Unsplash](https://unsplash.com) and used free of charge under the [Unsplash License](https://unsplash.com/license).

Fonts (Fredoka, Nunito) served via Google Fonts under the [SIL Open Font License](https://scripts.sil.org/OFL).

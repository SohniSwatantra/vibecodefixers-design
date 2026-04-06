# VibeCodeFixers - Landing Page Design

Design prototype for [vibecodefix.com](https://vibecodefixers.com) — an expert developer network that connects vibe-coders with professionals who fix, secure, and optimize their code.

## Preview

Two versions of the landing page:

| Version | File | Description |
|---------|------|-------------|
| **Dark Mode** | `dark-mode.html` | Nosana-inspired dark theme with green accents |
| **Light Mode** | `light-mode.html` | Light theme with pink tint (`#ffe6ff`) and green accents |

Open `index.html` to choose between them.

## Design System

### Brand Colors

| Color | Hex | Usage |
|-------|-----|-------|
| Primary Green | `#10E80C` (dark) / `#0CB608` (light) | CTAs, accents, highlights |
| Light Green | `#4DFF4A` | Hover states |
| Banner Border | `#d9ffb3` | Featured In banner |
| Featured Badge | `#ff8000` | Orange accent for press mentions |
| Pink Tint | `#ffe6ff` | Light mode background warmth |

### Typography

- **Headings:** Space Grotesk (400-700)
- **Body:** Open Sans (400, 600, 700)

### Animations

- Scroll-triggered reveal (IntersectionObserver)
- 3-panel demo section with looping 14s animation cycle
- SVG circuit-board line art with animated green traces
- Code editor illustration with bug/fix visualization
- Counter animations for stats
- Pulsing green dots on circuit endpoints
- CI/CD pipeline flow animation (Deployment card)
- Shield checkmark draw animation (Security card)

## Sections

1. **Featured In topbar** — 404 Media press mention
2. **Navigation** — Graphite-style (logo | center links | CTA buttons)
3. **Hero** — Headline + SVG code editor illustration with circuit traces
4. **3-Panel Demo** (CodeRabbit-style) — Submit Problem > Analysis > Expert Match
5. **As Seen In** — Hacker News, Futurism, 404 Media, Indeed, MIT Technology Review
6. **Featured Experts** — Horizontal scrollable cards (8 real experts)
7. **Why Choose VibeCodeFixers** — Bug Fixing, Security Analysis, Deployment (animated SVG graphics)
8. **Testimonials** — 3 real client testimonials
9. **How It Works** — 4-step process cards
10. **Join Expert Network** — CTA with logo image
11. **FAQ** — Expandable accordion (5 questions)
12. **Community** — Discord + Reddit links
13. **Footer** — Contact info, navigation

## Project Structure

```
.
├── index.html                  # Landing page selector (dark/light)
├── dark-mode.html              # Full landing page — dark theme
├── light-mode.html             # Full landing page — light theme
├── 404.html                    # Under construction page
├── branding-guide.md           # Brand system documentation
├── Marketing images/           # Logo images for As Seen In section
│   ├── hackernews.png
│   ├── futurism.png
│   ├── 404media.png
│   ├── indeed.png
│   ├── mit-tech-review.png
│   └── vibecodefixers-logo.png
├── Brand Assets Nosana/        # Nosana brand reference (colors, fonts, logos)
└── vibecodefixer logo/         # Additional logo assets
```

## Deployment

Static HTML — no build step required.

**Netlify:** Connect this repo, set publish directory to `/`, no build command.

All links use `javascript:void(0)` — this is a design prototype, so no pages are broken.

## Design Inspiration

- [Nosana](https://nosana.com) — Color palette, typography, dark theme, circuit-board graphics
- [Graphite](https://graphite.com) — Navigation bar layout
- [CodeRabbit](https://coderabbit.ai) — 3-panel animated demo section
- [Alpic](https://alpic.ai) — Dark mode card treatments

## Tech Stack

Pure HTML + CSS + vanilla JS. No frameworks, no dependencies, no build tools.

---

Built for VibeCodeFixers by Swatantra Sohni

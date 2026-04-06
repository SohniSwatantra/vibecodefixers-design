# VibeCodeFixers Branding Guide
## Based on Nosana Design System

**Name:** VibeCodeFixers
**Tagline:** Fix. Secure. Optimize.

---

## Typography

| Role | Font | Weights |
|------|------|---------|
| **Headings** | Space Grotesk | 400, 500, 600, 700 |
| **Body / UI** | Open Sans | 400 (Regular), 600 (Semibold), 700 (Bold) |

Space Grotesk for all headings, stats, logo text, section labels.
Open Sans for body text, buttons, nav links, descriptions.

---

## Brand Colors (Nosana Palette)

### Greens
| Name | Hex | Usage |
|------|-----|-------|
| Brand 100 | `#10E80C` | Primary accent, CTAs (dark mode), highlights |
| Brand 200 | `#4DFF4A` | Hover states, light green accent |
| Brand 300 | `#0CB608` | Primary accent (light mode), darker green for text-on-white |

### Neutrals
| Name | Hex | Usage |
|------|-----|-------|
| Brand 100 | `#FFFFFF` | White text on dark |
| Brand 200 | `#B5B5B5` | Secondary text (dark mode) |
| Brand 300 | `#7A7A7A` | Tertiary text |
| Brand 400 | `#555555` | Secondary text (light mode) |
| Brand 500 | `#2A2A2A` | Elevated backgrounds (dark) |
| Brand 600 | `#1F1F1F` | Card backgrounds (dark) |
| Brand 700 | `#141414` | Primary card/section bg (dark), primary text (light) |
| Brand 800 | `#090909` | Deepest background (dark), headline text (light) |

---

## Dark Mode Palette

| Role | Value |
|------|-------|
| Page background | `#0A0A0A` |
| Section alternate | `#0F0F0F` |
| Card background | `#141414` |
| Card hover | `#1A1A1A` |
| Elevated surface | `#1F1F1F` |
| Primary text | `#FFFFFF` |
| Secondary text | `#B5B5B5` |
| Tertiary text | `#7A7A7A` |
| Accent | `#10E80C` |
| Accent hover | `#4DFF4A` |
| Green muted bg | `rgba(16, 232, 12, 0.08)` |
| Green border | `rgba(16, 232, 12, 0.2)` |
| Card border | `rgba(255,255,255,0.06)` |
| Divider border | `rgba(255,255,255,0.08)` |

## Light Mode Palette

| Role | Value |
|------|-------|
| Page background | `#FAFAFA` |
| Section alternate | `#FFFFFF` |
| Card background | `#FFFFFF` |
| Card hover | `#F7F7F7` |
| Elevated surface | `#F3F3F3` |
| Primary text | `#141414` |
| Secondary text | `#555555` |
| Tertiary text | `#7A7A7A` |
| Accent | `#0CB608` |
| Accent hover/dark | `#098806` |
| Green soft bg | `rgba(12, 182, 8, 0.08)` |
| Green border | `rgba(12, 182, 8, 0.2)` |
| Card border | `rgba(0,0,0,0.06)` |
| Divider border | `rgba(0,0,0,0.08)` |

---

## Button Styles

### Primary CTA
- Rounded rectangle (`border-radius: 8px`)
- Dark mode: `#10E80C` bg, black text, hover `#4DFF4A`
- Light mode: `#0CB608` bg, white text, hover `#098806`
- Includes `>>` arrow icon in a subtle inset box
- Hover: lift -1px + green glow shadow

### Outline / Secondary
- Rounded rectangle, transparent bg
- Border: `rgba(255,255,255,0.14)` (dark) / `rgba(0,0,0,0.14)` (light)
- Hover: green-tinted border + soft green background

### Small Buttons (cards)
- Same 8px radius
- `btn-sm-green`: solid green
- `btn-sm-ghost`: transparent with border
- `btn-sm-accent`: green muted bg with green border

---

## Border Radius

| Token | Value | Usage |
|-------|-------|-------|
| `r-sm` | 8px | Buttons, inputs, icons, small cards |
| `r-md` | 12px | Medium containers |
| `r-lg` | 16px | Cards, panels |
| `r-xl` | 24px | Large sections, CTA blocks |
| `r-full` | 9999px | Badges, pills, counters |

---

## Shadow System

### Dark Mode
- Card: `0 1px 2px rgba(0,0,0,0.4)`
- Glow (hover): `0 0 20px rgba(16, 232, 12, 0.08)`

### Light Mode
- Small: `0 1px 2px rgba(0,0,0,0.04)`
- Card: `0 1px 3px rgba(0,0,0,0.04), 0 4px 16px rgba(0,0,0,0.03)`
- Large: `0 8px 32px rgba(0,0,0,0.06)`
- Glow: `0 0 20px rgba(12, 182, 8, 0.1)`

---

## Design Patterns (from Nosana)

- **Frosted-glass navbar** with backdrop blur
- **Pill badges** with borders for tags/labels (e.g., "How It Works", "Ecosystem Stats")
- **4-column stats row** with vertical dividers between items
- **Cards** with 1px borders, subtle shadows, green-glow on hover
- **Green dot** with glow animation for "live" indicators
- **Dot grid patterns** (radial-gradient) on visual/hero sections
- **Radial green glow** behind hero and CTA sections
- **Dark CTA block** even in light mode (uses `#141414` bg)
- **`>>` arrow buttons** matching Nosana's "Learn More >>" pattern

---

## Logo Usage

- **Text logo format:** "Vibe" in green + "CodeFixers" in primary text color
- **On dark backgrounds:** "Vibe" = `#10E80C`, "CodeFixers" = `#FFFFFF`
- **On light backgrounds:** "Vibe" = `#0CB608`, "CodeFixers" = `#141414`
- **Icon:** Wrench-in-braces `{🔧}` — white on dark, dark on light
- **Tagline:** "Fix. Secure. Optimize." in tertiary text color below logo
- **Join visual block** always uses dark background regardless of mode

---

## Files

| File | Description |
|------|-------------|
| `dark-mode.html` | Full landing page — Nosana dark theme |
| `light-mode.html` | Full landing page — Nosana light theme (inverted) |
| `branding-guide.md` | This file |

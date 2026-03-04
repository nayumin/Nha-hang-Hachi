# Refine Hachi UI Plan

## Phase 1: Discovery
[✓] Completed. User chose:
1. Palette: Keep current pink/strawberry (#ff6b81)
2. Style: Scrapbook / Kawaii
3. Tech: Custom CSS

## Phase 2: Design Commitment
🎨 **DESIGN COMMITMENT (Scrapbook / Kawaii)**

- **Style:** Scrapbook / Kawaii. Overlapping "paper" elements, tape/sticker aesthetics, wavy/dashed borders, playful and bouncy animations.
- **Topological Choice:** Fragmenting the layout into distinct "cards" or "polaroids" scattered on a desk, rather than a single centered `.overlay`.
- **Palette:** 
  - `pink-soft: #ffebee`
  - `pink-light: #fff0f5`
  - `pink-medium: #ffc1cc`
  - `pink-dark: #ff99ac`
  - `strawberry: #ff6b81`
  - `text-dark: #4a2c3d`
- **Typography:** Rounded, friendly serif or display fonts for headings, highly legible sans for body. (Will import an appropriate Google Font like 'Nunito' or 'Mali').
- **Effects/Motion:** 
  - Elements rotated slightly off-axis for a "tossed on a desk" look.
  - Hover effects: Pull elements straight (rotate to 0deg), scale up, and deepen shadow to simulate picking up a card.
  - "Tape" elements visually holding sections together.
- **Cliché Liquidation:** Breaking out of the single centered column. No glassmorphism. No bento grids. Pure tactile, crafty scrapbook feel.

## Phase 3: Implementation
- [ ] Import playful fonts.
- [ ] Redesign `.overlay` into scattered semantic `<article>` or `<section>` cards.
- [ ] Apply CSS variables and background dots/seamless pattern.
- [ ] Build the Menu table to look like a hand-written receipt or a pinned note.
- [ ] Add bouncy micro-interactions.

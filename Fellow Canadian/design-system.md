# Fellow Canadian — Design System

## Inspiration
Apostrophe REPS (apostrophereps.com) — editorial, typographic, bold but warm. Red and cream. Big numbers. Clean grid. Wit lives in the words, not the design.

---

## Colour

| Name | Hex | Usage |
|------|-----|-------|
| Cream | `#F4EFE4` | Page background |
| Red | `#D42B1E` | Headlines, accents, CTA borders, occasional full sections |
| Near-black | `#1A1A1A` | Body text |
| Mid-grey | `#777777` | Labels, captions, secondary text |
| Light grey | `#999999` | Eyebrow text, decorative |
| Red (muted border) | `rgba(192,40,28,0.2)` | Dividers, subtle lines |

**Rule:** Red is for typography and accents. Cream is the canvas. Black is for reading. Never use red as a full-page background except for deliberate contrast sections.

---

## Typography

| Role | Font | Size | Weight | Style |
|------|------|------|--------|-------|
| Logo / Nav | Arial | 13px | 700 | Uppercase, 2px letter-spacing |
| Eyebrow | Arial | 11px | 400 | Uppercase, 2.5px letter-spacing, #999 |
| Headline | Georgia (serif) | 56px desktop / 36px mobile | 700 | Red, tight line-height 1.08 |
| Subhead | Georgia (serif) | 20px | 400 | Italic, near-black |
| Body | Arial | 16px | 400 | Near-black, line-height 1.7 |
| Stat number | Georgia (serif) | 40–48px | 700 | Red |
| Stat label | Arial | 11–12px | 400 | Uppercase, letter-spacing 1px, #777 |
| Nav links | Arial | 12px | 400 | Uppercase, letter-spacing 1px, #555 |
| CTA button | Arial | 13px | 700 | Uppercase, letter-spacing 1.5px |

---

## Buttons

**Primary CTA:** Outline style — red border (2px), red text, cream/transparent background. On hover: fill red, cream text.

```css
.cta-btn {
  display: inline-block;
  background: transparent;
  color: #C0281C;
  border: 2px solid #C0281C;
  padding: 14px 32px;
  font-size: 13px;
  font-weight: 700;
  letter-spacing: 1.5px;
  text-transform: uppercase;
  cursor: pointer;
  transition: background 0.2s, color 0.2s;
}
.cta-btn:hover {
  background: #C0281C;
  color: #F4EFE4;
}
```

**Secondary / On red background:** Cream border, cream text. On hover: fill cream, red text.

---

## Spacing & Layout

- Max content width: 1200px, centered
- Page padding (desktop): 48px horizontal
- Page padding (mobile): 24px horizontal
- Section vertical padding: 72px top / 64px bottom
- Grid gap: 48px

---

## Components

### Nav
- Logo left (uppercase, red, letter-spaced)
- Links right (uppercase, grey, letter-spaced)
- Bottom border: `1px solid rgba(192,40,28,0.2)`

### Eyebrow
- Small dot (8px, red, circle) + uppercase label
- Used to open sections before the headline

### Stat Block
- Left border: `2px solid #C0281C`
- Large number (Georgia, red)
- Small label below (Arial, uppercase, grey)

### Section Divider
- `1px solid rgba(192,40,28,0.2)`
- Or a full-width red rule `2px solid #C0281C` for stronger breaks

### Section Colour Rule
- **Hero (Section 1):** Red background `#C0281C`, cream text `#F4EFE4`. Nav also red.
- **All other sections:** Cream background `#F4EFE4`, red headlines, near-black body text.
- The contrast between hero and the rest does the heavy lifting — do not repeat full red sections unless for a very deliberate CTA block at the end.

---

## Tone Rules (Design)
- Wit lives in the words. Design stays clean and warm.
- No hard lines, no black backgrounds, no aggressive typography treatments.
- Big numbers are editorial, not infographic.
- White space is not wasted space.
- No rounded corners — this is not a tech startup.
- No shadows, no gradients, no decorative icons.

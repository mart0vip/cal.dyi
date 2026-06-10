
# Minimalist Clinical Design System
Version: 1.0  
Style: Quiet Luxury / Clinical Minimalism / Scandinavian Influence

---

## 1. Principles

- Clean, structured, and minimal
- No visual noise or decorative elements
- Strong hierarchy through spacing and typography
- Neutral palette with restrained accent usage
- Clinical but human (soft, calm, precise)

---

## 2. Color System

### Tokens

```css
--color-bg-primary: #eae5e1;
--color-bg-secondary: #f7f9ff;

--color-text-primary: #595150;
--color-text-secondary: #919d9d;

--color-accent: #2E4953;

--color-border: rgba(89,81,80,0.15);
```

### Usage Rules

- Backgrounds: 70–80% (primary + secondary)
- Text & structure: 10–20%
- Accent: max 15%
- Avoid pure black (#000000)
- Avoid saturated or bright colors

---

## 3. Typography

### Fonts

- Primary: Bebas Neue (headings only)
- Secondary: Inter (or similar sans-serif)

### Scale

| Element | Size | Notes |
|--------|------|------|
| H1 | 56–64px | Uppercase, spaced |
| H2 | 40–48px | Uppercase |
| Body Large | 18px | |
| Body Base | 16px | Default |
| Small | 14px | Secondary text |

### Rules

- Max 2 font weights
- Headings: uppercase only
- Letter spacing (Bebas Neue): +2% to +6%
- Keep text concise (no long paragraphs)

---

## 4. Spacing System

Base unit: 8px

| Token | Value |
|------|------|
| XS | 8px |
| SM | 16px |
| MD | 24px |
| LG | 40px |
| XL | 64px |
| XXL | 96px |

### Rules

- Prefer spacing over dividers
- Maintain consistent vertical rhythm
- Sections should breathe (≥ 64px padding)

---

## 5. Layout Grid

- Max width: 1200–1320px
- Columns: 12
- Gutter: 24px

### Rules

- Align everything to grid
- Avoid overlapping elements
- Use whitespace instead of containers when possible

---

## 6. Buttons

### Primary

- Background: var(--color-accent)
- Text: var(--color-bg-primary)
- Border radius: 8–12px
- No shadow

### Secondary (Ghost)

- Background: transparent
- Border: 1px solid var(--color-border)
- Text: var(--color-text-primary)

### Interaction

- Hover: slight opacity change
- No heavy animations

---

## 7. Cards

### Style

- Background: slightly lighter than page
- Border: 1px solid var(--color-border)
- Radius: 12–16px
- Padding: 24–32px

### Rules

- No shadows
- No gradients
- Keep content minimal (icon + title + short text)

---

## 8. Forms

### Inputs

- Style: underline OR subtle border (not both)
- Background: transparent or very light

### States

- Focus: accent color
- Error: muted/desaturated red

### Labels

- Small
- Optional uppercase

---

## 9. Icons

- Style: line icons only
- Stroke: 1.5px–2px
- Sizes: 24px / 32px grid
- Colors: monochrome or duotone

### Rules

- No filled icons (unless necessary)
- Maintain consistent stroke and style

---

## 10. Dividers

- 1px line
- Low contrast (var(--color-border))

### Rule

- Use sparingly
- Prefer spacing instead

---

## 11. Data & Dashboard

### Tables

- No heavy borders
- Use spacing for separation

### Charts

- Neutral base colors
- Single accent highlight

### Labels

- Small caps or muted tone

---

## 12. Composition Guidelines

- Balanced and structured layouts
- Clear section separation
- Editorial / medical document style

### Rules

- Avoid clutter
- Avoid decorative elements
- Avoid heavy visual effects (shadows, gradients, 3D)

---

## 13. Tone & Mood

- Professional
- Calm
- Trustworthy
- Precise

### Avoid

- Playful or cartoon styles
- Bright colors
- Visual noise
- Overlapping elements

---

## 14. Implementation Constraints (Important)

- Accent color must remain <15% of UI
- Bebas Neue must not be overused
- Spacing consistency is mandatory
- No shadows or gradients unless explicitly approved
- All components must follow grid and spacing system

---

## 15. Component Summary

- Buttons: Primary / Ghost
- Cards: Minimal, bordered
- Forms: Clean, understated
- Icons: Line-based
- Layout: Grid-driven
- Sections: Spacing-defined

---

## 16. Design Philosophy (TL;DR)

Restraint over expression.  
Clarity over decoration.  
Structure over creativity.

The system should feel invisible but precise.

# Electric Bold Prompt Pack

Based on the [VOLTARA](https://horizonx.so/product/voltara) design concept.

## Visual Foundation

```
Color System:
- Background: #050505
- Surface: #0A0A0A
- Elevated: #111111
- Hover: #181818
- Border: rgba(255, 255, 255, 0.08)

Text:
- Primary: #FFFFFF
- Secondary: rgba(255, 255, 255, 0.7)
- Muted: rgba(255, 255, 255, 0.4)
- On accent: #000000

Accent: #00E5FF (electric cyan)
Accent alt: #7C3AED (violet for secondary emphasis)
Gradient: linear-gradient(135deg, #00E5FF, #7C3AED)

Typography:
- Headlines: 'Space Grotesk' or 'Plus Jakarta Sans', sans-serif — weight 700-800
- Body: 'Inter', sans-serif — weight 400
- Mono: 'JetBrains Mono' — for code/technical
- Scale: 12px, 14px, 16px, 20px, 28px, 40px, 56px, 72px
- Hero headings: tight tracking (-0.03em), tight leading (0.95)

Spacing: 8px grid
Border radius: 12px (cards), 8px (buttons/inputs), 9999px (pills)
```

## Component Rules

```
Cards:
- bg #0A0A0A, border rgba(255,255,255,0.08)
- Border radius: 12px
- On hover: border transitions to accent at low opacity rgba(0,229,255,0.3)
- Gradient border effect on featured cards: border-image with accent gradient

Buttons:
- Primary: gradient background (cyan→violet), text black, font-bold
- Secondary: bg transparent, border accent, text accent
- Ghost: text secondary, hover text primary
- All: 8px radius, 150ms transition
- Primary hover: subtle glow — box-shadow 0 0 20px rgba(0,229,255,0.3)

Glow effects (use sparingly):
- Accent elements: box-shadow 0 0 30px rgba(0,229,255,0.15)
- Active states: box-shadow 0 0 15px rgba(0,229,255,0.25)
- Never on body text or backgrounds — only on interactive accent elements

Typography effects:
- Gradient text on hero headings: background linear-gradient(135deg, #00E5FF, #7C3AED), -webkit-background-clip text
- Use on ONE heading per viewport max

Code blocks:
- bg #0A0A0A, border rgba(255,255,255,0.08)
- Syntax highlighting: cyan for keywords, violet for strings, white for identifiers
- JetBrains Mono 13px

Badges:
- Accent: bg rgba(0,229,255,0.1), text #00E5FF, border rgba(0,229,255,0.3)
- Pill shape (9999px)
```

## Page Templates

### Product Page
```
Build a product page for [product name], a [one-line description].

Visual: electric dark UI. Background #050505. Electric cyan (#00E5FF) accent.
Gradient highlights cyan→violet. Bold geometric typography (Space Grotesk).
Tight tracking (-0.03em) on headings.

Hero section: Full viewport height. Gradient text headline (56-72px).
Subheadline in secondary text (18px). Two CTAs side by side: primary
(gradient bg, black text) and secondary (outline, cyan border+text).
Below: product mockup or 3D render, centered, with subtle cyan glow
underneath (radial gradient).

Feature section: 3-column grid on dark surface (#0A0A0A).
Each card: icon (24px, cyan), title (20px, bold, white),
description (14px, secondary). Cards have subtle border that
shifts to cyan on hover.

Technical specs: full-width dark card (#0A0A0A). 4-column grid
of metric blocks. Each: number (40px, gradient text), label (12px,
uppercase, muted). Separated by thin vertical dividers.

CTA section: gradient border card (cyan→violet). Large heading (40px),
single gradient button, centered.

Responsive: single column mobile, reduce hero text ~40%, stack feature cards.
```

### Developer Tool Landing
```
Build a landing page for [tool name], a developer tool that [description].

Visual: electric dark with code-forward aesthetic. Background #050505.
Cyan accent. Monospace highlights (JetBrains Mono).

Hero: Split. Left: headline (48px, tight), subtext (16px, secondary),
CTA button (gradient), and "npm install [package]" code snippet
(bg #0A0A0A, mono font, cyan text, with copy button). Right: animated
terminal or code editor mockup with syntax-highlighted code.

Features: alternating rows (text left / code right, then flipped).
Each row: label (12px, uppercase, cyan), title (28px, bold),
description (16px), and a code example or terminal screenshot.

Integrations strip: logo grid showing compatible tools/frameworks.
Logos in white at 40% opacity, hover to full white. 6 across.

Open source CTA: "Star on GitHub" section. GitHub star count badge,
repo link, contributor avatars.

Footer: dark (#050505), border-top rgba(255,255,255,0.06).
Minimal: logo, docs link, GitHub link, Discord link.
```

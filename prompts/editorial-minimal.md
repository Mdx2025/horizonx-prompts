# Editorial Minimal Prompt Pack

Based on the [Hemlt](https://horizonx.so/product/hemlt) design concept.

## Visual Foundation

```
Color System:
- Background: #FAFAF9 (warm white)
- Surface: #FFFFFF
- Surface alt: #F5F5F4
- Border: #E7E5E4
- Border subtle: #F0EEEC

Text:
- Primary: #1C1917 (warm black)
- Secondary: rgba(28, 25, 23, 0.6)
- Muted: rgba(28, 25, 23, 0.4)
- Caption: rgba(28, 25, 23, 0.35)

Accent: #1C1917 (text color as accent — editorial restraint)
Link: #1C1917 with underline, underline-offset-2

Typography:
- Headlines: 'Playfair Display', Georgia, serif — weight 700
- Body: 'Inter', system-ui, sans-serif — weight 400, line-height 1.75
- Labels: 'Inter', system-ui, sans-serif — weight 600, letter-spacing 0.15em, uppercase
- Scale: 12px (caption), 14px (body-sm), 16px (body), 18px (body-lg), 24px (h3), 32px (h2), 48px (h1), 64px (display)

Spacing: generous — 80px between sections, 48px between groups, 24px between elements
Border radius: 0px (sharp) or 2px max — editorial, not rounded
```

## Component Rules

```
Section Headers:
- Label above: 12px, uppercase, tracking-[0.2em], text-muted, font-semibold
- Title: serif, 32-48px, font-bold, text-primary, tight leading (1.1)
- Optional description: 16px, text-secondary, max-width 540px

Cards:
- No background, no border, no shadow
- Content separated by whitespace and typography hierarchy
- Image + text stack, not boxed

Links:
- Text color, underline, underline-offset-2px
- Hover: text-secondary
- No color accent — underline IS the affordance

Images:
- Full bleed or within content column
- No border radius (0px — editorial crop)
- Optional subtle shadow for floating images

Buttons:
- Primary: bg #1C1917, text white, px-8 py-3
- Secondary: bg transparent, border #1C1917, text #1C1917
- No border radius (0px) or 2px max
- Font: 13px, uppercase, tracking-wider, font-semibold

Dividers:
- 1px solid #E7E5E4
- Used as section separators
- Full width with generous margin (40px+)
```

## Page Templates

### Landing Page
```
Build a landing page for [product/brand].

Visual style: editorial minimal. Warm white background (#FAFAF9).
Serif headings (Playfair Display), sans-serif body (Inter).
No border radius anywhere. Generous spacing (80px+ between sections).
Black and white palette with subtle warm undertones.

Sections:
1. Hero: Large serif headline (64px) left-aligned, 2-line max. Subheadline (18px, sans-serif, text-secondary) below. CTA button (black, no radius, uppercase, tracking-wider). Right side: editorial photograph, no radius, slight shadow.

2. Feature strip: 3 columns. Each has a label (12px, uppercase, tracking-wider, text-muted), a serif title (24px), and body text (16px, text-secondary). No icons — typography carries the weight.

3. Full-width image break: Edge-to-edge photograph or product shot. No padding.

4. Testimonial: Large serif quote (32px, italic), attribution below (14px, uppercase). Centered, max-width 680px.

5. CTA section: Centered. Serif headline (48px), description (16px), black button. Separated by thin rule above.

6. Footer: Minimal. Logo left, 3-4 link groups center, social icons right. Thin border-top.

Responsive: single column on mobile, reduce headline sizes by ~30%, maintain spacing proportions.
```

### Portfolio / Case Study
```
Build a case study page for [project name].

Editorial layout: single column, max-width 720px body, full-width images break out.

Header: label (12px, uppercase, "Case Study"), title (48px serif), metadata row (client, year, role — 13px, text-muted, separated by middots).

Body: alternating text blocks and full-width images. Text in 16px Inter, generous line-height (1.75). Pull quotes in 28px serif italic, indented left with a thin left border (#E7E5E4).

Image treatment: no radius, full viewport width on desktop. Caption below in 12px, text-muted, italic.

Results section: 3 large metrics in a row (48px serif numbers, 12px label below each). Subtle background #F5F5F4.

Navigation: "Previous / Next" case study links at bottom, serif titles, with arrow indicators.
```

# horizonx-prompts

AI prompts that generate premium-quality UI. Tested with Cursor, v0, Lovable, and Claude.

![License](https://img.shields.io/badge/license-MIT-blue)

## What is this?

A curated collection of AI prompts designed to generate production-quality user interfaces. Each prompt pack captures a specific visual language — color system, typography, spacing, component patterns — so you can consistently reproduce premium design across different projects.

## Prompt Packs

### Dark Analytics (Mosk Style)
Precision analytics dashboard with dark surfaces, gradient accents, and modular card system.

**Use for:** SaaS dashboards, analytics platforms, admin panels, data-heavy interfaces.

→ [prompts/dark-analytics.md](prompts/dark-analytics.md)

### Editorial Minimal (Hemlt Style)
Clean editorial layout with generous whitespace, serif headings, and high-contrast photography.

**Use for:** Landing pages, portfolios, editorial sites, marketing pages.

→ [prompts/editorial-minimal.md](prompts/editorial-minimal.md)

### Electric Bold (Voltara Style)
High-energy dark interface with electric accent colors, bold typography, and layered depth.

**Use for:** Product pages, SaaS marketing, tech-forward brands, developer tools.

→ [prompts/electric-bold.md](prompts/electric-bold.md)

## How to Use

### With Cursor
```
Open your component file → Cmd+K → paste the prompt → iterate
```

### With v0
```
Paste the prompt → generate → use "refine" to iterate
```

### With Lovable
```
Start a new project → paste the prompt as your first instruction
```

### With Claude / ChatGPT
```
Include the prompt as context → describe what you want to build
```

## Prompt Structure

Each prompt pack includes:

1. **Visual Direction** — color palette, typography, spacing system
2. **Component Rules** — border radius, shadows, hover states, transitions
3. **Layout Templates** — ready-to-use prompts for common page types
4. **Quality Markers** — specific instructions that push output from "generic" to "premium"

## Example

Here's what a prompt from the Dark Analytics pack looks like:

```
Build an analytics dashboard for a fintech platform.

Visual: Dark UI, background #0D0D0D, surface cards #141414, elevated #1E1E1E.
Accent: indigo-500 (#6366F1) for interactive elements only.
Typography: Inter for UI, JetBrains Mono for numbers. Sizes: 11px labels,
14px body, 24px primary metrics, 32px hero numbers.

Layout: No sidebar. Top bar (logo left, search center, avatar right).
4-column KPI strip full width. Below: 8/4 grid — chart area left,
activity feed right. Bottom: full-width data table.

KPI Cards: title (11px, uppercase, tracking-wider, text-muted),
value (24px, font-bold, tabular-nums), trend badge (green positive,
red negative, 10px). Cards have 20px padding, 16px radius, no border.

Table: header row bg-[#0F0F0F], 13px uppercase tracking-wider.
Row hover bg-[#1A1A1A]. Alternating subtle backgrounds. Inline
action buttons on hover only.

Interaction: 150ms transitions. Cards lift 2px on hover.
Focus rings: 2px accent with 2px offset on dark background.
Loading: skeleton screens matching exact card dimensions.
```

## Premium Concepts

These prompts are derived from design concepts published on [HorizonX](https://horizonx.so). Each concept is a complete visual language with dozens of production-ready patterns.

Browse all concepts → [horizonx.so/explore](https://horizonx.so/explore)

## Contributing

Found a prompt that consistently produces great results? Submit a PR.

## License

MIT

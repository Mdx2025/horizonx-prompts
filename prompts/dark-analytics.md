# Dark Analytics Prompt Pack

Based on the [Mosk](https://horizonx.so/product/mosk) design concept.

## Visual Foundation

```
Color System:
- Background: #0D0D0D
- Surface (cards): #141414
- Elevated surface: #1E1E1E
- Hover surface: #262626
- Border: rgba(255, 255, 255, 0.06)
- Border hover: rgba(255, 255, 255, 0.12)

Text:
- Primary: #F0F0F0
- Secondary: #A0A0A0
- Muted: #666666
- On accent: #FFFFFF

Accent: #6366F1 (indigo-500)
Accent hover: #818CF8 (indigo-400)

Semantic:
- Success: #22C55E
- Warning: #F59E0B
- Error: #EF4444
- Info: #3B82F6

Typography:
- UI: Inter, system-ui, sans-serif
- Data/Numbers: JetBrains Mono, ui-monospace, monospace
- Scale: 10px (micro), 11px (label), 13px (small), 14px (body), 16px (large), 20px (heading), 24px (metric), 32px (hero)

Spacing: 4px grid (4, 8, 12, 16, 20, 24, 32, 40, 48, 64)
Border radius: 8px (small), 12px (medium), 16px (large), 9999px (pill)
```

## Component Rules

```
Cards:
- Background: #141414, no border by default
- Padding: 20px
- Border radius: 16px
- Hover: bg shifts to #1E1E1E, subtle border appears rgba(255,255,255,0.06)
- Transition: 200ms ease

Buttons:
- Primary: bg #6366F1, hover #818CF8, text white
- Secondary: bg #1E1E1E, hover #262626, text #F0F0F0
- Ghost: bg transparent, hover rgba(255,255,255,0.06), text #A0A0A0
- Height: 36px (sm), 40px (md), 48px (lg)
- Border radius: 8px
- Focus ring: 2px #6366F1, 2px offset on #0D0D0D

Tables:
- Header: bg #0F0F0F, text 11px uppercase tracking-wider #666666
- Rows: bg transparent, hover #141414
- Cell padding: 12px 16px
- Borders: bottom only, rgba(255,255,255,0.04)
- Numbers: tabular-nums, right-aligned
- Actions: visible on row hover only

Badges:
- Pill shape (9999px radius)
- Success: bg #22C55E/10, text #22C55E
- Semantic colors at 10% opacity background, full color text

Charts:
- Grid lines: rgba(255,255,255,0.04)
- Axis labels: 10px, #666666
- Data colors: use accent + semantic palette
- Tooltips: bg #1E1E1E, border rgba(255,255,255,0.12), shadow
```

## Page Templates

### Dashboard
```
Build a [domain] analytics dashboard.

Layout: Full width, no sidebar. Top bar with logo left, global search center, user avatar + notification bell right. Below the bar: 4-column KPI strip spanning full width. Main area: 8-column chart panel left, 4-column sidebar right (activity feed or quick stats). Bottom: full-width sortable data table with pagination.

[Insert Visual Foundation from above]

KPI cards show: metric label (11px, uppercase, tracking-wider, #666666), current value (24px, font-bold, tabular-nums, #F0F0F0), trend badge (pill, green/red for positive/negative, 10px).

The chart should be a line/area chart with gradient fill fading to transparent. Use the accent color for the primary series.

Table columns: [list your columns]. Headers are sticky. Rows highlight on hover. Include a search input above the table and a "per page" dropdown.

All monetary values: tabular-nums, right-aligned, formatted with commas.
Loading states: skeleton screens matching exact component dimensions.
```

### Settings Page
```
Build a settings page for [product].

Layout: 240px sidebar left with section navigation (stacked links, active state = bg #141414 + accent text). Main area right with form sections separated by subtle dividers (rgba(255,255,255,0.06)).

[Insert Visual Foundation from above]

Sections: Profile, Notifications, Billing, Security, API Keys, Danger Zone.

Each section: heading (16px, font-semibold, #F0F0F0), description (13px, #A0A0A0), then form fields.

Inputs: full width, bg #141414, border rgba(255,255,255,0.12), 40px height, 14px text. Focus: ring accent. Error: border #EF4444.

Save button sticky at bottom right. Show "unsaved changes" indicator when form is dirty.

Danger zone: red-tinted card (bg rgba(239,68,68,0.05), border rgba(239,68,68,0.2)) with destructive actions.
```

### Login Page
```
Build a login page for [product].

Layout: Split screen. Left 50%: dark gradient background (#0D0D0D to #141414) with centered login form (max-width 380px). Right 50%: full-bleed product screenshot or abstract pattern.

[Insert Visual Foundation from above]

Form: logo at top, "Welcome back" heading (20px, #F0F0F0), "Sign in to your account" subtext (13px, #A0A0A0). Email input, password input with show/hide toggle, "Remember me" checkbox + "Forgot password?" link on same line. Primary sign-in button full width. Divider "or continue with". Social buttons (Google, GitHub) in a row, outline style.

Bottom: "Don't have an account? Sign up" text (13px, centered).

Responsive: on mobile, hide the right panel, login form goes full width with padding.
```

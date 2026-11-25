---
name: Swiss Mathematical
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1b1b1b'
  on-surface-variant: '#424656'
  inverse-surface: '#303030'
  inverse-on-surface: '#f1f1f1'
  outline: '#737688'
  outline-variant: '#c3c5d9'
  surface-tint: '#0052de'
  primary: '#004aca'
  on-primary: '#ffffff'
  primary-container: '#005fff'
  on-primary-container: '#eff0ff'
  inverse-primary: '#b4c5ff'
  secondary: '#435ba3'
  on-secondary: '#ffffff'
  secondary-container: '#99b0ff'
  on-secondary-container: '#284188'
  tertiary: '#9d2d00'
  on-tertiary: '#ffffff'
  tertiary-container: '#c73c01'
  on-tertiary-container: '#ffede8'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174c'
  on-primary-fixed-variant: '#003daa'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#00174c'
  on-secondary-fixed-variant: '#294289'
  tertiary-fixed: '#ffdbd0'
  tertiary-fixed-dim: '#ffb59e'
  on-tertiary-fixed: '#3a0b00'
  on-tertiary-fixed-variant: '#842500'
  background: '#f9f9f9'
  on-background: '#1b1b1b'
  surface-variant: '#e2e2e2'
  data-red: '#CC0000'
  data-green: '#007700'
  data-orange: '#FF7700'
typography:
  display-lg:
    fontFamily: JetBrains Mono
    fontSize: 70px
    fontWeight: '800'
    lineHeight: '1.05'
  display-lg-mobile:
    fontFamily: JetBrains Mono
    fontSize: 36px
    fontWeight: '800'
    lineHeight: '1.1'
  headline-lg:
    fontFamily: JetBrains Mono
    fontSize: 28px
    fontWeight: '800'
    lineHeight: '1.1'
  headline-md:
    fontFamily: JetBrains Mono
    fontSize: 18px
    fontWeight: '700'
    lineHeight: '1.3'
  formula-lg:
    fontFamily: JetBrains Mono
    fontSize: 13.5px
    fontWeight: '700'
    lineHeight: '1.65'
  body-md:
    fontFamily: JetBrains Mono
    fontSize: 12.5px
    fontWeight: '400'
    lineHeight: '1.65'
  table-header:
    fontFamily: JetBrains Mono
    fontSize: 11.5px
    fontWeight: '700'
    lineHeight: '1.4'
    letterSpacing: 0.04em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.08em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10.5px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.18em
  caption-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '400'
    lineHeight: '1.4'
spacing:
  gutter: 1.875rem
  margin: 3.75rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies a minimalist Swiss editorial and technical aesthetic tailored for mathematical presentations, academic lectures, and data-dense analytical viewers. It targets educators, researchers, engineers, and students who require absolute clarity, zero visual distraction, and high-precision information hierarchy.

The emotional response is one of intellectual rigor, calm authority, and structural precision. By stripping away decorative gradients, shadows, and ornamental chrome, the interface foregrounds the content—equations, diagrams, and tabular data—with museum-grade typographic discipline.

The visual language draws from **Minimalism** and **Swiss International Style**:
- **Strict Monochromatic Foundation:** A pure white canvas (`#FFFFFF`) paired with deep ink black (`#000000`) for structural rules, dividers, and primary text.
- **Surgical Accentuation:** A single electric cobalt blue (`#005FFF`) directs attention to slide titles, active states, and primary mathematical concepts, supported by a subtle ice-blue tint (`#EEF3FF`) for formula callouts and row highlights.
- **Uncompromising Flatness:** Zero drop shadows, zero blurs, and sharp `0px` corners establish a crisp, architectural grid.

## Colors

The color system is built on a high-contrast light mode (`#FFFFFF` canvas, `#000000` ink) with a single electric cobalt primary (`#005FFF`).

- **Primary (`#005FFF`):** Reserved for slide headings, primary interactive states (button hover fills, progress bar), active badges, and primary mathematical curves or root nodes.
- **Primary Tint (`#EEF3FF`):** Derived from the primary hue, used for formula box backgrounds, table row hover states, and highlighted structural regions.
- **Neutral (`#000000`):** Used for primary body text, heavy structural borders (`3px` header rules), table headers, and dark-mode navigation chrome (`#111111` viewport/nav bar). Grayscale steps (`#333333` through `#E8E8E8`) handle secondary labels, muted notes, and hairline table/grid dividers.
- **Named Data Accents:** `data-red` (`#CC0000`), `data-green` (`#007700`), and `data-orange` (`#FF7700`) are strictly reserved for multi-series mathematical plots, number line points, and interval differentiation. They must never be used for general UI chrome.

## Typography

`JetBrains Mono` serves as the sole typeface across all levels, uniting prose, tabular data, UI controls, and inline SVG mathematical diagrams under a single monospaced voice.

- **Hierarchy through Weight & Case:** Because the typeface is monospaced, hierarchy is established through stark weight contrasts (`400` regular vs. `700`/`800` bold), uppercase transformations with wide tracking (`0.08em` to `0.18em`) for labels, and color shifts (`#005FFF` for headings, `#000000` for body, `#888888`–`#999999` for notes).
- **Responsive Scaling:** On desktop presentation canvases (`1280×720`), `display-lg` scales to `70px`. On compact mobile viewports, `display-lg-mobile` (`36px`) prevents horizontal overflow while preserving the bold hero presence.

## Layout & Spacing

The layout philosophy uses a **fixed-aspect-ratio canvas (`1280px × 720px`)** that scales proportionally to fit any viewport, ensuring exact typographic and diagram alignment across projectors, desktops, and tablets.

- **Slide Framing:** Each slide maintains generous outer margins (`60px` / `3.75rem` horizontal, `40px` / `2.5rem` top, `32px` / `2rem` bottom) to isolate content from the viewport edge.
- **Grid & Columns:** Multi-column content uses a `30px` (`1.875rem`) gutter (`gutter`) to separate text, formula blocks, and SVG diagrams cleanly.
- **Rhythm:** Component-level spacing follows a tight, predictable scale—`space-xs` (`4px`) for badge/list micro-gaps, `space-sm` (`8px`) for table cell padding and list item separation, `space-md` (`16px`) for formula box padding, and `space-lg` (`24px`) for header-to-content separation.
- **Mobile Adaptation:** When rendered outside the scaled presentation frame on mobile (`< 768px`), outer margins collapse to `1rem` (`space-md`) and multi-column rows stack vertically with `space-lg` gaps.

## Elevation & Depth

This design system is **strictly flat (2D)**. Depth and visual hierarchy are never communicated through drop shadows, blurs, or Z-axis elevation.

- **No Shadows:** `box-shadow` and `backdrop-filter` are prohibited across all components.
- **Structural Borders & Tonal Contrast:** Hierarchy is achieved through border weight (`3px solid #000000` for slide headers, `4px solid #005FFF` for formula callouts, `1px solid #E8E8E8` for table rows) and surface contrast (`#FFFFFF` slide canvas against `#111111` navigation chrome, `#EEF3FF` highlight blocks).
- **Watermark Layering:** Oversized background numerals and mathematical symbols sit behind primary content at `0.04` opacity with `pointer-events: none`, adding architectural depth without interfering with legibility.

## Shapes

The shape language is **Sharp (`0px` radius)**. Every HTML container—slides, formula boxes, buttons, badges, and tables—uses crisp `90°` corners to reinforce the Swiss editorial grid.

The only permitted exception is within inline SVG mathematical diagrams (such as tree nodes and concept maps), where a minimal `2px`–`3px` corner radius (`rx="2"` or `rx="3"`) may be applied to soften dense node clusters.

## Components

- **Buttons (`.nbtn`):** Sharp `0px` radius, `2px solid #FFFFFF` border, `#FFFFFF` background with `#000000` uppercase `11px` bold text. On hover, transitions (`0.15s`) to `#005FFF` background and border with `#FFFFFF` text.
- **Formula & Callout Boxes (`.fx`):** Sharp `0px` radius, `#EEF3FF` background, `4px solid #005FFF` left accent border (or `#CC0000` for cautionary/contrast formulas), `10px 15px` padding, and `13.5px` bold `JetBrains Mono` text.
- **Tables:** Full-width with `0px` radius. Headers (`thead th`) use `#000000` background with `#FFFFFF` `11.5px` bold text. Body cells (`tbody td`) use `6.5px 13px` padding, `1px solid #E8E8E8` bottom borders, `#F7F7F7` zebra striping on even rows, and `#EEF3FF` on row hover.
- **Badges (`.badge`):** Sharp `0px` radius, `2px 10px` padding, `10px` uppercase bold text with `0.1em` letter-spacing. Uses `#000000` or `#005FFF` solid fills with `#FFFFFF` text.
- **Lists (`.list`):** Unstyled lists using geometric `▶` bullets in `#005FFF` with `9px` gap and `6px` bottom margin between items.
- **Input Fields & Checkboxes/Radios:** When used in interactive extensions, maintain `0px` radius, `1.5px solid #000000` borders, `#FFFFFF` fill, and `#005FFF` focus/checked states with `#EEF3FF` active backgrounds.
- **Progress Bar (`.prog`):** `3px` height track in `#333333` with `#005FFF` fill, transitioning smoothly (`0.3s`) across slide changes.
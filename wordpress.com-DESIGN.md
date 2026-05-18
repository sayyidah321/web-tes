# Design System Inspired by WordPress.com

## 1. Visual Theme & Atmosphere

This design system embodies a clean, modern, and accessible approach to web building. The interface prioritizes clarity and focus, using a minimal color palette to guide user attention toward primary actions. The loading state presented reflects a calm, professional demeanor—communicating stability and trust during critical moments. Helvetica Neue's geometric precision combined with restrained color choices creates an interface that feels both contemporary and timeless, emphasizing content and function over decoration.

**Key Characteristics**
- Minimal color palette with high contrast for accessibility
- Geometric, humanist typography prioritizing readability
- Generous whitespace for breathing room and focus
- Flat design with subtle interactive elements
- Professional, trustworthy aesthetic suited to website creation
- Clear hierarchy guiding user actions and attention

## 2. Color Palette & Roles

### Primary
- **Dark Charcoal** (`#111516`): Primary text, headings, and dominant UI elements; establishes visual hierarchy and ensures readability across the interface.

### Accent Colors
- **Electric Indigo** (`#3F58E0`): Primary call-to-action elements, interactive links, and accent highlights; conveys action and draws focus to key interactions.

### Interactive
- **Link Active** (`#3F58E0`): Default link color with 700 weight font; maintains consistency across navigational and inline links.
- **Link Hover** (`#2A3BA8`): Darker shade derived from accent for hover states; inferred to provide visual feedback during interaction.

### Neutral Scale
- **Off White** (`#FFFFFF`): Primary background, card surfaces, and container fills; ensures clean, minimal aesthetic.
- **Light Gray** (`#F5F5F5`): Secondary background for subtle differentiation; used sparingly for secondary surfaces.
- **Medium Gray** (`#999999`): Supporting text and secondary labels; inferred for visual hierarchy below primary text.

### Surface & Borders
- **Border Light** (`#E5E5E5`): Subtle dividers and borders; inferred to provide definition without visual clutter.
- **Background Surface** (`#FFFFFF`): Default page and container backgrounds maintaining clarity.

## 3. Typography Rules

### Font Family
**Primary:** `Helvetica Neue, Helvetica, Arial, sans-serif`
**Fallback:** `system-ui, -apple-system, sans-serif`

### Hierarchy

| Role | Font | Size | Weight | Line Height | Letter Spacing | Notes |
|------|------|------|--------|-------------|-----------------|-------|
| Display / H1 | Helvetica Neue | 32px | 500 | normal | 0px | Page titles and hero content; establishes primary visual entry point |
| Heading / H2 | Helvetica Neue | 24px | 600 | 1.4 | 0px | Section headers; maintains hierarchy below H1 |
| Heading / H3 | Helvetica Neue | 20px | 600 | 1.3 | 0px | Subsection headers and component titles |
| Body | Helvetica Neue | 16px | 400 | 1.5 | 0px | Default paragraph and content text |
| Body Small | Helvetica Neue | 14px | 400 | 1.5 | 0px | Supporting text and descriptions; inferred for secondary content |
| Button | Helvetica Neue | 16px | 600 | normal | 0px | Interactive button labels; inferred from link weight |
| Link | Helvetica Neue | 16px | 700 | normal | 0px | Inline and navigation links; bold weight ensures visibility |
| Caption | Helvetica Neue | 12px | 400 | 1.4 | 0px | Fine print, timestamps, and helper text; inferred |
| Code | `Monaco, Courier, monospace` | 13px | 400 | 1.6 | 0px | Inline and block code; monospace fallback stack |

### Principles
- **Hierarchy through weight and scale:** Use size and weight changes to establish visual priority; avoid overuse of both simultaneously.
- **Readability first:** Maintain minimum 1.4 line-height for body text to ensure comfortable reading on all screen sizes.
- **Contrast and accessibility:** All body text should meet WCAG AA minimum contrast ratios against background colors.
- **Consistent baseline:** Align typography to a 4px baseline grid for visual rhythm and consistency.

## 4. Component Stylings

### Buttons

**Primary Button**
```
background-color: #3F58E0
color: #FFFFFF
padding: 12px 24px
border-radius: 4px
border: 0px none
font-size: 16px
font-weight: 600
font-family: Helvetica Neue
box-shadow: none
transition: all 0.2s ease
```

**Primary Button Hover**
```
background-color: #2A3BA8
cursor: pointer
```

**Primary Button Active**
```
background-color: #1A2578
```# Design System Inspired by WordPress.com

## 1. Visual Theme & Atmosphere

This design system embodies a clean, professional digital

**Secondary Button**
```
background-color: #FFFFFF
color: #111516
padding: 12px 24px
border-radius: 4px
border: 1px solid #E5E5E5
font-size: 16px
font-weight: 600
font-family: Helvetica Neue
box-shadow: none
transition: all 0.2s ease
```

**Secondary Button Hover**
```
background-color: #F5F5F5
border-color: #D0D0D0
cursor: pointer
```

**Ghost Button**
```
background-color: transparent
color: #3F58E0
padding: 12px 24px
border-radius: 4px
border: 0px none
font-size: 16px
font-weight: 600
font-family: Helvetica Neue
box-shadow: none
transition: all 0.2s ease
```

**Ghost Button Hover**
```
background-color: rgba(63, 88, 224, 0.08)
cursor: pointer
```

### Cards & Containers

**Card Default experience centered around clarity, trust, and accessibility. Drawing from WordPress.com's security-conscious brand identity, the aesthetic is minimalist and purposeful, with a focus on reassurance during critical user interactions. The visual language prioritizes legibility and calm through generous whitespace, a restrained color palette, and straightforward typography. The overall mood is welcoming yet authoritative—acknowledging user concerns while maintaining confidence in the platform's reliability. This is reflecte**
```
background-color: #FFFFFF
border-radius: 8px
border: 1px solid #E5E5E5
padding: 24px
box-shadow: 0 2px 8px rgba(0, 0, 0, 0.04)
```

**Card Elevated**
```
background-color: #FFFFFF
border-radius: 8px
border: none
padding: 24px
box-shadow: 0 4px 16px rgba(0, 0, 0, 0.08)
```

**Container Full Width**
```
background-color: #FFFFFF
width: 100%
padding: 40px 0
margin: 0
```

### Inputs & Forms

**Text Input Default**
```
background-color: #FFFFFF
color: #111516
font-size: 16px
font-family: Helvetica Neue
padding: 12px 16d in the use of soft neutral backgrounds paired with purposeful accent colors that guide attention without overwhelm.

**Key Characteristics**
- Clean, centered layouts with ample breathing room
- Neutral-first color philosophy with strategic accent placement
- High-contrast text for maximum accessibility
- Minimalist, no-flourish component design
- Professional serif-px
border-radius: 4px
border: 1px solid #E5E5E5
height: 44px
transition: all 0.2s ease
```

**Text Input Focus**
```
border-color: #3F58E0
box-shadow: 0 0 0 3px rgba(63, 88, 224, 0.1)
outline: none
```

**Text Input Error**
```
border-color: #DC3545
background-color: #FFF8F8
```

**Label**
```
color: #111516
font-size: 14px
font-weight: 600
font-family: Helvetica Neue
margin-bottom: 8px
display: block
```

### Navigation

**Navigation Link Default**
```
colorinfluenced typography hierarchy
- Trust-building visual language for security contexts

## 2. Color Palette & Roles

### Primary
- **Dark Charcoal** (`#111516`): Primary text, headings, and dominant UI surfaces. Used extensively across the interface for structural hierarchy and readability.
- **Off-White/Background** (`#FFFFFF`): Clean canvas for content areas. Default background supporting dark text for optimal contrast.

### Accent Colors
- **Electric Blue** (`#3F58E0`): Primary interactive elements, calls-to-action, and links. Provides visual focus and guides user attention to actionable items.

### Interactive
- **Blue Hover** (`#2E47: #111516
font-size: 16px
font-weight: 700
font-family: Helvetica Neue
text-decoration: none
padding: 8px 16px
transition: color 0.2s ease
```

**Navigation Link Hover**
```
color: #3F58E0
```

**Navigation Link Active**
```
color: #3F58E0
border-bottom: 2px solid #3F58E0
```

### Loading Spinner

**Spinner Default**
```
colorC1`): Dark: #3F58E0
width: 32px
height: 32px
border: 4px solid rgbaened blue for interactive hover states, indicating state change and interactivity.
- **Blue(63, 88, 224, 0.2)
border-top-color: #3F58E0
border-radius: 50%
animation: spin 1s linear infinite
```

## Active 5. Layout Principles

### Spacing System
Base unit: `4px`** (`#1F30A3`): Deepened blue for active/pressed states of buttons

Spacing scale:
- ` and links.

### Neutral Scale
- **Light4px` (0.25rem): Minimal gaps between t Gray** (`#F5F5F5`): Secondary backgrounds, disabled states, and subtle containers.
- **Mediumightly related elements
- `8px` (0.5rem): Compact spacing within Gray** (`#999999`): Secondary text, components
- `12px` ( helper0 text, and de-emphasized content.
- **Dark Gray** (`#333333`): Tert.75rem): Standard internal padding for inputs and buttons
- `16px` (1rem): Default spacing betweeniary text and reduced-emphasis interface elements.

### Surface & Borders
- **Subtle Border** (`#DD componentDDDD`): Light dividers and container outlines, maintaining visual separation without intrusion.

## 3. Typography Rules

### Font Family
**Primary Font Stack:** `Helvetica Neue`, Helvetica, Arial, sans-serif
**Secondary Font Stack:** System fonts: `-apple-system`, `BlinkMacSystemFont`, `Segoe UI`, Roboto, sans-serif

### Hierarchy

| groups
- `24px` (1.5rem): Generous padding within cards and containers
- `32px` (2rem): Section spacing for vertical rhythm
- `40px` (2.5rem): Major container padding and large section breaks
- `48px` (3rem): Full-screen section spacing
- `132px` (8.25rem): Extra-large margin for hero and landing sections

### Grid & Container
- **Max width:** `1200px` for Role | Font | Size | Weight | Line Height | Letter Spacing | Notes |
|------|------|------|--------|-------------|----------------|-------|
| Display / H1 | Helvetica Neue | 32px | 500 | 1.2 (38.4 content containers
- **Column strategy:** 12-column flexible grid for responsive scaling
- **Gutter:** `16px` between columns; `24px` for larger layouts
- **Section patternpx) | 0px | Primary page headings; centered alignment for emphasis |
| Heading /:** Containers use full-width backgrounds with centered content at `1200px`; padding applie H2 | Helvetica Neue | 28px | 500 | 1.2 (33.6px) | 0px | Secondary headings; strong visual hierarchy |
| Heading / H3 | Helvetica Neue | 24px | 500 | 1.2 (28.8px) | 0px | Tertiary headings; section breaks |
| Body / Paragraph | Helvetica Neue | 16px | 400 | 1.5 (24px) | 0px | Standard body copy; comfortable reading length |
| Body / Small | Helvetica Neue | 14px | 400 | 1.4 (19d to outer container

### Whitespace Philosophy
Whitespace is treated as a design element rather than empty space. Generous margins and padding create breathing room around content, reducing cognitive load and directing focus. The interface favors negative space over visual density, with spacing increasing at hierarchy levels (headings receive more space above than.6px) | 0px | Secondary descriptive text; helper text |
| Link | Helvetica Neue | 16px | 700 | 1.5 (24px) | 0px | Interactive links; bold weight for distinction |
| Button / CTA | Helvetica Neue | 16px | 600 | 1 (16px) | 0px | Action-oriented text; strong visual presence |
| Caption | Helvetica Neue | 12px | 400 | 1 body text).

### Border Radius Scale
- `0px`: No radius; used for sharp, geometric elements
- `4px`: Subtle roundness for inputs, buttons, and small components; default radius for interactive elements
- `8px`: Medium roundness for cards, modals, and container blocks; bridges subtle and pronounce.3 (15.6px) | 0px | Footnotes and metadata |
| Code | `Monaco`, `Courier New`, monospace | 13px | 400 | 1.5 (19.5px) | 0px | Code snippets; system font fallback |

### Principles
- **Weight Distribution:** Use 500–d styling
- `12px`: Soft roundness for large cards and prominent containers; inferred for elevated components
- `50%`: Full circle; reserved for avatar images and loading spinners

## 6. Depth & Elevation

| Level | Treatment | Use |
|-------|-----------|-----|
| Surface (Base) | No shadow;700 weights for hierarchy; avoid extreme lightness for accessibility.
- **Line Height:** Generous line heights (1.4–1.5) promote readability and reduce cognitive load.
- **Center Alignment:** Headings in security/reassurance contexts are center-aligned for emphasis and authority.
- **Contrast First:** All text meets WCAG AA contrast standards (7:1 for dark text on light backgrounds).
- **Helvetica Heritage:** Helvetica Neue as primary maintains WordPress.com's established visual identity while remaining modern and web-safe.

## 4. Component Stylings

### Buttons

**Primary Button**
- `background-color`: `#3F58E0`
- `color`: `#FFFFFF`
- `font-size`: `16px`
- `font-weight`: `600`
- `font-family`: `Helvetica Neue`
- `padding`: `12px 24px`
- `border-radius`: `4px`
- `border`: `0px none`
- `cursor`: `pointer`
- `transition`: `all 200ms ease`
- **Hover State:** `box-shadow: none` | Flat interactive elements like inputs, ghost buttons, and default cards |
| Raised (Level 1) | `0 2px 8px rgba(0, 0, 0, 0.04)` | Standard cards, popovers, and content containers with subtle lift |
| Elevated (Level 2) | `0 4px 16px rgba(0, 0, 0, 0.08)` | Prominent cards, modals, and featured content requiring visual separation |
| Floating (Level 3) | `0 8px 24px rgba(0, 0, 0, 0.12)` | Dropdowns, tooltips, and overlay elements; maximum visual prominence |
| Maximum (Level 4) | `0 12px 32px rgba(0, 0, 0, 0.16)` | Full-screen modals and critical overlays; inferred for extreme elevation |

**Shadow Philosophy**
Shadows communicate depth and hierarchy without overwhelming the interface. Soft, diffused shadows with low opacity create subtle elevation suggesting user interaction and focus. Shadows are intentionally weak and directional to maintain the clean, minimal aesthetic; strong shadows are reserved for critical moments requiring maximum visual separation.

## 7. Do's and Don'ts

### Do
- Use the **Electric Indigo** (`#3F58E0`) consistently for all primary call-to-action buttons to maintain visual language.
- Maintain minimum touch targets of `44px × 44px` for interactive elements across all device sizes.
- Apply `Helvetica Neue` at `16px` with `line-height: 1.5` for body copy to ensure optimal readability.
- Use generous whitespace (24px–40px) between major sections to create visual rhythm and reduce cognitive load.
- Employ the shadow `background-color: #2E47C1`; `box-shadow: 0px 4px 12px rgba(63, 88, 224, 0.3)`
- **Active State:** `background-color: #1F30A3`; `transform: translateY(1px)`
- **Disabled State:** `background-color: #F5F5F5`; `color: #999999`; `cursor: not-allowed`

**Secondary Button**
- `background-color`: `#F5F5F5`
- `color`: `#111516`
- `font-size`: `16px`
- `font-weight`: `600`
- `font-family`: `Helvetica Neue`
- `padding`: `12px 24px`
- `border-radius`: `4px`
- `border`: `1px solid #DDDDDD`
- `cursor`: `pointer`
- `transition`: `all 200ms ease`
- **Hover State:** `background-color: #EEEEEE`; `border-color: #CCCCCC`
- **Active State:** `background-color: #E0E0E0`

**Ghost Button**
- `background-color`: `transparent`
- `color`: `#3F58E0`
- `font-size`: `16px`
- `font-weight`: `700`
- `font-family`: `Helvetica Neue`
- `padding`: `12px 16px`
- `border-radius`: `4px`
- `border`: `0px none`
- `cursor`: `pointer`
- `transition`: `all 200ms ease`
- **Hover State:** `color: #2E47C1`; `background-color: rgba hierarchy systematically: surface (none) → raised (Level 1) → elevated (Level 2) based on interaction priority(63, 88, 224, 0.08)`
- **Active State:** `color: #1F30A3`

### Cards & Containers

**Card (Default)**
- `background-color`: `#FFFFFF`
- `border`: `1px solid #DDDDDD`
- `border-radius`: `4px`
- `padding`: `24px`
- `box-shadow`: `0px 1px 3px rgba(0, 0, 0, 0.08)`
- **Hover State (Interactive):** `box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.12)`; `border-color: #CCCCCC.
- Test link colors against `#FFFFFF` and `#F5F5F5` backgrounds to confirm WCAG AA contrast compliance.
- Use **Dark Charcoal** (`#111516`) for all primary text; avoid pure black (`#000000`) to reduce eye strain.

### Don't
- Mix typeface weights h`

**Card (Elevated)**
- `background-color`: `#FFFFFF`
- `border`: `0px none`
- `border-radius`: `8px`
- `padding`: `32px`
- `box-shadow`: `0px 8px 24px rgba(0, 0, 0, 0.12)`

**Container (Centered)**
- `max-width`: `600px`
- `margin`: `0 auto`
- `padding`: `40aphazardly; reserve bold (`600–700`) for headings, links, and emphasis only.
- Apply shadows exceeding Level 2 (0 4px 16px) for routine components; reserve maximum elevation for critical overlays.
- Use the accent color for body text or large passages; restrict to interactivepx 20px`
- `background-color`: `#FFFFFF`

### Inputs & Forms

**Text Input (Default)**
- `background-color`: `#FFFFFF`
- `color`: `#111516`
- `font-size`: `16px`
- `font-family`: `Helvetica Neue`
- `padding`: `12px 16px`
- `border`: `1px solid #DDDDDD`
- `border-radius`: `4px`
- `transition`: `border-color 200ms ease, box-shadow 200ms ease`
- **Focus State:** `border-color: #3F58E0`; `box-shadow: 0px 0px 0px 3px rgba(63, 88, 224, 0.1)`; `outline: 0px`
- **Error State:** `border-color: #DC2626`; `background-color: #FEE2E2`
- **Disabled State:** `background-color: #F5F5F5`; `color: #999999`; `border-color: #DDDDDD`; elements and highlights.
- Set line-height below `1.4` for any body-copy typography role.
- Apply border-radius exceeding `12px` for standard UI components; reserve `50%` for circular elements only.
- Reduce padding below `8px` in interactive elements; maintain comfort for mouse and touch interaction.
- Mix multiple accent colors; `cursor: not-allowed`

**Label**
- `color`: `#111516`
- `font-size`: `14px`
- `font-weight`: `600`
- `font-family`: `Helvetica Neue`
- `margin-bottom`: `8px`
- `display`: `block`

### use only **Electric Indigo** (`#3F58E0`) for interactive states across the system.

## 8. Responsive Behavior

### Navigation

**Primary Navigation Bar**
- `background-color`: `#FFFFFF`
- `border-bottom`: `1px solid #DDDDDD`
- `padding`: `16px 20px`
- `display`: `flex`
- `align-items`: `center`
- `justify-content`: `space-between`

**Navigation Link (Default)**
- `color`: `#111516`
- `font-size`: `16px`
- `font-weight`: `400`
- `font-family`: `Helvetica Neue`
- `padding`: `8px 12px`
- `text-decoration`: `none`
- `cursor`: `pointer`
- `transition`: `color 200ms ease`
- **Hover State:** ` Breakpoints

| Breakpoint | Width | Key Changes |
|------------|-------|------------|
| Mobile | 320px–479px | Single column; padding: 12px; font-size: 14px for body; full-width inputs; stacked navigation |
| Small Tablet | 480px–767px | Single column; padding: 16px;color: #3F58E0`
- **Active State:** `color: #3F58E0`; `font-weight: 600`; `border-bottom: 2px solid #3 font-size: 16px for body; two-column grid where applicable |
| Tablet | 768px–1023px | Two-column grid; padding: 24px; font-size: 16px; horizontal navigation; optimized spacing |
| Desktop | 1024px–1439F58E0`

### Loading Indicator

**Spinner**
- `width`: `40px`
- `height`: `40px`
- `border`: `4px solid #F5F5F5`
- `border-top-color`: `#3F58E0`
- `border-radius`: `50%`
- `animation`: `spin 1s linear infinite`
- **Animation Definition:** `@keyframes spin {px | Full 12-column grid; padding: 40px; font-size: 16px; multi-row layouts; max-width: 1200px |
| Large Desktop | 1440px+ | Centered 1200px container; padding: 40px sides; extended whitespace for breathing room |

### Touch from { transform: rotate(0deg); } to { transform: rotate(360deg); } }`

### Links

**Link (Interactive)**
- `color`: `#3F58E0`
- `font-size`: `16px`
- `font-weight`: `700`
- `font-family`: `Helvetica Neue`
- `text-decoration`: `none`
- `background-color`: `transparent`
- `padding`: `0px`
- `border`: `0px none`
- `cursor`: `pointer`
- `transition`: `color 200ms ease, opacity 200ms ease`
- **Hover State:** `color: #2E47C1`; `text-decoration: underline`
- **Active State:** `color: #1F30A3`
- **Visited State:** `color: #5B5B8D`

## 5. Layout Principles

### Spacing System
**Base Unit:** `4 Targets
- **Minimum size:** `44px × 44px` for all interactive elements (buttons, links, inputs, icons).
- **Recommended minimum:** `48px × 48px` for primary actions and frequently tapped elements.
- **Safe spacing:** `8px` minimum distance between adjacent touch targets to prevent accidental interaction.
- **Hover area:** Expand touchpx`

**Spacing Scale:**
- `4px`: Minimal gaps between tightly related elements
- `8px`: Adjacent component spacing
- `12px`: Internal padding (inputs, buttons)
- `16px`: Card/container internal spacing
- `20px`: Standard horizontal target hit area by `12px` in all directions on desktop for larger interaction zones.

### Collapsing Strategy
- **Navigation:** Horizontal navigation collapses to page margins
- `24px`: Standard section padding
- `32px`: Large section spacing
- `40px`: Major section separation
- `48px`: Full page section breaks
- `64px`: Hero/display section spacing
- `80px`: Landing vertical stack at tablet breakpoint; triggered by hamburger menu icon at mobile.
- **Typography:** H1 scales from `32px` (desktop) to `28px` (tablet) to `24px` (mobile) maintaining visual hierarchy.
- **Spacing:** Margins and padding scale proportionally: `40px` → page major sections
- `132px`: Maximum spacing for emphasis

### Grid & Container
- **Max Width Container:** `1200px`
- **Standard Container:** `960px`
- **Narrow Container:** `600px` (used for trust/security messaging)
- **Column Strategy:** Flexible 12-column grid; 1 column on mobile, 2–3 columns on tablet, 3+ on desktop
- **Section Pattern:** Full-width background with max-width centered content; alternating left/right alignment for visual rhythm

### Whitespace Philosophy `32px` (tablet) → `16px` (mobile) for vertical rhythm.
- **Grid:** Flexible columns reflow from 12 → 8 → 4 → 2 → 1 column across breakpoints; gutters adjust from `24px` → `16px` → `12px`.
- **Cards & Containers:** Border-radius remains constant; padding adjusts from `24px` → `16px` → `12px` on smaller screens.
- **Inputs & Buttons:** Height remains `44px` minimum; font-size adjusts to prevent zoom on mobile; width scales to full container on small screens.

## 9. Agent Prompt Guide

### Quick Color Reference
- **Primary CTA:** Electric Indigo (`#3F58E0`) — all primary buttons, active links, accents
- **Primary Text:** Dark Charcoal (`#111516`) — headings, body copy, UI
Whitespace is treated as an active design element, not passive emptiness. Generous margins and padding create cognitive rest areas, reduce perceived complexity, and emphasize hierarchy. Center-aligned content with balanced whitespace on both sides builds visual authority. Stack vertical rhythm at 8px intervals for consistency.

### Border Radius Scale
- `0px`: Strict rectangular cards for technical contexts (code blocks, logs)
- `4px`: Standard container corners, buttons, inputs; provides subtle softness
- `8px`: Elevate labels
- **Background:** Off White (`#FFFFFF`) — primary surface, cards, containers
- **Secondary Background:** Light Gray (`#F5F5F5`) — subtle differentiation, hover states
- **Border:** Border Light (`#E5E5E5`) — dividers, input borders, card edges
- **Secondary Text:** Medium Gray (`#999999`) — supporting text, captions, disabled states; inferred

### Iteration Guide

1. **Always use `#111516` for primary text and headings** unless it isd cards, modals, and containers requiring distinction
- `12px`: Large component groups and hero containers
- `50%`: Circular avatar images and badge indicators

## 6. Depth & Elevation

| Level | Treatment | Use |
|-------|-----------|-----|
| Flat / L0 | No shadow; `box-shadow: none` | Background surfaces, disabled states, text-only content |
| Raised / L1 | `box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.08)` | Default cards, containers, standard UI elements |
| Elevated / L2 | `box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.12)` | Hover states on cards, dropdown menus, tooltips |
| Floating / L3 | `box-shadow: 0px 8px 24px rgba(0, 0, 0, 0.15)` | Modals, overlays, floating action buttons, elevated cards |
| Maximum / L4 | `box-shadow: 0px 16px  interactive (then use `#3F58E0`). Never use pure black.

2. **Apply `Helvetica Neue` at `16px` / `1.5` line-height as default body copy**; all other sizes and weights derive from the hierarchy table in Section 3.

3. **Interactive elements use `#3F58E0` exclusively** for primary CTAs; secondary actions use `#FFFFFF` background with `#E5E5E5` border.

4. **Spacing follows the scale: 4, 8, 12, 16, 24, 32, 40, 48, 132px**; use context to select: internal padding (12–24px), section margins (32–40px), hero spacing (132px).

5. **Touch targets minimum `44px × 44px`; maintain `8px` minimum gap** between adjacent interactive elements to prevent misclick.

6. **Border-radius: 4px for inputs/buttons, 8px for cards, 50% for circles**; do not exceed 12px for standard components.

7. **Shadows follow the 4-level hierarchy**: surface (none) → raised (0 2px 8px rgba 0.04) → elevated (0 4px 16px rgba 0.08) → floating (0 8px 24px rgba 0.12); use raised for default40px rgba(0, 0, 0, 0.2)` | Fullscreen overlays, top-level modals, drawer navigation |

**Shadow Philosophy:**
Shadows are subtle and always use black with reduced opacity to maintain a light, accessible interface. Elevation is used sparingly to draw focus to critical actions or distinct containers. The shadow intensity increases proportionally with semantic importance, guiding users' visual hierarchy. Hard shadows are avoided; all shadows use blur radii (3px–40px) for softness.

## 7. Do's and Don'ts

### Do
- **Center, elevated for featured.

8. **Responsive breakpoints: 320px mobile, 480px small tablet, 768px tablet, 1024px desktop, 1440px large desktop**; scale typography and spacing proportionally; collapse navigation to vertical on tablet.

9. **All hover states add `transition: all 0.2s ease`** to buttons and links; primary button hover is `#2A3BA8`; secondary is `#F5F5F5` background.

10. **Accessibility: maintain WCAG AA contrast (4.5:1 for text) between `#111516` text and `#FFFFFF` background; all interactive elements must be keyboard accessible** with visible focus indicators using the shadow system.-align critical messaging** — headings, reassurance text, and CTAs should be centered for authority and emphasis
- **Use consistent 8px spacing intervals** — maintain vertical rhythm across all sections
- **Prioritize text contrast** — ensure all text meets WCAG AA standards (7:1 minimum for body text)
- **Apply blue accent sparingly** — reserve `#3F58E0` for primary CTAs, links, and interactive elements only
- **Use Helvetica Neue as primary font** — maintains brand consistency and web-safe reliability
- **Include adequate padding in interactive elements** — minimum `12px` vertical, `24px` horizontal for buttons
- **Provide visual feedback on hover** — color shifts, underlines, or shadow changes indicate interactivity
- **Leverage whitespace** — generous margins reduce cognitive load and increase visual trust
- **Test on light backgrounds** — all designs use light/white backgrounds for security contexts
- **Use loading spinners responsibly** — apply to asynchronous operations without blocking the UI

### Don't
- **Don't mix multiple accent colors** — stick to `#3F58E0` for consistency
- **Don't use font weights lighter than 400** — poor accessibility; minimum is regular weight
- **Don't apply shadows to text** — text shadows reduce legibility; use color contrast instead
- **Don't override focus states** — keyboard navigation and `outline: 0px` removal violates accessibility standards (always provide `:focus` styling)
- **Don't use small type for critical content** — minimum readable size is `14px`; use `16px` for body copy
- **Don't apply rigid borders to all elements** — use subtle `1px solid #DDDDDD` for containers only
- **Don't center-align body paragraphs** — center alignment reduces readability; use left alignment for copy
- **Don't use more than 2 font sizes in headers** — maintain hierarchy simplicity
- **Don't forget line-height** — minimum `1.4` for readability; use `1.5` for comfort
- **Don't hide required form labels** — always display labels above inputs, even if placeholder text exists
- **Don't apply animations to critical elements** — spinners only; avoid decorative motion in security contexts

## 8. Responsive Behavior

### Breakpoints

| Breakpoint Name | Width | Key Changes |
|---|---|---|
| Mobile | 320px–639px | Single column; full-width containers minus 20px margins; `16px` base font; stack all sections vertically |
| Tablet | 640px–1023px | 2-column grid; `18px` base font; increased padding to `24px`; horizontal scrolling disabled |
| Desktop | 1024px+ | 3+ column grid; max-width `1200px` containers; `16px` base font; full horizontal layout |
| Large Desktop | 1440px+ | Extended max-width `1400px`; enhanced spacing for breathing room |

### Touch Targets
- **Minimum touch target:** `48px` × `48px` (mobile buttons and links)
- **Recommended touch target:** `56px` × `56px` (primary CTAs)
- **Desktop click target:** `40px` × `40px` minimum (buttons, links)
- **Spacing between targets:** Minimum `8px` to prevent accidental activation

### Collapsing Strategy
- **Mobile (320–639px):** Hide secondary navigation; stack cards vertically; single-column layouts; remove horizontal padding on sections
- **Tablet (640–1023px):** Show condensed navigation; 2-column grids; increase section padding to `20px`; maintain heading sizes but reduce line-height for space efficiency
- **Desktop (1024px+):** Full navigation bar; multi-column grids; generous spacing; optimal reading widths achieved via max-width containers

## 9. Agent Prompt Guide

### Quick Color Reference
- **Primary CTA & Links:** Electric Blue (`#3F58E0`)
- **Primary CTA Hover:** Blue Dark (`#2E47C1`)
- **Heading & Body Text:** Dark Charcoal (`#111516`)
- **Background & Surfaces:** Off-White (`#FFFFFF`)
- **Secondary/Disabled Elements:** Light Gray (`#F5F5F5`)
- **Borders & Dividers:** Subtle Border (`#DDDDDD`)
- **Helper Text & Muted:** Medium Gray (`#999999`)

### Iteration Guide

1. **Typography Priority:** Always use Helvetica Neue at exact pixel sizes specified in Section 3 hierarchy table. No font substitution except system fallback stack.

2. **Spacing Consistency:** Apply spacing in 4px multiples (8px, 12px, 16px, 24px, 32px, 40px). Never use arbitrary spacing values. Reference Section 5 spacing scale for all margins/padding.

3. **Color Discipline:** Use only the 6 core colors specified in Section 2. Dark text is always `#111516` on light backgrounds. Interactive elements are exclusively `#3F58E0` unless explicitly stated as variant.

4. **Component Assembly:** Every button, input, and card must match the CSS properties listed in Section 4. Include all three states: default, hover, and active. Include focus state for keyboard accessibility.

5. **Elevation Strategy:** Apply shadows strictly per Section 6 table levels. Level 1 for cards, Level 2 for hover/dropdowns, Level 3 for modals. Never exceed `rgba(0, 0, 0, 0.2)` opacity.

6. **Responsive Adaptation:** Implement breakpoints from Section 8. Mobile layouts stack vertically; tablet uses 2 columns; desktop uses max-width containers. Touch targets are minimum `48px` × `48px`.

7. **Accessibility Compliance:** All text contrasts must meet WCAG AA (7:1 minimum). Never remove focus outlines. All interactive elements require hover/active states. Form labels are always visible.

8. **Whitespace Application:** Center-align critical messaging (headings, loading states). Use 40px–132px spacing for major section breaks. Leave minimum 20px horizontal margin on mobile.

9. **Trust & Clarity Design Principle:** All components should feel professional, secure, and clear. Avoid decorative elements, rounded shadows, or bright alerts. Use calm blues and neutrals. Every interaction should be obvious without ambiguity.

10. **Testing Validation:** Verify all components on light backgrounds only. Test loading states with animated spinners. Validate form states (focus, error, disabled). Confirm all links are underlined and blue on hover/active.
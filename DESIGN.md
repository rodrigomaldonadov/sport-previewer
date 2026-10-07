---
name: Octagon Pulse
colors:
  surface: '#131315'
  surface-dim: '#131315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0e0e10'
  surface-container-low: '#1c1b1d'
  surface-container: '#201f22'
  surface-container-high: '#2a2a2c'
  surface-container-highest: '#353437'
  on-surface: '#e5e1e4'
  on-surface-variant: '#e6bdb8'
  inverse-surface: '#e5e1e4'
  inverse-on-surface: '#313032'
  outline: '#ac8884'
  outline-variant: '#5c403c'
  surface-tint: '#ffb4ab'
  primary: '#ffb4ab'
  on-primary: '#690005'
  primary-container: '#dc2626'
  on-primary-container: '#fff6f5'
  inverse-primary: '#bf0715'
  secondary: '#b4c5ff'
  on-secondary: '#002a78'
  secondary-container: '#0053db'
  on-secondary-container: '#cdd7ff'
  tertiary: '#f7be1d'
  on-tertiary: '#3f2e00'
  tertiary-container: '#906d00'
  on-tertiary-container: '#fff8f0'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ab'
  on-primary-fixed: '#410002'
  on-primary-fixed-variant: '#93000b'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#00174b'
  on-secondary-fixed-variant: '#003ea8'
  tertiary-fixed: '#ffdf9a'
  tertiary-fixed-dim: '#f7be1d'
  on-tertiary-fixed: '#251a00'
  on-tertiary-fixed-variant: '#5a4300'
  background: '#131315'
  on-background: '#e5e1e4'
  surface-variant: '#353437'
typography:
  headline-xl:
    fontFamily: Oswald
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: 0.04em
  headline-xl-mobile:
    fontFamily: Oswald
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: 0.03em
  headline-lg:
    fontFamily: Oswald
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: 0.03em
  headline-lg-mobile:
    fontFamily: Oswald
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: 0.02em
  headline-md:
    fontFamily: Oswald
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: 0.02em
  headline-sm:
    fontFamily: Oswald
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 24px
    letterSpacing: 0.01em
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 18px
    letterSpacing: 0.06em
  label-md:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 12px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system channels the electrifying, high-stakes atmosphere of elite Pay-Per-View combat sports broadcasts. It is engineered for fight analysts, sports bettors, and hardcore mixed martial arts fans who demand real-time telemetry, split-second strike telemetry, dynamic corner analysis, and live event tracking.

The design movement merges **Tactile Broadcast UI** with **High-Contrast Precision**. Visually, it replicates high-end ringside graphics packages and dynamic broadcast scorebugs: pure zinc-950 pitch-black depth, layered dark metallic surfaces, laser-etched border micro-lines, and razor-sharp data readouts. It avoids playful or casual softness, prioritizing an aggressive, urgent, and technically pristine aesthetic that treats live athletic combat with championship-level reverence.

## Colors
The color palette directly mirrors the iconic architecture of combat sports:
- **Red Corner (Primary: `#DC2626`)**: Fierce, alert, intense. Used for Red Corner fighters, live broadcast indicators, danger/critical metrics, and offensive strike surges.
- **Blue Corner (Secondary: `#2563EB`)**: Technical, vivid, commanding. Used for Blue Corner fighters, secondary telemetry filters, defensive stats, and system highlights.
- **Championship Gold (Tertiary: `#EAB308`)**: Title fight badges, championship belt verifications, performance bonuses, and definitive victorious finishes.
- **Octagon Abyss (Neutral: `#09090B`)**: Grounding foundation built on dark neutral scales:
    - Surface Canvas: `#09090B` (zinc-950)
    - Surface Card Elevated: `#18181B` (zinc-900)
    - Surface Nested / Overlay: `#27272A` (zinc-800/60)
    - Hairline Borders: `#27272A` (zinc-800) and `#3F3F46` (zinc-700) for active states.
    - Text Primary: `#FAFAFA` (zinc-50), Text Muted: `#A1A1AA` (zinc-400), Text Dim: `#71717A` (zinc-500).

## Typography
Typography is bold, condensed, and athletic.

- **Display & Headlines (`Oswald`)**: All display titles, fighter names, weight classes, and event headliners are rendered in uppercase `Oswald`. The condensed structure mimics live TV chyrons and scoreboard graphics, conserving horizontal space while maximizing impact.
- **Telemetry & Body (`Space Grotesk`)**: Technical, high-legibility grotesque designed to convey round clocks, strike percentages, physical reaches, odds, and analytical breakdowns cleanly without typographic noise.
- **Labels & Micro-data**: Always uppercase with widened tracking (`0.06em` to `0.1em`) to maintain sharp legibility on dark low-light viewports.

## Layout & Spacing
The layout implements a high-density, 12-column responsive grid built to present high volumes of live fight data simultaneously without claustrophobic crowding.

- **Desktop (>= 1280px)**: 12 columns, 1.5rem gutter, 2rem page margin. Layout supports a split 3-pane configuration: live card marquee / event list on the left (3 cols), fight telemetry & tale-of-the-tape center arena (6 cols), and real-time round stats / bet odds feed on the right (3 cols).
- **Tablet (768px - 1279px)**: 8 columns, 1rem gutter, 1.5rem margin. Center and right panes stack vertically.
- **Mobile (< 768px)**: 4 columns, 0.75rem gutter, 1rem margin. Single-column flow with swipeable telemetry tabs and pinned bottom broadcast mini-bar.
- **Rhythm**: Element padding relies strictly on `space-xs` (4px) to `space-md` (16px) for data tables, metric tiles, and strike breakdown maps, maintaining tight broadcast monitor density.

## Elevation & Depth
Elevation avoids generic soft drop shadows. Depth is achieved via **Tonal Surface Stacking** coupled with **Subtle Luminous Backdrops**:

- **Level 0 (Octagon Base)**: Pure `#09090B`. The deep ground for global viewport backdrops.
- **Level 1 (Card Matrix)**: Surface `#18181B` enclosed by a crisp `1px solid #27272A` outline. Creates distinct, tactical containment for fighter profiles and fight cards.
- **Level 2 (Active / Floating Overlays)**: Surface `#27272A` with an ambient dark rim: `box-shadow: 0 8px 24px -4px rgba(0, 0, 0, 0.8)`.
- **Corner Luminescence**: High-voltage fights utilize subtle tinted edge glows:
    - Red Corner focus: `box-shadow: 0 0 20px -6px rgba(220, 38, 38, 0.25), inset 0 1px 0 0 rgba(220, 38, 38, 0.4)`.
    - Blue Corner focus: `box-shadow: 0 0 20px -6px rgba(37, 99, 235, 0.25), inset 0 1px 0 0 rgba(37, 99, 235, 0.4)`.
    - Championship focus: `box-shadow: 0 0 24px -6px rgba(234, 179, 8, 0.2), inset 0 1px 0 0 rgba(234, 179, 8, 0.5)`.

## Shapes
Shapes are disciplined, architectural, and compact.

The system operates on **Soft Level 1 (`0.25rem` / 4px base)** to retain the sharp, athletic edge of stadium electronics, digital timers, and live broadcast chyrons. Roundedness rules:
- Base inputs, buttons, and stat badges: `0.25rem` (4px).
- Main telemetry containers and card shells (`rounded-lg`): `0.5rem` (8px).
- Modals, large video viewports, and floating panels (`rounded-xl`): `0.75rem` (12px).
- Pill shapes are restricted exclusively to live status indicators (e.g., `• LIVE PPV`) and round status badges.

## Components

### Buttons
- **Red Corner Action (Primary Strike)**: Background `#DC2626`, text `#FFFFFF`, font `Space Grotesk` uppercase bold (`label-md`). Hover: `#EF4444`. Active: subtle downward scale (`98%`). Focus: `2px solid #FAFAFA` with 2px offset.
- **Blue Corner Action (Secondary Strike)**: Background `#2563EB`, text `#FFFFFF`, uppercase bold. Hover: `#3B82F6`.
- **Championship Action**: Background `#EAB308`, text `#09090B`, font `Space Grotesk` bold.
- **Ghost Broadcast Button**: Background `transparent`, border `1px solid #3F3F46`, text `#FAFAFA`. Hover: background `#27272A`, border `#71717A`.

### Fighter Cards & Tale of the Tape
- Containers feature `#18181B` backgrounds framed with `#27272A` borders.
- Split cards display asymmetric accents: Red corner athlete accented by a 3px top-left `#DC2626` strip, Blue corner athlete mirrored with a 3px top-right `#2563EB` strip.
- Centered between opponents sits the "VS" emblem and odds comparison chip.

### Stats Badges & Chips
- **Live Broadcast Chip**: `#18181B` surface with a pulsing `#DC2626` dot indicator and label `LIVE`.
- **Championship Badge**: High-contrast `#EAB308` text over `rgba(234, 179, 8, 0.12)` fill with a hairline `1px solid rgba(234, 179, 8, 0.4)` border. Accompanied by Lucide `Trophy` or `Crown` icon.
- **Fighter Record & Metric Chip**: Monospaced tabular figures, `#27272A` fill, `#A1A1AA` text, uppercase tracking.

### Countdown Timers & Round Clocks
- Displayed using oversized `Oswald` numerical styling.
- Round status badges (`R1`, `R2`, `R5 - CHAMPIONSHIP ROUND`) display prominent contrasting backdrops with countdowns in `00:00` tabular mono formats.

### Form Inputs & Telemetry Filters
- **Inputs**: Dark field surface `#18181B`, border `1px solid #27272A`, text `#FAFAFA`, placeholder `#71717A`.
- **Focused State**: Border `#FAFAFA` with zero diffusion halo for razor-sharp precision.
- **Radio & Checkbox**: Custom square indicators with 2px chamfered corners; checked state fills with `#DC2626` or `#2563EB` containing high-contrast checkmark icons.

### Lucide Icons Integration
- Rendered with `1.75px` stroke weight to match the technical precision of `Space Grotesk`.
- Color inheritance aligns strictly with current context (e.g., Lucide `Flame` in `#DC2626`, Lucide `Shield` in `#2563EB`, Lucide `Award` in `#EAB308`).
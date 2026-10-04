---
name: Academic Kinetic
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#464555'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4d44e3'
  primary: '#3525cd'
  on-primary: '#ffffff'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#5654a8'
  on-secondary: '#ffffff'
  secondary-container: '#a7a5ff'
  on-secondary-container: '#393689'
  tertiary: '#005338'
  on-tertiary: '#ffffff'
  tertiary-container: '#006e4b'
  on-tertiary-container: '#67f4b7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#e2dfff'
  secondary-fixed-dim: '#c3c0ff'
  on-secondary-fixed: '#100563'
  on-secondary-fixed-variant: '#3e3c8f'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-stat:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0em
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-stat:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.25rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.875rem
  space-lg: 1.25rem
  space-xl: 1.75rem
---

## Brand & Style

This design system is engineered for undergraduate and graduate students managing academic accountability under high cognitive load. The design language marries academic rigor with digital athleticism—positioning daily attendance tracking not as an administrative chore, but as an empowering, dynamic personal metric.

The aesthetic follows **Tactile Minimal Modernism**: a high-utility, hyper-clean foundation built with generous white/slate canvases, paired with purposeful, high-contrast semantic feedback loops. Key moments feature tactile, physical micro-interactions (snappy segmented toggles, pill status indicators, and confident metric cards). Visual noise is eliminated; hierarchy is dictated strictly through typography scale, precise spacing, and status-driven chromatic signaling. The emotional tone is decisive, reassuring, motivating, and frictionless.

## Colors

The palette leverages a high-impact core anchored by deep navy and energetic electric indigo, coupled with dedicated chromatic zones that instantly communicate academic standing:

- **Primary & Interactive Engine**: `#4F46E5` (Electric Indigo) commands primary actions, focused tabs, and active selection states. `#312E81` (Deep Indigo Navy) serves as the anchor for prominent card headings, app bars, and high-density metric displays.
- **Surface Infrastructure**: Canvas background strictly utilizes `#F8FAFC` (Slate 50) to minimize glare and eye fatigue during late-night and early-morning checks. Foreground cards, drawers, and modal sheets sit crisply on pure `#FFFFFF` (White), complemented by structural borders in `#E2E8F0` (Slate 200).
- **Attendance Semantic Triad**:
  - **Safe Zone (≥ 75%)**: `#10B981` (Emerald 500) text/indicator on `#ECFDF5` (Mint/Emerald 50) container surface. Communicates safety, low friction, and compliance.
  - **Warning Zone (65% – 74%)**: `#F59E0B` (Amber 500) text/indicator on `#FFFBEB` (Amber 50) container surface. Demands attention without triggering panic.
  - **Critical Zone (< 65%)**: `#EF4444` (Rose 500) text/indicator on `#FEF2F2` (Rose 50) container surface. Signals urgent risk of debarment or academic penalty.
- **Typography & Neutrals**: Primary text relies on `#0F172A` (Slate 900), secondary context on `#64748B` (Slate 500), and disabled/muted text on `#94A3B8` (Slate 400).

## Typography

Typography prioritizes extreme data legibility and optical weight contrast:

- **Display & Headlines (Plus Jakarta Sans)**: Used for prominent figures, course names, and section titles. The geometric yet rounded contours project youthfulness without sacrificing structural sharpness.
- **Body & Controls (Inter)**: Handles informational text, course codes, schedules, and button elements. Delivers neutral clarity at dense mobile scales.
- **Tabular Figures & Metrics**: All numerical statistics, attendance percentages, and fractions (`e.g., 28/32`) must activate the OpenType feature `font-variant-numeric: tabular-nums` (tnum). This guarantees column stability when counters update or progress bars animate.
- **Type Pairing Rule**: Never set course codes or numbers in light weights; metrics must be bold (`700` or `800`) to anchor scanning eyes instantly.

## Layout & Spacing

The layout is built mobile-first, calibrated around a default **390px viewport width** (standard contemporary smartphone form factor):

- **Grid Architecture**: Single-column layout on mobile devices (`< 600px`), transitioning to an offset multi-pane view on tablets (`600px - 1024px`) and desktop (`> 1024px`).
- **Canvas Boundaries**: Outer horizontal padding is standardized to `1rem` (`16px`) on mobile devices to preserve horizontal card real estate, stepping up to `1.25rem` (`20px`) on tablets.
- **Spacing Rhythm**: Employs an exact 4px/8px modular base. Compact gaps (`0.5rem` / `8px`) delineate tightly coupled metadata (lecturer name, lecture hall), while structural separation between independent course cards uses `0.875rem` (`14px`) to maintain density without visual collision.
- **Vertical Thumb Zone Optimization**: Primary interactive elements (daily segmented attendance markers, quick logging floating bars) are anchored within the lower 40% of the viewport. Top app bars remain restricted to global metric overviews and calendar pickers.

## Elevation & Depth

Visual depth is achieved through an overlap of crisp container outlines and atmospheric ambient drop-shadows:

- **Surface Tiers**:
  - **Base Canvas**: Flat `#F8FAFC`. Zero elevation.
  - **Cards & Primary Modules**: `#FFFFFF` with a `1px` structural outline in `#F1F5F9` and an ultra-soft ambient shadow: `0 1px 3px rgba(15, 23, 42, 0.04), 0 4px 12px rgba(15, 23, 42, 0.03)`.
  - **Active / Dragged Elements**: Elevated cards receive a concentrated lift: `0 8px 24px rgba(79, 70, 229, 0.12)`.
  - **Floating Dock / Bottom Nav**: Elevated sheet with backdrop blur (`backdrop-filter: blur(16px)` on `rgba(255, 255, 255, 0.88)`) and high diffusion shadow: `0 -4px 20px rgba(15, 23, 42, 0.06)`.
- **Status Glows**: Warning and critical metric rings use faint 10% opacity color glows rather than harsh drop-shadows, ensuring accessibility without visual clutter.

## Shapes

The system implements a controlled **Rounded** geometry scheme (`level 2`) to balance mobile ergonomics with structured dashboard order:

- **Cards & Panels**: `rounded-lg` (`1rem` / `16px`) corners give subject blocks a friendly, approachable touch footprint.
- **Segmented Attendance Sliders & Badges**: Fully pill-shaped (`9999px`) to create an immediate visual contrast against rectangular course cards and communicate distinct clickability.
- **Progress Trackers & Gauges**: Track ends and circular arc caps use continuous rounded strokes (`stroke-linecap: round`), sustaining fluid movement during state updates.

## Components

### Buttons & Interactive Controls
- **Primary Action**: Solid `#4F46E5` background, pure white text, 48px standard touch height, fully rounded or `rounded-lg`. On press, triggers an optical inset or micro-scale down (`0.98`).
- **Segmented Attendance Control**: Dual-segment toggle contained within a `#F1F5F9` pill container (44px height).
  - *Present State*: Switches to `#10B981` (or `#4F46E5`) with white text and an internal soft shadow.
  - *Absent State*: Transitions to `#EF4444` background with white text.
  - Inactive options rest as slate-gray text (`#64748B`) with an animated sliding pill thumb.

### Status Chips & Badges
- Pill-shaped badges (`height: 24px`, padding `0 10px`, typography `label-stat`).
- **Safe**: `#ECFDF5` background, `#047857` text, with a 6px solid `#10B981` leading dot indicator.
- **Warning**: `#FFFBEB` background, `#B45309` text, 6px `#F59E0B` leading dot.
- **Critical**: `#FEF2F2` background, `#B91C1C` text, 6px `#EF4444` leading dot.

### Course Attendance Card
- Encapsulated white surface (`rounded-lg`, subtle border, `p-4`).
- Contains a 3-part layout:
  1. *Top Header*: Course code (`body-sm`, uppercase, slate-500) aligned beside the status pill badge.
  2. *Midsection*: Course title (`headline-sm`, slate-900) accompanied by large tabular percentage metric (`headline-md`).
  3. *Bottom Utility*: Linear progress bar (6px height, track in `#F1F5F9`, bar filled with matching semantic status color) followed by the tactile "Mark Present / Absent" segmented switch.

### Inputs & Search
- Inputs use `#FFFFFF` background with a crisp `#CBD5E1` border, 48px height, `rounded-md` (8px).
- Focus state replaces the border with a sharp 2px electric indigo ring (`#4F46E5`) accompanied by an indigo tint wash (`rgba(79, 70, 229, 0.05)`).
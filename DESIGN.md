---
name: Kisan Mandi Connect
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf1'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fa'
  on-surface: '#111c2c'
  on-surface-variant: '#43474d'
  inverse-surface: '#263142'
  inverse-on-surface: '#ebf1ff'
  outline: '#74777e'
  outline-variant: '#c4c6ce'
  surface-tint: '#49607c'
  primary: '#001326'
  on-primary: '#ffffff'
  primary-container: '#0e2841'
  on-primary-container: '#7890ae'
  inverse-primary: '#b1c8e8'
  secondary: '#1d6587'
  on-secondary: '#ffffff'
  secondary-container: '#98d6fe'
  on-secondary-container: '#115e80'
  tertiary: '#260900'
  on-tertiary: '#ffffff'
  tertiary-container: '#471800'
  on-tertiary-container: '#e26b2d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d1e4ff'
  primary-fixed-dim: '#b1c8e8'
  on-primary-fixed: '#011d35'
  on-primary-fixed-variant: '#314863'
  secondary-fixed: '#c5e7ff'
  secondary-fixed-dim: '#90cef5'
  on-secondary-fixed: '#001e2d'
  on-secondary-fixed-variant: '#004c6a'
  tertiary-fixed: '#ffdbcc'
  tertiary-fixed-dim: '#ffb694'
  on-tertiary-fixed: '#351000'
  on-tertiary-fixed-variant: '#7b2f00'
  background: '#f9f9ff'
  on-background: '#111c2c'
  surface-variant: '#d8e3fa'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '800'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  section-eyebrow:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '800'
    lineHeight: 16px
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  space-2xs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4rem
  gutter-mobile: 1rem
  gutter-desktop: 1.5rem
  margin-mobile: 1rem
  margin-tablet: 2rem
  margin-desktop: 3rem
---

## Brand & Style

This design system delivers a civic-tech and govtech digital infrastructure engineered for transparency, efficiency, and dignified utility. Built to support agricultural procurement scheduling, slot booking, and live market visibility, the interface serves two core user archetypes: rural farmers seeking swift, frictionless slot generation on handheld devices under bright sunlight, and Mandi market officials coordinating high-throughput logistics.

The aesthetic philosophy balances **Civic Utility** and **Modern Approachability**. Rather than relying on outdated bureaucratic layouts or hyper-minimalist fintech abstractions, the UI adopts an organized, highly structured design model characterized by generous spatial breathing room, high-contrast typography, crisp surface delineation, and tactile clarity. Every critical user action—such as token status, queue timing, crop verification, and payment milestones—is prioritized through immediate visual hierarchy.

Interactions are robust, utilitarian, and dependable. The visual tone instills governance confidence while remaining warm, legible, and directly empowering for users across diverse digital literacy levels.

## Colors

The palette is engineered to meet strict accessibility thresholds (WCAG AAA for primary textual elements, AA minimum across all actionable components) under challenging daylight environments.

- **Primary (`#0E2841`)**: Deep agricultural navy anchoring headers, navigation bars, structural framing, and primary text hierarchies. It establishes authoritative governance and high contrast against white and light neutral surfaces.
- **Secondary (`#156082`)**: Mid-tier sea-slate blue applied to contextual navigation, secondary actions, selected card states, interactive icons, and subheadings.
- **Tertiary (`#E97132`)**: Harvest amber/orange reserved for critical calls-to-action (Slot Booking, Confirm Gate Pass), real-time alerts, pending triage states, and high-urgency notifications.
- **Supportive Accents**:
  - **Success / Low-Load Green (`#196B24`, secondary tint `#4EA72E`)**: Validated gate passes, approved quality metrics, available Mandi capacity, and completed payouts.
  - **Informative Sky (`#0F9ED5`)**: Informational badges, metric trend indicators, and active focal outlines.
- **Surfaces & Neutrals**:
  - Default canvas is pure `#FFFFFF` interspersed with soft neutral section washes (`#F8FAFC`).
  - Structural card backgrounds utilize `#FFFFFF` resting on `#F1F5F9`, bounded by crisp, low-saturation borders (`#E2E8F0` and `#E8E8E8`).
  - Neutral text tiers transition from deep charcoal (`#1E293B`) to accessible slate (`#4A5568`).

## Typography

The type hierarchy uses **Plus Jakarta Sans** across all roles. Its geometric underpinnings provide high technical clarity, while wide counters and open apertures maximize legibility on budget smartphone screens and lower-resolution field displays.

- **Display & Headlines**: Prominent, confident, and tight. Used for queue numbers, slot status, daily procurement rates (MSP), and primary dashboard greetings. Mobile variants downscale gracefully to preserve line rhythm and eliminate awkward hyphenation.
- **Section Eyebrows (`section-eyebrow`)**: Always styled in bold uppercase (`text-transform: uppercase`) with positive tracking (`letterSpacing: 0.08em`). Used strictly for categorical signposts, regulatory agency prefixes, and table headers.
- **Body & Numerical Readouts**: Body levels emphasize comfortably spaced line-heights for rapid reading. Quantitative tabular data (weights in quintals, token numbers, payouts in ₹) rely on tabular figures (`font-variant-numeric: tabular-nums`) to guarantee clean column alignment.

## Layout & Spacing

This design system uses an **8pt modular grid** mapped to rem spacing units, enforcing a strict fluid layout adaptable across mobile handhelds, ruggedized field tablets, and Mandi control room desktop workstations.

- **Mobile (< 640px)**: 4-column fluid layout with `1rem` margins and `1rem` gutters. Touch targets adhere to a minimum size of 48px × 48px to accommodate one-handed operation in transit or field work.
- **Tablet (640px - 1024px)**: 8-column layout with `2rem` margins and `1.5rem` gutters. Slotted side panels, scheduling timelines, and crop verification cards shift into 2-column card configurations.
- **Desktop (> 1024px)**: 12-column fixed-max layout centered at a maximum canvas width of `1280px` with `3rem` lateral padding. Dashboard data grids, live gate entry monitors, and queue management pipelines utilize persistent left-rail navigation (`280px` width) paired with responsive analytical matrices.

## Elevation & Depth

Visual hierarchy is communicated through **structural borders and tonal elevation** rather than dramatic shadows. Under outdoor glare, heavy blurred drop shadows wash out and introduce visual murkiness; crisp outlines paired with soft, low-spread ambient elevation maintain absolute edge definition.

- **Flat / Surface Level (0dp)**: Standard section cards, table containers, and read-only informational tiles use a solid `#FFFFFF` fill resting on `#F8FAFC` backgrounds, bounded by a 1px solid border (`#E2E8F0`).
- **Interactive Surface (2dp)**: Selectable time slots, vehicle type pickers, and filter chips use subtle border differentiation (`#CBD5E1`) combined with a soft atmospheric lift: `box-shadow: 0 1px 3px 0 rgba(14, 40, 65, 0.05), 0 1px 2px -1px rgba(14, 40, 65, 0.05)`.
- **Floating / Elevated (4dp - 8dp)**: Modal dialogues, active slot confirmation drawers, gate pass verification sheets, and sticky mobile booking triggers implement a crisp border and targeted navy-tinted ambient depth: `box-shadow: 0 10px 15px -3px rgba(14, 40, 65, 0.08), 0 4px 6px -4px rgba(14, 40, 65, 0.04)`.
- **Focus & Selection**: Interactive components reject ambient blurs in favor of a distinct 2px outer ring offset in `#0F9ED5` or `#E97132`, ensuring distinct tactical feedback.

## Shapes

The interface embraces a balanced **Rounded (`2`)** geometry. Radii are distributed systematically to maintain high structural integrity while remaining soft, modern, and human:

- **Base Radius (`0.5rem` / 8px)**: Standard text inputs, dropdown triggers, utility buttons, inline badge indicators, and verification banners.
- **Large Radius (`1rem` / 16px)**: Slot booking cards, commodity pricing summary modules, gate entry summary cards, and modal dialog containers.
- **Extra Large Radius (`1.5rem` / 24px)**: Bottom drawer sheets on mobile viewports, high-priority alert cards, and onboarding status blocks.
- **Pill (`9999px`)**: Category tags, live queue status pills (e.g., "Mandi Capacity: Low"), interactive chip filters, and numeric counter avatars.

## Components

### Buttons
- **Primary Action (Tertiary Orange `#E97132`)**: High-contrast white text (`#FFFFFF`), solid background, 8px border radius, 48px minimum height on mobile. Used exclusively for forward-driving actions (e.g., "Confirm Slot Booking", "Generate Mandi Pass").
- **Secondary Action (Accent Navy `#156082`)**: Deep blue background with white text or 1.5px solid `#156082` border with `#156082` text on transparent fill. Used for "Download Receipt", "View Alternatives", and secondary data filters.
- **Subtle / Ghost Button**: `#F1F5F9` background or transparent fill with `#0E2841` text for back actions, cancel events, and tertiary actions.

### Badges & Status Chips
- **Low Load / Success Pill**: Pale emerald fill (`#E8F5E9`), dark green text (`#196B24`), 1px solid `#C8E6C9` border. Displays "Low Wait Time", "MSP Verified", or "Gate Approved".
- **Moderate / Pending Pill**: Soft amber fill (`#FFF3E0`), dark orange text (`#C2410C`), 1px solid `#FFE0B2` border. Used for "Arrival Pending" and "Queue Filling".
- **High Load / Alert Pill**: Soft rose fill (`#FEE2E2`), crimson text (`#991B1B`), 1px solid `#FECACA` border. Used for "Capacity Full" and "Document Required".
- All chips feature pill geometry (`rounded-full`), `0.25rem` vertical / `0.75rem` horizontal padding, and uppercase `label-md` tracking.

### Cards & Procurement Containers
- Primary modules reside on `#FFFFFF` backgrounds bordered with 1px `#E2E8F0` and standard `1rem` radius.
- Cards are partitioned using subtle dividing rules (`#F1F5F9`). Header zones house the uppercase category eyebrow and title, while the body isolates key metrics (crop variety, quintal volume, scheduled window) using structured grid cells.

### Form Inputs & Selectors
- Text fields utilize a 48px height footprint, `#FFFFFF` background, 1.5px border in `#CBD5E1`, and 8px border radius.
- Labels are positioned statically above the field in `label-lg` (`#0E2841`) with explicit required-indicator asterisks in `#E97132`.
- Focus states invoke a 1.5px `#156082` border paired with an outer `0 0 0 3px rgba(15, 158, 213, 0.2)` highlight.

### Checkboxes, Radios & Slot Tiles
- Large 20px controls with generous hit boxes (44px target area).
- Interactive time-slot selectors operate as selectable card tiles: resting state has `#FFFFFF` fill and `#E2E8F0` border; selected state transitions to a light blue wash (`#F0F9FF`), `#156082` 2px border, and a checked indicator badge.

### Domain-Specific Components
- **Live Mandi Capacity Gauge**: A high-visibility progress bar featuring stepped color segmentation (`#196B24` to `#4EA72E` to `#E97132`), signaling dock congestion and active wait-time estimates in hours/minutes.
- **Digital Gate Pass Token**: A distinctive, downloadable high-contrast container with dual-notch punchout styling, displaying an uncompressed QR code, prominent vehicle plate identifier, Farmer Registration ID, and allocated gate number.
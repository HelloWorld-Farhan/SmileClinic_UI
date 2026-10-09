---
name: Clinical Patient Portal
colors:
  surface: '#f7fafc'
  surface-dim: '#d7dadc'
  surface-bright: '#f7fafc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f6'
  surface-container: '#ebeef0'
  surface-container-high: '#e5e9eb'
  surface-container-highest: '#e0e3e5'
  on-surface: '#181c1e'
  on-surface-variant: '#3e494a'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eef1f3'
  outline: '#6e797b'
  outline-variant: '#bdc8ca'
  surface-tint: '#006972'
  primary: '#005c65'
  on-primary: '#ffffff'
  primary-container: '#007782'
  on-primary-container: '#c1f7ff'
  inverse-primary: '#7cd4e0'
  secondary: '#1560a4'
  on-secondary: '#ffffff'
  secondary-container: '#7cb7ff'
  on-secondary-container: '#00477e'
  tertiary: '#005d5d'
  on-tertiary: '#ffffff'
  tertiary-container: '#007877'
  on-tertiary-container: '#9ffdfc'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#99f0fd'
  primary-fixed-dim: '#7cd4e0'
  on-primary-fixed: '#001f23'
  on-primary-fixed-variant: '#004f56'
  secondary-fixed: '#d3e4ff'
  secondary-fixed-dim: '#a2c9ff'
  on-secondary-fixed: '#001c38'
  on-secondary-fixed-variant: '#004880'
  tertiary-fixed: '#94f2f1'
  tertiary-fixed-dim: '#77d6d4'
  on-tertiary-fixed: '#002020'
  on-tertiary-fixed-variant: '#00504f'
  background: '#f7fafc'
  on-background: '#181c1e'
  surface-variant: '#e0e3e5'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.25rem
---

## Brand & Style
The design system is engineered for critical healthcare environments, patient management platforms, and hospital administrative operations. It balances sterile clinical precision with empathetic human-centered digital care. 

The emotional tone evokes calm authority, trust, hygiene, and effortless legibility. Rooted in modern institutional minimalism, the visual language avoids frivolous ornament while introducing softness through generous rounded surfaces, subtle translucent navigation containers, and focused color accents. The aesthetic accommodates both high-stress medical professionals navigating complex electronic health records (EHR) and vulnerable patients reviewing test results or scheduled procedures.

## Colors
The palette is centered on high-trust clinical tones:
- **Primary Teal (`#007782`)**: The anchor of the interface, used for top-level call-to-actions, primary navigation states, active vital tags, and interactive indicators.
- **Secondary Medical Blue (`#286CB0`)**: Provides authoritative grounding for secondary controls, structural administrative headers, informational charts, and department categorization.
- **Tertiary Mint/Teal (`#319796`)**: Applied for positive health signals, non-urgent badges, chart progress fills, and supporting visual hierarchy.
- **Neutral Canvas (`#F7FAFC`)**: A crisp, clinical off-white canvas that prevents glare while sustaining high contrast against `#FFFFFF` elevated cards and `#E2E8F0` hairline dividers.
- **Typography & Dark Contrast**: Dark charcoal (`#1A202C`) for headings and deep slate (`#4A5568`) for readable secondary body text. A dedicated emergency red (`#E53E3E`) is reserved strictly for destructive actions, critical vitals, and allergy alerts.

## Typography
Inter delivers clarity, uniform proportions, and neutral geometric letterforms essential for dense diagnostic data, dosage instructions, and patient identification numbers. 

- **Headings**: Use semi-bold and bold weights to delineate page sections, modular dashboard panels, and patient summary headers.
- **Body copy**: Prioritizes comfortable line-heights and standard 400 weight for effortless scanning during clinical handoffs.
- **Labels & Numbers**: Employ tabular figures (`tnum`) across metrics, lab readouts, timestamps, and dosages to ensure vertical alignment throughout patient charts and clinical tables.

## Layout & Spacing
The layout model employs a responsive 12-column grid system paired with strict 8pt rhythm multiples (represented via base tokens).

- **Desktop Layout**: Features an anchor administrative sidebar (collapsed at 72px or expanded at 260px), a 64px utility header, and a fluid main dashboard panel composed of structured cards.
- **Card Modular Units**: Cards accommodate data streams, clinical charts, and diagnostic forms with an internal padding of `space-lg` (24px) for desktop and `space-md` (16px) for compact viewports.
- **Responsive Behavior**: Multi-column patient panels collapse to a single column below 768px (`margin-mobile`), maintaining full-width tap targets and horizontal scrolling tab carousels for lab panels.

## Elevation & Depth
Depth in the design system is maintained through soft planar separation rather than heavy physical drops:

- **Surface Layers**: Canvas sits on `#F7FAFC`, while analytical cards and interaction zones are rendered in pure white `#FFFFFF`.
- **Low-Contrast Structural Outlines**: Every card and container is framed with a hairline border (`1px solid #E2E8F0`), creating clear visual boundaries without visual clutter.
- **Ambient Diffusion**: Elevated elements like active flyouts, modal dialogs, and floating navigation pills utilize ultra-soft, tinted ambient shadows: `0px 8px 24px -4px rgba(0, 119, 130, 0.06), 0px 2px 6px -1px rgba(0, 0, 0, 0.04)`.
- **Subtle Layered Panels**: Recessed search bars and inactive pill containers use muted background fills (`#EDF2F7` or `rgba(0, 119, 130, 0.04)`) to establish internal visual wells.

## Shapes
The design system combines friendly rounded surfaces with disciplined structure to soften the hospital software experience:

- **Dashboard Cards**: Employ standard `rounded-xl` (16px) or `rounded-2xl` (20px) outer corners to preserve an approachable, modern feel.
- **Buttons and Chips**: Feature fully rounded pill forms (`rounded-full`) or smooth 8px corners (`rounded-md`) for tactical ease.
- **Form Controls**: Standard input fields maintain 8px to 10px corners, matching the visual balance of table structures and search components.

## Components

### Buttons
- **Primary**: Solid teal `#007782` background with `#FFFFFF` text, 40px height, 8px corner radius, transitioning to `#005F68` on hover.
- **Secondary**: Light teal tint (`rgba(0, 119, 130, 0.1)`) with `#007782` text.
- **Inverted / Dark**: Dark charcoal `#1A202C` background with white text, used for high-impact administrative actions.
- **Outlined**: 1px border `#CBD5E0` with neutral dark text and hover state introducing `#F7FAFC`.
- **Icon Actions**: Circular or square pill buttons (`w-10 h-10`) with centered medical icons, rendered in solid brand teal, deep blue, or danger red.

### Form Inputs & Search Fields
- Framed in subtle `#E2E8F0` borders on `#FFFFFF` or `#F7FAFC` recessed surfaces.
- Integrated leading search icons with `#718096` placeholders. Focus state introduces an inner `#007782` 1.5px ring without harsh browser outlines.

### Badges & Status Chips
- Pill-shaped (`rounded-full`) tags with compact padding (`py-1 px-3`).
- Contextual variants: Green/Mint (`#319796`) for normal vitals, Yellow/Amber for pending reviews, Red (`#E53E3E`) for urgent triage, and Blue (`#286CB0`) for active inpatient status.

### Metric Panels & Cards
- Clean pure-white cards enclosed in 1px `#E2E8F0` borders.
- Clear two-tier typographic structure: small muted uppercase category label above large 28px bold metric readouts.
- Embedded mini horizontal bar charts with rounded cap tracks comparing standard patient baseline against current readings.

### Navigation Header & Dock Chrome
- High-level navigation features floating pill docks with active teal circular backdrops framing crisp white icons.
- Sub-menus and tab switches utilize connected segmental pills for toggling between "Overview", "Lab Results", "Vitals History", and "Prescriptions".
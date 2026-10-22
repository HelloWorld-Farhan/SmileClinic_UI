---
name: Clinical Calm & Precision
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
  on-surface-variant: '#3e494a'
  inverse-surface: '#263142'
  inverse-on-surface: '#ebf1ff'
  outline: '#6e797b'
  outline-variant: '#bdc8ca'
  surface-tint: '#006972'
  primary: '#005c65'
  on-primary: '#ffffff'
  primary-container: '#007782'
  on-primary-container: '#c1f7ff'
  inverse-primary: '#7cd4e0'
  secondary: '#1960a3'
  on-secondary: '#ffffff'
  secondary-container: '#7db6ff'
  on-secondary-container: '#00477f'
  tertiary: '#005d5c'
  on-tertiary: '#ffffff'
  tertiary-container: '#007876'
  on-tertiary-container: '#9ffefb'
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
  on-secondary-fixed-variant: '#004881'
  tertiary-fixed: '#94f2f0'
  tertiary-fixed-dim: '#77d6d3'
  on-tertiary-fixed: '#00201f'
  on-tertiary-fixed-variant: '#00504e'
  background: '#f9f9ff'
  on-background: '#111c2c'
  surface-variant: '#d8e3fa'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  subhead:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
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
  body-md-medium:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  caption:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system targets healthcare practitioners, pharmacists, and safety-conscious patients navigating complex prescription safety data. The aesthetic is corporate-modern, rigorous, and reassuringly clinical, eliminating ambient anxiety through structured whitespace and disciplined balance. 

By avoiding hyper-dense EHR legacy aesthetics and ungrounded consumer-tech tropes, the system establishes absolute authority and quiet reliability. Every interaction reinforces trust, rapid cognitive clarity, and decisive risk communication.

## Colors

The palette establishes a high-trust clinical environment anchored by an authoritative deep teal and dependable clinical blue, contrasted against a crisp, non-glare surface architecture.

### Core Canvas & Structure
- **Canvas Base:** `#F7FAFC` provides a calm, low-eye-strain backdrop that separates from pure white card modules.
- **Card & Sheet Surface:** `#FFFFFF` offers sterile, high-contrast focus areas.
- **Surface Outline:** `#CBD5E0` delivers clean, structural boundaries for unselected inputs and neutral panels.

### Typography Hierarchy
- **Heading Text:** `#1A202C` delivers unambiguous legibility for drug names, dosages, and critical verdicts.
- **Body & Secondary Copy:** `#4A5568` ensures readable, compliant contrast ratios for explanatory clinical notes and metadata.

### Interactive Accents
- **Primary Action:** `#007782` (Teal). State hover transitions to `#006068`.
- **Secondary Interaction:** `#2B6CB0` (Clinical Soft Blue) handles informational controls, secondary workflows, and neutral navigational elements.
- **Accent Highlight:** `#319795` accents active states, toggles, and positive feedback indicators.

### Clinical Severity Tiers
Severity tiers are strictly paired as high-contrast foreground text over light-tint container fills to prevent visual vibration:
- **High Severity (Critical Interaction):** Text `#BA1A1A` on Container `#FFDAD6`.
- **Moderate Severity (Warning/Caution):** Text `#B7791F` on Container `#FEFCBF`.
- **Low Severity (Notice):** Text `#2B6CB0` on Container `#EBF8FF`.
- **Informational (Neutral Data):** Text `#4A5568` on Container `#EDF2F7`.
- **Unable to Assess (Insufficient Data):** Text `#6B46C1` on Container `#FAF5FF`.

## Typography

The typography uses Inter across all viewports to provide clear, neutral glyph distinctions, crucial for medical abbreviations, numbers, and dosage units (e.g., distinguishing `1`, `l`, and `I`).

- Use tabular figures (`tnum`) for all numerical medical values, dosages, lab values, and timestamps.
- Maintain strict hierarchy: titles clearly lead into contextual body descriptions, with subheads anchoring complex drug-drug interaction summaries.
- Mobile screens switch from `headline-lg` (32px) to `headline-lg-mobile` (24px) to avoid awkward wrapping on complex pharmaceutical names.

## Layout & Spacing

The layout is anchored on an 8pt base grid within a 12-column responsive layout for tablet and desktop viewports, dropping to a 4-column structure on mobile devices.

### Structural Parameters
- **Desktop (>= 1024px):** 12 columns, 2rem section margins, 1.5rem gutters. Max content width cap at 1280px to preserve line-length readability for complex medical monographs.
- **Tablet (768px - 1023px):** 8 columns, 1.5rem margins, 1rem gutters. Side-by-side verification panels stack into tabbed or linear sections.
- **Mobile (< 768px):** 4 columns, 1rem margins, 1rem gutters. Form fields, severity cards, and interaction lists shift to full-width linear stacks.

## Elevation & Depth

Visual hierarchy uses clean planar layering rather than dramatic drop shadows, maintaining an uncluttered, modern clinical feel.

### Shadows & Surfaces
- **Card Resting Level:** `0 4px 20px rgba(0, 119, 130, 0.06)` combined with a crisp 1px `#E2E8F0` border. This teal-tinted ambient glow ties the surface to the primary medical brand color.
- **Hover & Active Panels:** `0 8px 24px rgba(0, 119, 130, 0.10)` with `#CBD5E0` border transition for selectable records or expandable risk cards.
- **Floating Modals & Flyouts:** `0 16px 36px rgba(26, 32, 44, 0.12)`, grounding high-priority interaction dialogues over a `#1A202C` backdrop with 40% opacity.
- **Disclaimers & Banners:** Strictly flat (0dp elevation) with 1px inset or enclosing border lines to convey structural, permanent context rather than dismissible floating UI.

## Shapes

The shape system pairs friendly, approachably rounded exterior perimeters with disciplined inner content geometry.

- **Inputs, Buttons, Dropdowns:** `rounded-lg` (8px). Maintains structural, professional utility.
- **Cards, Clinical Data Containers, Tables:** `rounded-2xl` (16px). Softens large analytical cards without losing functional visual weight.
- **Modals, Dialogs, Bottom Sheets:** `rounded-3xl` (24px). Distinctly separates interactive dialogues from the underlying grid.
- **Severity Badges, Chips, Filter Tags:** `rounded-full` (9999px). Instantly communicates discrete status metadata and tokenized values.

## Components

### Global Banner
- **Format:** Slim fixed or inline strip placed at the top of verification viewports.
- **Style:** Background `#EBF8FF`, border-bottom 1px `#BEE3F8`, text `#2B6CB0` using `body-md-medium`.
- **Content:** "Clinical decision support only. Not a definitive safety declaration. Confirm with a licensed prescriber or pharmacist."
- **Behavior:** Persistent, non-dismissible across all active screening sessions.

### Buttons
- **Primary:** Solid `#007782` background, `#FFFFFF` text, 8px border radius. Hover: `#006068`. Focus ring: 2px offset with `#319795`.
- **Secondary:** Transparent background, 1.5px solid `#007782` border, `#007782` text. Hover: `#007782` at 6% opacity fill.
- **Ghost:** Transparent background, `#007782` text. Hover: `#007782` at 6% opacity fill, no border.
- **Sizing:** Default 40px height (`space-md` horizontal padding); Small 32px height (`space-sm` horizontal padding).

### Chips & Severity Tags
- **Base Style:** `rounded-full` pill, 6px vertical padding, 12px horizontal padding, `label-sm` typography.
- **High Severity:** `#FFDAD6` fill, `#BA1A1A` text, leading alert icon.
- **Moderate Severity:** `#FEFCBF` fill, `#B7791F` text, leading warning icon.
- **Low Severity:** `#EBF8FF` fill, `#2B6CB0` text, leading info icon.
- **Informational:** `#EDF2F7` fill, `#4A5568` text.
- **Unable to Assess:** `#FAF5FF` fill, `#6B46C1` text, leading question/help icon.

### Cards
- **Base:** `#FFFFFF` background, `rounded-2xl` (16px), 1px solid `#E2E8F0`, teal ambient shadow (`0 4px 20px rgba(0, 119, 130, 0.06)`).
- **Interactive State:** Hover elevates to border color `#CBD5E0` and shadow `0 8px 24px rgba(0, 119, 130, 0.10)`.
- **Padding:** 24px (`space-lg`) on desktop; 16px (`space-md`) on mobile screens.

### Input Fields & Selectors
- **Base:** `#FFFFFF` fill, 1px solid `#CBD5E0`, `rounded-lg` (8px), 40px height, text `#1A202C`, placeholder `#A0AEC0`.
- **Active/Focus:** 1.5px solid `#007782` border, outline 3px soft teal glow (`rgba(0, 119, 130, 0.15)`).
- **Error State:** 1.5px solid `#BA1A1A` border with validation caption below in `#BA1A1A`.

### Selection Controls (Checkboxes & Radios)
- **Checkboxes:** 18x18px square, 4px corner radius, `#CBD5E0` unselected border. Selected: `#007782` background with white check icon.
- **Radio Buttons:** 18x18px outer circle, `#CBD5E0` border. Selected: `#007782` outer border with a centered 8px solid `#007782` circle.

### Lists & Drug Interaction Matrices
- **Interaction Row:** Border-bottom 1px `#EDF2F7`, 16px vertical padding. 
- **Layout:** Displays drug names in `headline-md` or `subhead` (`#1A202C`), dosage flags in `body-md` (`#4A5568`), right-aligned severity chip, and expandable mechanism-of-action drawer.
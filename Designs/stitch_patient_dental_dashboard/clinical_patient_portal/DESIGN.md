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
  background: '#f7fafc'
  on-background: '#181c1e'
  surface-variant: '#e0e3e5'
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
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
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
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  margin: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system is crafted for a modern healthcare dental clinic patient portal. The aesthetic centers on a clean, trustworthy, and calming experience designed to reduce patient anxiety. By utilizing professional medical teal and soft blue primary tones against crisp white and light gray backgrounds, the interface establishes an immediate sense of clinical precision paired with genuine warmth. 

Adopting a **Corporate / Modern** design style, the UI relies on structural clarity, generous whitespace, accessible typography, and calm, predictable interaction patterns. Every visual element is optimized for readability, patient comprehension, and effortless navigation across sensitive health records, appointment scheduling, and billing workflows.

## Colors

The color palette is anchored in medical teal (`#007782`), conveying clinical authority and healing, supported by a reassuring soft blue (`#2B6CB0`) for secondary actions and interactive states. A vibrant accent teal (`#319795`) highlights active states and key conversion points like appointment bookings. 

Backgrounds utilize crisp white (`#FFFFFF`) for card surfaces and ultra-clean light grays (`#F7FAFC`) for canvas tiers. Text colors maintain high contrast with dark slate (`#1A202C`) for primary headings and muted charcoal (`#4A5568`) for secondary body copy, ensuring complete WCAG AAA compliance for users of all ages.

## Typography

The typography system uses **Inter**, prized for its exceptional legibility at small sizes and neutral, systematic design. Characterized by clear letterforms and generous counters, it ensures clinical data, dental charts, and billing figures are effortlessly digestible. 

Font sizes scale gracefully from mobile to desktop. Headings above 32px adapt down to 24px on mobile viewports to prevent awkward wrapping in patient dashboard headers. Line heights are kept generous to support reading comfort for patients reviewing complex treatment plans.

## Layout & Spacing

The portal employs a structured **12-column fluid grid** system optimized for desktop dashboards while scaling seamlessly down to single-column stacks on mobile devices. A consistent spacing rhythm based on 4px/8px increments ensures a harmonious, breathable layout that alleviates visual clutter.

- **Breakpoints:** Mobile (< 640px), Tablet (640px – 1024px), Desktop (> 1024px).
- **Margins:** Outer canvas margins scale from 1rem on mobile to 2.5rem on desktop to keep dense medical data neatly framed.
- **Gutters:** Standardized at 1.5rem to maintain clear separation between patient record cards, appointment widgets, and navigation panels.

## Elevation & Depth

Visual hierarchy is communicated primarily through **tonal layers** combined with subtle, ambient shadows. To avoid a sterile clinical feel while maintaining absolute clarity, surfaces are separated using light background shifts paired with extra-diffused, low-opacity shadows (`0 4px 20px rgba(0, 119, 130, 0.06)`). 

Interactive elements such as upcoming appointment cards and primary action buttons lift slightly upon hover, utilizing soft blue and teal shadow tints to reinforce a calming, tactile feedback loop without harsh visual jumps.

## Shapes

The portal adopts a friendly, accessible rounded shape language (Option 2: Rounded). With a base border radius of `0.5rem` for standard inputs and buttons, and scaling up to `1rem` (`rounded-lg`) and `1.5rem` (`rounded-xl`) for primary content cards and modal containers, the interface feels welcoming rather than rigid or intimidating. Sharp corners are entirely avoided to soften the overall visual tone for patients.

## Components

### Buttons
- **Primary:** Solid medical teal background (`#007782`), white text, rounded-md shape, with a subtle hover shade shift (`#006068`).
- **Secondary:** Transparent background with a 1px solid medical teal or neutral border, teal text.
- **Ghost:** Text-only buttons with subtle hover background tints for tertiary actions.

### Input Fields
- Clean white background, 1px neutral border (`#CBD5E0`), rounded-md corners, and clear placeholder text in muted charcoal. Focus states feature a 2px primary teal border with a soft blue-tinted ring for high accessibility.

### Cards
- Surface containers utilizing pure white backgrounds against the light gray canvas, featuring soft rounded corners (`rounded-lg`) and subtle ambient shadows to segment appointment summaries, treatment plans, and billing statements.

### Checkboxes & Radio Buttons
- Generous touch targets (minimum 24px) with high-contrast checked states in medical teal, designed for effortless accessibility across all patient demographics.

### Chips & Badges
- Pill-shaped status indicators used for appointment states (e.g., "Confirmed", "Pending", "Completed") utilizing soft pastel backgrounds with deep-toned text matching the primary and secondary palettes.

### Additional Portal Components
- **Dental Charting Modules:** Interactive tooth-grid components with color-coded status indicators (healthy, crown, cavity, upcoming work).
- **Appointment Timeline:** Vertical step-indicators tracking pre-visit instructions, check-in status, and post-op care.
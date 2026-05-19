---
name: Emerald Civic Portal
colors:
  surface: '#101415'
  surface-dim: '#101415'
  surface-bright: '#363a3b'
  surface-container-lowest: '#0b0f10'
  surface-container-low: '#191c1e'
  surface-container: '#1d2022'
  surface-container-high: '#272a2c'
  surface-container-highest: '#323537'
  on-surface: '#e0e3e5'
  on-surface-variant: '#bbcabf'
  inverse-surface: '#e0e3e5'
  inverse-on-surface: '#2d3133'
  outline: '#86948a'
  outline-variant: '#3c4a42'
  surface-tint: '#4edea3'
  primary: '#4edea3'
  on-primary: '#003824'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#006c49'
  secondary: '#bec6e0'
  on-secondary: '#283044'
  secondary-container: '#3f465c'
  on-secondary-container: '#adb4ce'
  tertiary: '#b9c7e0'
  on-tertiary: '#233144'
  tertiary-container: '#95a4bb'
  on-tertiary-container: '#2c3a4e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#d5e3fd'
  tertiary-fixed-dim: '#b9c7e0'
  on-tertiary-fixed: '#0d1c2f'
  on-tertiary-fixed-variant: '#3a485c'
  background: '#101415'
  on-background: '#e0e3e5'
  surface-variant: '#323537'
typography:
  display-lg:
    fontFamily: Public Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Public Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Public Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Public Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Public Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Public Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style

The design system is a high-contrast, accessibility-first framework designed for public service and civic engagement. It leverages a "Modern Corporate" aesthetic with a "High-Contrast Dark" implementation to ensure maximum legibility and reduced eye strain for citizens.

The emotional response should be one of **authority, security, and efficiency**. By utilizing a deep slate foundation contrasted with a vibrant emerald accent, the UI feels both established and technologically forward-thinking. The style avoids unnecessary decoration, focusing instead on clear information hierarchy and structural integrity.

## Colors

This design system uses a palette optimized for high-contrast accessibility in dark mode. 

- **Primary (Emerald):** The signature emerald green is shifted to `#10b981` (Emerald 500) for UI accents to ensure it "pops" against dark backgrounds while maintaining a AA contrast ratio against the slate foundation for non-decorative elements.
- **Backgrounds:** The core surface uses `#0f172a` (Slate 950). Elevated surfaces and cards use `#1e293b` (Slate 800).
- **Typography:** Primary text is set to `#f8fafc` (Slate 50) for maximum clarity. Secondary text uses `#94a3b8` (Slate 400).
- **Borders:** All structural borders use a low-opacity white `rgba(255, 255, 255, 0.1)` to provide subtle definition without visual clutter.

## Typography

The design system utilizes **Public Sans** for all primary communication. As a typeface designed for government and institutional use, it offers exceptional clarity and neutrality. 

- **Headlines:** Use Bold or Semi-Bold weights with tighter letter spacing for a sturdy, authoritative look.
- **Body:** Standardized on a 16px base for mobile and 18px for desktop to ensure long-form civic documents are readable.
- **Labels:** **JetBrains Mono** is used sparingly for data-heavy labels, timestamps, and ID numbers to evoke a sense of precision and technical reliability.

## Layout & Spacing

The design system follows a **Fixed-Fluid Hybrid** grid model. On desktop, content is constrained to a 1280px central container with a 12-column grid. On mobile, it transitions to a single-column fluid layout.

- **The 8px Square:** All padding and margins must be increments of 8px.
- **Vertical Rhythm:** Use 48px or 64px sections to separate major civic service categories.
- **Gutter Strategy:** A generous 24px gutter ensures that even dense data tables or card grids remain legible and distinct.

## Elevation & Depth

In this high-contrast dark environment, depth is communicated through **Tonal Layering** rather than traditional shadows. 

1. **Base Layer:** `#0f172a` (The void/background).
2. **Content Layer:** `#1e293b` (Cards and containers).
3. **Interactive Layer:** `#334155` (Hover states and active inputs).

**Borders over Shadows:** High-contrast accessibility is maintained by using 1px solid borders (`rgba(255, 255, 255, 0.1)`) for all cards. This ensures that even on screens with low brightness, the boundaries of different tools and services are clearly defined. Avoid heavy drop shadows which can muddy the dark slate background.

## Shapes

The design system uses a **Soft (0.25rem)** rounding strategy. This provides a professional and serious tone while avoiding the "aggressive" sharpness of 0px corners.

- **Primary UI Elements:** (Buttons, Inputs, Small Cards) use 4px (0.25rem) radius.
- **Large Containers:** (Modal overlays, Main Page Sections) use 8px (0.5rem) radius.
- **Status Indicators:** Pills and tags use a fully rounded (999px) radius to distinguish them from interactive buttons.

## Components

- **Buttons:** Primary buttons use the Emerald accent (`#10b981`) with black or very dark slate text for maximum contrast. Secondary buttons are ghost-style with a 1px white-alpha border.
- **Tool Cards:** Cards should have a 1px border of `rgba(255, 255, 255, 0.1)`. On hover, the border opacity should increase to `0.4` and the background should subtly shift to a lighter slate.
- **Input Fields:** Use a dark-filled style (`#1e293b`) with a bottom-border emphasis. Focus states must use a 2px emerald outline for accessibility compliance.
- **Status Chips:** Use high-saturation, low-brightness background tints (e.g., dark red for "Overdue", dark amber for "Pending") with bright text to ensure status is glanceable.
- **Civic Alerts:** Global notifications appear at the top of the viewport using a high-contrast emerald or sapphire background to command immediate attention without appearing "alarmist."
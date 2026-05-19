---
name: Functional Civic
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#3d4947'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#6d7a77'
  outline-variant: '#bcc9c6'
  surface-tint: '#006a61'
  primary: '#00685f'
  on-primary: '#ffffff'
  primary-container: '#008378'
  on-primary-container: '#f4fffc'
  inverse-primary: '#6bd8cb'
  secondary: '#515f74'
  on-secondary: '#ffffff'
  secondary-container: '#d5e3fd'
  on-secondary-container: '#57657b'
  tertiary: '#595c5e'
  on-tertiary: '#ffffff'
  tertiary-container: '#727577'
  on-tertiary-container: '#fbfdff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#89f5e7'
  primary-fixed-dim: '#6bd8cb'
  on-primary-fixed: '#00201d'
  on-primary-fixed-variant: '#005049'
  secondary-fixed: '#d5e3fd'
  secondary-fixed-dim: '#b9c7e0'
  on-secondary-fixed: '#0d1c2f'
  on-secondary-fixed-variant: '#3a485c'
  tertiary-fixed: '#e0e3e5'
  tertiary-fixed-dim: '#c4c7c9'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: Public Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Public Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Public Sans
    fontSize: 24px
    fontWeight: '700'
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
  body-sm:
    fontFamily: Public Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Public Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Public Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
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
  margin-desktop: 32px
  stack-sm: 16px
  stack-md: 32px
  stack-lg: 48px
---

## Brand & Style

The design system is engineered for a modern government utility portal, prioritizing trust, efficiency, and unwavering clarity. The aesthetic balances a "Corporate Modern" foundation with "Minimalist-Brutalist" structural elements—specifically the use of precise 1-pixel borders to define information hierarchy without relying on heavy shadows or decorative flourishes.

The target audience is the general public, requiring a UI that feels authoritative yet accessible. The emotional response should be one of "calm competence." By utilizing a high-contrast palette and a rigid grid, the design system ensures that critical data—such as billing cycles and usage metrics—is processed with minimal cognitive load.

## Colors

The palette is anchored by **Teal (#0d9488)**, which serves as the primary action color. It is used for call-to-actions, progress indicators, and interactive states, providing a sense of renewal and eco-conscious utility management. 

**Slate Gray (#334155)** provides the structural backbone, used for primary typography, icons, and card borders to ensure maximum legibility and an institutional feel. 

- **Primary:** Action-oriented teal for high-priority interactions.
- **Secondary:** Deep slate for content structure and professional grounding.
- **Surface:** A range of cool grays (Slate 50 to 100) are used for background zoning.
- **Contrast:** Maintaining a minimum 4.5:1 ratio is mandatory for all text-to-background combinations to meet AA/AAA accessibility standards.

## Typography

This design system utilizes **Public Sans**, an institutional typeface designed specifically for government interfaces. It offers exceptional legibility across various screen resolutions and maintains a neutral, trustworthy tone.

- **Headlines:** Use Bold (700) or SemiBold (600) weights to establish clear hierarchy.
- **Body Text:** Primarily Regular (400) weight for long-form utility information and instructions.
- **Labels:** Utilized for data descriptors and navigation categories, using SemiBold (600) with slight letter spacing and uppercase styling for distinct separation from body content.
- **Scaling:** On mobile devices, Large Headlines scale down to 24px to prevent excessive line wrapping while maintaining visual impact.

## Layout & Spacing

The layout follows a **fixed-grid philosophy** for desktop to ensure content remains readable on ultra-wide monitors, while adopting a fluid behavior for mobile and tablet views.

- **Grid:** A 12-column grid system is used for desktop (1024px+), shifting to a 4-column grid for mobile.
- **Rhythm:** An 8px base unit governs all spatial decisions. Padding and margins should always be multiples of 8 (e.g., 16, 24, 32, 48).
- **Zoning:** Large vertical sections (Stacks) are separated by 48px or 64px to distinguish between functional areas (e.g., "Active Bill" vs "Usage History").

## Elevation & Depth

This design system intentionally avoids traditional shadows to maintain a clean, contemporary professional appearance. Instead, depth is communicated through **tonal layering and precise outlines**:

- **The Card Style:** Content is housed in cards defined by a **1px border** (Slate #cbd5e1).
- **Surface Hierarchy:** 
    - Level 0: Site background (Slate #f8fafc).
    - Level 1: Primary cards and content blocks (White #ffffff).
    - Level 2: Nested elements or sidebars (Slate #f1f5f9).
- **Interactive Depth:** Only the most critical interactive elements (like a primary "Pay Now" button) may feature a subtle, high-diffusion shadow on hover to provide tactile feedback. Otherwise, all elements remain flat against their respective surfaces.

## Shapes

The shape language is disciplined and geometric. A **Soft (Level 1)** roundedness is applied to UI components to prevent the interface from appearing overly aggressive or "sharp," while maintaining a professional, structured look.

- **Component Corners:** 4px (0.25rem) radius for buttons, inputs, and cards.
- **Large Components:** 8px (0.5rem) radius for large modal containers or featured hero sections.
- **Icons:** Use sharp or slightly rounded 2px corner icons to match the Slate 1px border aesthetic.

## Components

### Buttons
- **Primary:** Solid Teal (#0d9488) with white text. No border.
- **Secondary:** Transparent background with a 1px Slate (#334155) border. 
- **Ghost:** Transparent background with Slate text; used for low-priority navigation.

### Input Fields
- **Default:** White background, 1px Slate (#cbd5e1) border. 
- **Focus:** 2px Teal (#0d9488) border with a subtle 4px Teal-tinted glow (10% opacity).
- **Labels:** Always positioned above the field in Label-MD typography.

### Cards
- **Structure:** 1px Slate (#e2e8f0) border, 24px internal padding, and a 4px corner radius.
- **Header:** Cards containing complex data should include a subtle Slate (#f8fafc) header row to separate the title from the data.

### Chips & Badges
- **Status Badges:** Small, high-contrast pills with 1px borders. (e.g., "Paid" in Teal, "Pending" in Slate).
- **Usage Chips:** Used for filtering usage data, featuring 1px borders that fill with Teal on selection.

### Lists & Tables
- **Data Tables:** Horizontal 1px Slate separators only. No vertical lines. Row highlights use Slate (#f8fafc) on hover to assist with horizontal scanning of utility metrics.
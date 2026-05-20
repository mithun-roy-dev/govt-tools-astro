---
name: GovtFlow Utility
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#404944'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#707974'
  outline-variant: '#bfc9c2'
  surface-tint: '#276a52'
  primary: '#003727'
  on-primary: '#ffffff'
  primary-container: '#00503a'
  on-primary-container: '#7fc1a5'
  inverse-primary: '#91d4b7'
  secondary: '#4f635b'
  on-secondary: '#ffffff'
  secondary-container: '#d1e8dd'
  on-secondary-container: '#556961'
  tertiary: '#003728'
  on-tertiary: '#ffffff'
  tertiary-container: '#09503c'
  on-tertiary-container: '#82c1a7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#adf1d2'
  primary-fixed-dim: '#91d4b7'
  on-primary-fixed: '#002116'
  on-primary-fixed-variant: '#02513b'
  secondary-fixed: '#d1e8dd'
  secondary-fixed-dim: '#b6cbc2'
  on-secondary-fixed: '#0c1f19'
  on-secondary-fixed-variant: '#374b43'
  tertiary-fixed: '#b0f0d4'
  tertiary-fixed-dim: '#94d4b9'
  on-tertiary-fixed: '#002116'
  on-tertiary-fixed-variant: '#0a513d'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
  accent-blue: '#E7F1FF'
  accent-amber: '#FFF3CD'
  accent-purple: '#F3E5F5'
  surface-glass: rgba(255, 255, 255, 0.7)
  border-subtle: '#E9ECEF'
  success-emerald: '#10b981'
  warning-rose: '#f43f5e'
typography:
  headline-lg:
    fontFamily: Hind Siliguri
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Hind Siliguri
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Hind Siliguri
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  bangla-body:
    fontFamily: Hind Siliguri
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.8'
  label-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
  subtitle-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.02em
  caption:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '700'
    lineHeight: '1'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1200px
  section-padding: 64px
  gutter: 24px
  margin-mobile: 16px
  stack-lg: 32px
  stack-md: 16px
  stack-sm: 8px
---

## Brand & Style
GovtFlow is a **Corporate Modern** design system tailored for institutional trust and high-efficiency utility. It blends the reliability of government branding with contemporary **Glassmorphism** and a light touch of **Minimalism**. 

The brand personality is authoritative yet accessible, using a professional emerald green palette to evoke stability and growth. The interface prioritizes clarity for data-heavy tasks while using subtle transitions and backdrop blurs to feel modern and responsive. The goal is to transform complex administrative processes into a friction-less, one-click experience.

## Colors
The palette is rooted in a deep **Deep Emerald (#00503a)** which serves as the anchor for all primary actions and institutional identity. 

- **Primary & Containers**: Use the primary green for headers and main buttons. Utilize high-lightness variants (10-20% opacity) for section backgrounds to maintain brand presence without overwhelming content.
- **Accents**: A set of soft, desaturated pastels (Blue, Amber, Purple) is used exclusively for icon backgrounds within cards to provide categorical distinction.
- **Surface**: The background is a clean, near-white neutral. Glass surfaces with 70% opacity and 12px blur are reserved for sticky navigation components to maintain spatial awareness during scrolling.

## Typography
The system uses a dual-font strategy to optimize for bilingual legibility and professional tone.

- **Hind Siliguri**: Reserved for all Bengali text and major headlines. Its higher line-height (1.8 for body) ensures that complex scripts remain legible.
- **Inter**: Used for all English UI labels, navigation items, and functional metadata. Its neutral, systematic nature balances the more decorative qualities of the Bengali script.
- **Hierarchy**: Headlines use heavy weights (600-700) to stand out against the soft UI. Labels and subtitles use medium weights to ensure clarity at smaller sizes.

## Layout & Spacing
The system employs a **Fixed Grid** model for desktop, centered within a 1200px container to ensure readability on wide screens.

- **Rhythm**: Vertical rhythm is managed through a "stack" system. Use `stack-lg` (32px) between major sections or content groups, and `stack-sm` (8px) between headings and their descriptors.
- **Responsive Behavior**: On mobile, horizontal margins shrink to 16px. The layout reflows from a 4-column grid for cards to a single-column stack.
- **Sticky Elements**: Navigation and category filters are pinned during scroll, using height-compensated offsets to prevent overlap.

## Elevation & Depth
Depth is created through **Tonal Layers** and **Subtle Shadows** rather than high-contrast silhouettes.

- **Low-Level Elevation**: Cards and containers use a 1px border (#E9ECEF) in their resting state.
- **High-Level Elevation**: Upon interaction (hover), elements transition to a floating state using a diffused shadow (`0 12px 24px -10px rgba(0, 0, 0, 0.1)`) and a slight upward translation (-4px).
- **Backdrop Blurs**: Functional overlays and sticky headers use a 12px blur effect with a semi-transparent white tint to separate themselves from the scrolling content beneath without breaking the visual flow.

## Shapes
The shape language is consistently **Rounded**, conveying a modern and user-friendly approachable feel.

- **Cards & Sections**: Use `rounded-xl` (0.75rem or 12px) for a soft, containerized look.
- **Interactive Elements**: Buttons and search inputs use **Full/Pill** rounding to clearly distinguish them from static containers.
- **Icons**: Icon backgrounds use `rounded-xl` to maintain harmony with the card shapes they sit within.

## Components
- **Buttons**: Primary buttons are pill-shaped with high-contrast text. Support/Secondary buttons use subtle container fills (10% primary color) with primary-colored text.
- **Tool Cards**: Feature a vertical layout with an icon in a colored pastel box, a bold headline, and 2 lines of descriptive text. They must include a subtle 200ms transition for transform and shadow.
- **Badges/Tags**: Small, uppercase, and bold. Used for "New" or category status. Positioned either inline or absolute-anchored to the top-right of cards.
- **Search Bar**: A prominent, full-width pill with a persistent left-aligned icon and a high-contrast internal button for the primary action.
- **Category Navigation**: A horizontal scrolling pill-bar with active states highlighted by the primary color and inactive states using desaturated secondary container fills.
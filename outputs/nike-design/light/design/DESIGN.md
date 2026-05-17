---
name: Nike Athlete Recovery System
colors:
  surface: '#F5F5F5'
  surface-dim: '#F5F5F5'
  surface-bright: '#CCCCCC'
  surface-container-lowest: '#FFFFFF'
  surface-container-low: '#F0F0F0'
  surface-container: '#EBEBEB'
  surface-container-high: '#E0E0E0'
  surface-container-highest: '#D5D5D5'
  on-surface: '#141414'
  on-surface-variant: '#555555'
  inverse-surface: '#1a1a1a'
  inverse-on-surface: '#F5F5F5'
  outline: '#888888'
  outline-variant: '#CCCCCC'
  surface-tint: '#2a2a2a'
  primary: '#2a2a2a'
  on-primary: '#F5F5F5'
  primary-container: '#141414'
  on-primary-container: '#888888'
  inverse-primary: '#5e5e5e'
  secondary: '#2a2a2a'
  on-secondary: '#F5F5F5'
  secondary-container: '#CCCCCC'
  on-secondary-container: '#555555'
  tertiary: '#2a2a2a'
  on-tertiary: '#F5F5F5'
  tertiary-container: '#141414'
  on-tertiary-container: '#888888'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#141414'
  primary-fixed-dim: '#2a2a2a'
  on-primary-fixed: '#F5F5F5'
  on-primary-fixed-variant: '#888888'
  secondary-fixed: '#141414'
  secondary-fixed-dim: '#2a2a2a'
  on-secondary-fixed: '#F5F5F5'
  on-secondary-fixed-variant: '#888888'
  tertiary-fixed: '#141414'
  tertiary-fixed-dim: '#2a2a2a'
  on-tertiary-fixed: '#F5F5F5'
  on-tertiary-fixed-variant: '#888888'
  background: '#F5F5F5'
  on-background: '#141414'
  surface-variant: '#D5D5D5'
  recovery-green: '#00FF00'
  surface-border: '#CCCCCC'
  data-neutral: '#888888'
typography:
  display-lg:
    fontFamily: anton
    fontSize: 96px
    fontWeight: '400'
    lineHeight: 90%
    letterSpacing: -0.04em
  display-sm:
    fontFamily: anton
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 90%
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: anton
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 100%
    letterSpacing: 0.02em
  headline-lg-mobile:
    fontFamily: anton
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 100%
  body-lg:
    fontFamily: lexend
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 150%
  body-md:
    fontFamily: lexend
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 150%
  label-bold:
    fontFamily: lexend
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 100%
    letterSpacing: 0.1em
  kpi-numeric:
    fontFamily: anton
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 100%
spacing:
  unit: 4px
  margin-mobile: 16px
  margin-desktop: 32px
  gutter: 16px
  container-max-width: 1440px
---

# Design System: Nike-Inspired Athlete Recovery (Light Theme)

## Visual Direction
- **Aesthetic**: Clean, airy, athletic premium — same elite performance identity in a light context.
- **Color Palette**:
  - Primary: High-contrast near-black (#141414) on soft white surfaces (#F5F5F5, #FFFFFF).
  - Accent: Recovery green (#00FF00) unchanged — strictly for positive recovery signals.
- **Typography**: Unchanged from dark theme. Aggressive editorial typography with tight leading on display sizes.
- **UI Chrome**: Minimal. Thin borders (#CCCCCC), zero to minimal shadows, flat surfaces.
- **Hierarchy**: Strong visual weight on key performance indicators; CTA uses inverted primary-container (#141414).

## Component Guidelines
- **Sidebar**: Minimalist left-aligned navigation — structure unchanged.
- **Cards**: Compact, sharp edges, high contrast on light surfaces.
- **Visualizations**: Circular recovery scores, clean analytics charts.
- **Buttons**: Bold CTA hierarchy — primary-container remains highest-contrast element.

## Light Theme Notes
- `recovery-green` preserved unchanged (brand signal color).
- `surface-border` inverted to #CCCCCC for dividers on light backgrounds.
- Typography and spacing tokens are theme-agnostic and identical to the dark design.

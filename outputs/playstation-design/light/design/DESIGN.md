---
name: PlayStation Athlete Recovery
colors:
  surface: '#F4F6FA'
  surface-dim: '#F4F6FA'
  surface-bright: '#C4C9D4'
  surface-container-lowest: '#FFFFFF'
  surface-container-low: '#EEF1F6'
  surface-container: '#E8ECF2'
  surface-container-high: '#DDE2EA'
  surface-container-highest: '#D0D5DE'
  on-surface: '#141820'
  on-surface-variant: '#4A5260'
  inverse-surface: '#141820'
  inverse-on-surface: '#F4F6FA'
  outline: '#6B7280'
  outline-variant: '#C8CDD6'
  surface-tint: '#0072CE'
  primary: '#0072CE'
  on-primary: '#FFFFFF'
  primary-container: '#0072CE'
  on-primary-container: '#FFFFFF'
  inverse-primary: '#005FAE'
  secondary: '#4A5260'
  on-secondary: '#FFFFFF'
  secondary-container: '#D0D5DE'
  on-secondary-container: '#6B7280'
  tertiary: '#E85D04'
  on-tertiary: '#FFFFFF'
  tertiary-container: '#B75502'
  on-tertiary-container: '#FFF5F1'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#D4E3FF'
  primary-fixed-dim: '#0072CE'
  on-primary-fixed: '#001C3A'
  on-primary-fixed-variant: '#004785'
  secondary-fixed: '#141820'
  secondary-fixed-dim: '#4A5260'
  on-secondary-fixed: '#F4F6FA'
  on-secondary-fixed-variant: '#6B7280'
  tertiary-fixed: '#FFDBC9'
  tertiary-fixed-dim: '#E85D04'
  on-tertiary-fixed: '#321200'
  on-tertiary-fixed-variant: '#753400'
  background: '#F4F6FA'
  on-background: '#141820'
  surface-variant: '#D0D5DE'
  surface-deep: '#FFFFFF'
  surface-canvas: '#F8F9FC'
  surface-card: '#EEF1F6'
  playstation-blue: '#0072CE'
  action-glow: rgba(0, 114, 206, 0.25)
  text-muted: '#6B7280'
  accent-success: '#00F0FF'
typography:
  display-hero:
    fontFamily: bebasNeue
    fontSize: 72px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: 0.05em
  headline-lg:
    fontFamily: sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: sora
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: sora
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  display-hero-mobile:
    fontFamily: bebasNeue
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.1'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  sidebar-width: 280px
  insight-panel-width: 340px
  gutter: 2rem
  section-gap: 4rem
  container-max: 1800px
---

# PlayStation-Inspired Athlete Recovery (Light Theme)

## Visual Direction
- **Aesthetic**: Clean, immersive, premium gaming-inspired UI on airy light surfaces.
- **Color Palette**:
  - Surfaces: Soft cool whites (#F4F6FA, #FFFFFF) with layered containers.
  - Primary CTA: PlayStation blue (#0072CE) unchanged — brand anchor.
  - Accent success: Cyan (#00F0FF) unchanged for positive signals.
- **Typography**: Unchanged — cinematic Bebas Neue hero, Sora headlines, Manrope body.
- **UI Chrome**: Minimal with rounded cards; subtle blue highlights for actionable insights.
- **Hierarchy**: PlayStation blue remains the highest-contrast CTA element.

## Layout & Components
- Structure identical to dark theme: left sidebar, recovery hero, analytics, nutrition widgets, AI insight panel.
- Circular recovery visualization, rounded analytics cards, pill-shaped CTAs preserved.

## Light Theme Notes
- `playstation-blue` and `accent-success` preserved unchanged.
- `action-glow` reduced opacity for light backgrounds.
- Typography, spacing, and rounded tokens are theme-agnostic.

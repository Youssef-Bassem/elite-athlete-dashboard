---
name: SpaceX Engineering Style
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
  primary: '#1A1A1A'
  on-primary: '#F5F5F5'
  primary-container: '#E2E2E2'
  on-primary-container: '#636565'
  inverse-primary: '#5d5f5f'
  secondary: '#555555'
  on-secondary: '#F5F5F5'
  secondary-container: '#CCCCCC'
  on-secondary-container: '#555555'
  tertiary: '#1A1A1A'
  on-tertiary: '#F5F5F5'
  tertiary-container: '#E2E2E2'
  on-tertiary-container: '#636565'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#141414'
  primary-fixed-dim: '#2a2a2a'
  on-primary-fixed: '#F5F5F5'
  on-primary-fixed-variant: '#888888'
  secondary-fixed: '#141414'
  secondary-fixed-dim: '#555555'
  on-secondary-fixed: '#F5F5F5'
  on-secondary-fixed-variant: '#888888'
  tertiary-fixed: '#141414'
  tertiary-fixed-dim: '#2a2a2a'
  on-tertiary-fixed: '#F5F5F5'
  on-tertiary-fixed-variant: '#888888'
  background: '#F5F5F5'
  on-background: '#141414'
  surface-variant: '#D5D5D5'
  background-deep: '#FFFFFF'
  surface-dark: '#F0F0F0'
  divider-subtle: '#CCCCCC'
  status-active: '#1A1A1A'
  status-dimmed: '#888888'
  accent-technical: '#1A1A1A'
typography:
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  body-base:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0.01em
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
    letterSpacing: 0.01em
  mono-label:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  mono-data:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: '1'
    letterSpacing: '0'
spacing:
  unit: 4px
  gutter: 1px
  margin-xs: 0.5rem
  margin-sm: 1rem
  margin-md: 2rem
  margin-lg: 4rem
---

# SpaceX-Inspired Design System (Light Theme)

## Visual Identity
- **Aesthetic**: Ultra-minimal engineering on light surfaces — precision-driven, aerospace-grade.
- **Palette**: Monochrome inversion — soft whites (#F5F5F5, #FFFFFF), near-black text (#141414), technical accents (#1A1A1A).
- **Typography**: Unchanged — restrained Hanken Grotesk, JetBrains Mono for data labels.
- **Hierarchy**: Data-first, extreme whitespace discipline, thin dividers (#CCCCCC) instead of shadows.
- **Atmosphere**: Futuristic, calm, mission-critical.

## Components
- **Layout**: Rigid grid, modular analytics cards — structure unchanged.
- **Indicators**: Status active (#1A1A1A) vs dimmed (#888888); thin progress bars.
- **Navigation**: Minimal sidebar preserved.

## Light Theme Notes
- `accent-technical` inverted from #FFFFFF to #1A1A1A for structural lines on light backgrounds.
- `status-active` inverted to near-black for visibility on light surfaces.
- Typography and spacing tokens are theme-agnostic.

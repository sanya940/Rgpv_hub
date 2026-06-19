---
name: Academic Excellence
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#454652'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#767683'
  outline-variant: '#c6c5d4'
  surface-tint: '#4c56af'
  primary: '#000666'
  on-primary: '#ffffff'
  primary-container: '#1a237e'
  on-primary-container: '#8690ee'
  inverse-primary: '#bdc2ff'
  secondary: '#515f74'
  on-secondary: '#ffffff'
  secondary-container: '#d5e3fc'
  on-secondary-container: '#57657a'
  tertiary: '#400003'
  on-tertiary: '#ffffff'
  tertiary-container: '#670008'
  on-tertiary-container: '#ff635b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e0e0ff'
  primary-fixed-dim: '#bdc2ff'
  on-primary-fixed: '#000767'
  on-primary-fixed-variant: '#343d96'
  secondary-fixed: '#d5e3fc'
  secondary-fixed-dim: '#b9c7df'
  on-secondary-fixed: '#0d1c2e'
  on-secondary-fixed-variant: '#3a485b'
  tertiary-fixed: '#ffdad6'
  tertiary-fixed-dim: '#ffb3ac'
  on-tertiary-fixed: '#410003'
  on-tertiary-fixed-variant: '#930010'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  h1:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  h3:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: '0'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: '0'
  label-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.01em
  button:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  container-max: 1440px
  gutter: 24px
  sidebar-width: 280px
---

## Brand & Style

The brand personality is authoritative yet accessible, designed to instill confidence in students and educators. It balances the rigor of high-level academia with the efficiency of modern productivity software. The target audience includes university students seeking structured knowledge and faculty members organizing curriculum resources.

The design system adopts a **Corporate / Modern** style with a focus on information density and clarity. It utilizes a refined color palette and precise alignment to evoke a sense of digital scholarship. The interface avoids unnecessary ornamentation, ensuring that the content—academic notes—remains the primary focus, while subtle RGPV-inspired accents provide a sense of institutional belonging.

## Colors

The color palette is anchored by "Scholarly Navy" (Primary), representing stability and intelligence. "Professional Slate" (Secondary) is used for secondary UI elements and metadata to provide contrast without competing for attention. 

The background is a "Clean White" to maximize readability. Accents of RGPV’s identity are integrated through a controlled "Heritage Red" (Tertiary) used for critical actions or notifications, and a "Vibrant Blue" (Accent) used for links and interactive states. This creates a high-contrast, legible environment suitable for long study sessions.

## Typography

This design system utilizes **Inter** for all typographic needs to ensure maximum legibility across various screen densities. The scale is built on a modular rhythm that prioritizes a clear vertical hierarchy.

Headlines use tighter letter spacing and heavier weights to feel "anchored" and authoritative. Body text is set with generous line-height to reduce eye strain during reading. Label styles are used for navigation items and metadata, employing a medium weight to maintain visibility at smaller sizes.

## Layout & Spacing

The layout follows a **Fixed Grid** model for the main content area to ensure optimal line lengths for reading, while the sidebar remains fixed to the viewport edge. 

A 12-column system is used for the dashboard, with content typically spanning 8 or 12 columns. The spacing rhythm is based on a 4px baseline grid. Page margins are set to 40px (xl) on desktop to provide "breathing room" for dense academic material. The sidebar uses a consistent 280px width to accommodate deep navigation nesting without feeling cramped.

## Elevation & Depth

Visual hierarchy is established through **Tonal Layers** and **Low-contrast Outlines**. Rather than aggressive shadows, the system uses subtle shifts in background color (e.g., Slate 50 vs. White) to separate the sidebar from the main content.

Card elements utilize a single-pixel border in a soft slate-grey to define their boundaries. For interactive elements like "Semester Cards" or "Search Inputs," a very soft, diffused ambient shadow (4% opacity) is applied on hover to indicate tactility without breaking the clean, flat aesthetic.

## Shapes

The design system employs a **Soft** shape language. This level of roundedness (4px to 8px) strikes a balance between the precision of a traditional academic paper and the approachability of modern software. Large containers like the sidebar or main content panels use 0px or very minimal rounding to maintain a structural, architectural feel, while interactive components like buttons and cards use the standard soft radius.

## Components

### Sidebar Navigation
The sidebar is the primary anchor of the platform. It should feature a clean vertical list of links using "label-sm" typography. Active states are indicated by a Scholarly Navy left-accent bar and a subtle light-grey background fill.

### Prominent Search Bar
The search bar is a top-level component, spanning at least 50% of the content area width. It features a Slate-100 background and a "Professional Slate" icon. When focused, the border transitions to "Scholarly Navy" with a subtle glow effect.

### Semester Cards
Structured cards designed to house course lists. They feature a "h3" header and a list of subjects below. Every card must have a distinct footer area for "Last Updated" metadata.

### Buttons & Inputs
- **Primary Buttons:** Solid Scholarly Navy with white text.
- **Secondary Buttons:** Outlined Slate with Navy text.
- **Input Fields:** Minimalist design with a 1px Slate-200 border, transitioning to Navy on focus.

### Additional Components
- **Progress Steppers:** For tracking course completion.
- **Subject Chips:** Small, rounded labels for tagging notes by topic (e.g., "Maths", "CS").
- **PDF Viewer Toolbar:** A specialized horizontal component for note-viewing actions like zoom, print, and download.
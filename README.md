---
name: Nocturne Elite
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#c6c6c6'
  on-secondary: '#2f3131'
  secondary-container: '#484949'
  on-secondary-container: '#b8b8b8'
  tertiary: '#e3c2ff'
  on-tertiary: '#4a0080'
  tertiary-container: '#d09eff'
  on-tertiary-container: '#602397'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#e3e2e2'
  secondary-fixed-dim: '#c6c6c6'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#464747'
  tertiary-fixed: '#f0dbff'
  tertiary-fixed-dim: '#ddb7ff'
  on-tertiary-fixed: '#2c0050'
  on-tertiary-fixed-variant: '#622599'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
  champagne-gold: '#E5D1B0'
  brushed-silver: '#E2E2E2'
  matte-obsidian: '#121212'
  surface-gray: '#1A1A1A'
  royal-purple: '#2D004F'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 80px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 32px
  margin-desktop: 80px
  margin-mobile: 24px
  section-gap: 160px
---

## Brand & Style

This design system embodies the atmosphere of a high-end, exclusive gala. The brand personality is prestigious, mysterious, and authoritative, targeting a high-net-worth clientele and corporate decision-makers. 

The aesthetic is **Minimalist with an Editorial edge**, prioritizing negative space to let high-resolution photography of event lighting and stage production act as the primary visual driver. The interface should feel like a premium digital concierge: whisper-quiet but unmistakably luxurious. We use high-contrast typography pairings and a restrained color palette to evoke an emotional response of awe and exclusivity.

## Colors

The palette is strictly dark-mode centric, utilizing **Matte Obsidian** (#121212) as the foundation to mimic the dark, light-focused environment of a premium event stage. 

- **Primary Accents:** Muted Champagne Gold is used for interactive elements and critical highlights.
- **Secondary Accents:** Brushed Silver provides a cooler contrast for secondary metadata and borders.
- **Atmospheric Tones:** Deep Royal Purple is reserved for subtle background gradients or "glow" effects, echoing the lighting seen in the reference photography.
- **Text:** High-readability whites and light silvers are used against the dark backgrounds to maintain a crisp, editorial feel.

## Typography

The typography strategy focuses on the "High-Low" pairing of a classical Serif and a functional Sans-Serif. 

- **Headlines:** Use Playfair Display for all major headings. Large display sizes should use tight letter-spacing to feel impactful and cinematic.
- **Body:** Inter provides a clean, neutral balance, ensuring that descriptions of event logistics and services remain highly legible.
- **Micro-copy:** All labels and overlines should use Inter in all-caps with generous letter-spacing to mimic fashion-magazine metadata.

## Layout & Spacing

The layout philosophy is built on **intentional emptiness**. We use a 12-column fixed grid for desktop content, but sections are separated by massive vertical gaps (160px+) to ensure each piece of content is digested as an individual "moment."

- **Desktop:** Wide margins (80px) to frame the content like a gallery piece.
- **Mobile:** Transition to a 4-column grid with reduced vertical spacing, focusing on single-column imagery.
- **Flow:** Layouts should be asymmetrical where possible, placing text and images in a staggered format to guide the eye through the "event experience."

## Elevation & Depth

To maintain the "matte" aesthetic, we avoid traditional drop shadows. Depth is achieved through:

- **Tonal Layering:** Interactive surfaces use #1A1A1A against the #121212 background.
- **Glassmorphism:** Overlays (like mobile menus or image captions) use a high-density background blur (40px+) with a 10% opacity white tint and a 1px brushed silver outline.
- **Light Gels:** Subtle radial gradients in the brand's Royal Purple or Gold can be used behind key components to simulate stage lighting hitting a dark floor.

## Shapes

The design system utilizes **Sharp (0px)** corners for all primary containers, buttons, and images. This architectural approach feels more formal and high-end. 

The only exception to this rule is the brand logo itself. All other UI elements—from input fields to "Book Now" buttons—must maintain 90-degree angles to reinforce the minimalist, structural aesthetic.

## Components

- **Buttons:** Primary buttons are solid Champagne Gold with Matte Obsidian text. Secondary buttons are transparent with a 1px Brushed Silver border and white text. Hover states should involve a slow (400ms) fade or a subtle letter-spacing expansion.
- **Cards:** Cards should have no background by default, utilizing high-resolution imagery that fills the container. Text is placed either below the image or as a glassmorphic overlay at the bottom.
- **Inputs:** Input fields are simple 1px bottom-borders in Brushed Silver. Labels remain small and uppercase above the line.
- **Chips/Badges:** Use small, sharp-edged boxes with a 1px Brushed Silver border and "label-caps" typography for event categories or dates.
- **Lists:** Use wide spacing between list items, separated by low-opacity (10%) silver dividers.
- **Transitions:** Every page transition and modal opening must use a "fade and slide" motion to mimic the smooth dimming of house lights before a show starts.
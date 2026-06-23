---
name: Portal 8 Design System
colors:
  surface: '#faf8ff'
  surface-dim: '#dad9e1'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3fa'
  surface-container: '#eeedf4'
  surface-container-high: '#e9e7ef'
  surface-container-highest: '#e3e1e9'
  on-surface: '#1a1b21'
  on-surface-variant: '#444651'
  inverse-surface: '#2f3036'
  inverse-on-surface: '#f1f0f7'
  outline: '#757682'
  outline-variant: '#c5c5d3'
  surface-tint: '#4059aa'
  primary: '#00236f'
  on-primary: '#ffffff'
  primary-container: '#1e3a8a'
  on-primary-container: '#90a8ff'
  inverse-primary: '#b6c4ff'
  secondary: '#1b6b4f'
  on-secondary: '#ffffff'
  secondary-container: '#a6f2cf'
  on-secondary-container: '#247155'
  tertiary: '#4b1c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#6e2c00'
  on-tertiary-container: '#f39461'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#00164e'
  on-primary-fixed-variant: '#264191'
  secondary-fixed: '#a6f2cf'
  secondary-fixed-dim: '#8bd6b4'
  on-secondary-fixed: '#002115'
  on-secondary-fixed-variant: '#00513a'
  tertiary-fixed: '#ffdbcb'
  tertiary-fixed-dim: '#ffb691'
  on-tertiary-fixed: '#341100'
  on-tertiary-fixed-variant: '#773205'
  background: '#faf8ff'
  on-background: '#1a1b21'
  surface-variant: '#e3e1e9'
typography:
  headline-xl:
    fontFamily: Lexend
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Lexend
    fontSize: 30px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Lexend
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Lexend
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Lexend
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Lexend
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Lexend
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Lexend
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1200px
  gutter: 24px
---

## Brand & Style
The design system is engineered for 8th-grade students (ages 13-14), balancing academic authority with a modern, approachable energy. The brand personality is "The Supportive Mentor"—knowledgeable and structured, but never intimidating or dull.

The visual style is **Modern/Corporate with a Soft Edge**. It utilizes generous whitespace to reduce cognitive load and high-contrast elements to guide focus. By combining clean layouts with vibrant, optimistic accents, the interface feels like a professional tool designed specifically for young learners. The primary goal is to foster a "flow state" by removing visual noise and emphasizing clarity through systematic hierarchy.

## Colors
The palette is rooted in academic stability with "Deep Blue" serving as the primary anchor for navigation and primary actions. "Soft Mint" is used exclusively to denote progress, completion, and positive reinforcement, creating a psychological link between the color and achievement.

The "Warm White" background is slightly desaturated to reduce screen glare during long study sessions. Coral and Amber are used sparingly as functional accents: Coral for urgent alerts or errors, and Amber for "in-progress" states or highlighted tips. All color pairings must meet WCAG AA standards to ensure inclusivity for all learners.

## Typography
Lexend is selected as the sole typeface for this design system due to its specific design intent of improving reading proficiency. For 8th graders managing complex subjects, the expanded character spacing and unique glyph shapes reduce visual crowding.

Headlines use heavier weights (600-700) to create a clear content skeleton. Body text is set at a generous 18px for primary lesson content to ensure maximum legibility. Line heights are kept loose (1.6) to prevent "line-skipping" during fast reading.

## Layout & Spacing
The layout follows a **Fluid Grid** model with a maximum container width of 1200px to prevent line lengths from becoming too long for comfortable reading. 

- **Desktop:** 12-column grid with 24px gutters and 48px side margins.
- **Tablet:** 8-column grid with 20px gutters and 24px side margins.
- **Mobile:** 4-column grid with 16px gutters and 16px side margins.

Vertical rhythm is strictly maintained using multiples of 8px. Large sections (e.g., separating a video lesson from a quiz) utilize the `xl` (80px) spacing to provide a clear mental break between different types of tasks.

## Elevation & Depth
This design system uses **Tonal Layers** combined with **Ambient Shadows** to create a sense of organized depth.

- **Level 0 (Background):** The Warm White surface.
- **Level 1 (Cards/Modules):** Pure white surfaces with a 1px border (#E5E7EB) and a very soft, diffused shadow (0px 4px 20px rgba(30, 58, 138, 0.05)).
- **Level 2 (Interactive/Floating):** Used for hovered states or modals. The shadow becomes more pronounced (0px 10px 30px rgba(30, 58, 138, 0.10)).

Avoid heavy black shadows; instead, use shadows tinted with the Primary Deep Blue to maintain a clean, "airy" feel that doesn't weigh down the interface.

## Shapes
A "Rounded" shape language (0.5rem base) is applied to strike the balance between a professional tool and a student-friendly environment. 

- **Standard Buttons & Inputs:** 8px (0.5rem) radius.
- **Content Cards:** 16px (1rem) radius to feel substantial and "held."
- **Progress Bars:** Fully pill-shaped (rounded-full) to emphasize fluidity and continuous movement.

## Components

### Buttons
- **Primary:** Deep Blue background, white text. High-contrast and bold.
- **Secondary:** Soft Mint background, Deep Blue text. Used for "Next" or "Continue" actions.
- **Ghost:** No background, Deep Blue border and text. Used for secondary navigation or "Cancel."

### Input Fields
Inputs use a white background with a 2px border. The border remains neutral gray (#D1D5DB) in its default state and shifts to Deep Blue on focus with a subtle Soft Mint outer glow to signify "active engagement."

### Progress Indicators
Progress bars should have a thickness of at least 8px. The "track" is a very light version of the Deep Blue, while the "fill" is the Soft Mint. This creates a high-contrast visual cue of completion.

### Cards
Cards are the primary container for lessons and assignments. They should feature a 16px padding as a minimum, using the Level 1 elevation style. Headers within cards should be separated by a subtle horizontal rule.

### Chips/Tags
Used for subject categories (e.g., "Math", "History"). These should be small, pill-shaped, and use low-saturation versions of the accent colors (e.g., pale Amber) to ensure they don't compete with primary action buttons.
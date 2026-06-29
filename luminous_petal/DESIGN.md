---
name: Luminous Petal
colors:
  surface: '#fdf9f5'
  surface-dim: '#ddd9d6'
  surface-bright: '#fdf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ef'
  surface-container: '#f1ede9'
  surface-container-high: '#ebe7e4'
  surface-container-highest: '#e5e2de'
  on-surface: '#1c1c19'
  on-surface-variant: '#524343'
  inverse-surface: '#31302e'
  inverse-on-surface: '#f4f0ec'
  outline: '#847373'
  outline-variant: '#d6c2c1'
  surface-tint: '#855050'
  primary: '#855050'
  on-primary: '#ffffff'
  primary-container: '#e8a5a5'
  on-primary-container: '#6a393a'
  inverse-primary: '#fab5b5'
  secondary: '#6f5959'
  on-secondary: '#ffffff'
  secondary-container: '#f6d9d9'
  on-secondary-container: '#735d5e'
  tertiary: '#745757'
  on-tertiary: '#ffffff'
  tertiary-container: '#d1aeae'
  on-tertiary-container: '#5b4141'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad9'
  primary-fixed-dim: '#fab5b5'
  on-primary-fixed: '#350f11'
  on-primary-fixed-variant: '#6a393a'
  secondary-fixed: '#f9dcdc'
  secondary-fixed-dim: '#dcc0c0'
  on-secondary-fixed: '#271718'
  on-secondary-fixed-variant: '#564242'
  tertiary-fixed: '#ffdad9'
  tertiary-fixed-dim: '#e3bebe'
  on-tertiary-fixed: '#2a1616'
  on-tertiary-fixed-variant: '#5a4040'
  background: '#fdf9f5'
  on-background: '#1c1c19'
  surface-variant: '#e5e2de'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 60px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 42px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.05em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style
The design system transitions from a utilitarian botanical focus to a high-end, editorial aesthetic centered on softness and light. The brand personality is sophisticated, nurturing, and luminous, targeting a discerning audience that appreciates boutique aesthetics and organic growth. 

The design style is a blend of **Minimalism** and **Glassmorphism**. It utilizes expansive "warm white" whitespace to create breathing room, punctuated by high-contrast serif typography that feels like a luxury publication. Subtle translucent layers and soft background blurs are used to suggest the delicacy of flower petals, ensuring the "brighter" directive is felt through luminosity rather than just saturation.

## Colors
The palette shifts from earth-tones to a curated "Dusty Rose" spectrum. 
- **Primary (#E8A5A5):** A soft, sophisticated petal pink used for key actions and brand moments.
- **Secondary (#F4D7D7):** A lighter blush used for tonal backgrounds and hover states.
- **Tertiary (#9E7E7E):** A muted mauve-taupe for text hierarchies and subtle borders, providing necessary contrast without the harshness of pure black.
- **Neutral (#FFFBF7):** A warm cream "Paper" base that provides a softer, more premium feel than clinical white.

Functional colors (Success, Warning, Error) should be desaturated to match the tonal range of the primary palette (e.g., a sage green for success rather than emerald).

## Typography
The typography strategy relies on the tension between the high-contrast, editorial **Playfair Display** for headlines and the clean, approachable **Plus Jakarta Sans** for functional text. 

Headlines should use tight letter-spacing to emphasize their "stylized lettering" quality. Body text maintains generous line-height to ensure readability and a sense of "airiness" across the layout. Labels are set in uppercase with increased tracking to provide a modern, navigational feel that contrasts against the fluid serif headers.

## Layout & Spacing
The design system employs a **Fluid Grid** with generous outer margins to reinforce the premium, "boutique" feel. 

- **Desktop:** 12-column grid with 24px gutters. Use wide 64px margins to "frame" the content like a high-end magazine.
- **Tablet:** 8-column grid with 20px gutters. 
- **Mobile:** 4-column grid with 16px gutters and 20px margins.

Spacing should favor "Macro-white space"—increasing the padding between sections to 80px-120px to maintain the bright, uncluttered aesthetic. Vertical rhythm is based on an 8px base unit.

## Elevation & Depth
Depth is created through **Tonal Layers** and **Glassmorphism** rather than traditional heavy shadows.

- **Level 1 (Base):** The Cream (#FFFBF7) background.
- **Level 2 (Cards/Surface):** White (#FFFFFF) with a very soft, diffused pink-tinted shadow (10% opacity Primary color) to give the impression of elements floating on a cloud.
- **Level 3 (Overlays):** Semi-transparent white with a 12px backdrop blur. This creates a "frosted glass" effect that allows the underlying pink accents to bleed through, enhancing the "luminous" quality.

Avoid solid borders; use subtle tonal shifts in background color to define boundaries.

## Shapes
In alignment with the "Botanical" roots and the "Soft Petal" evolution, the shape language uses **Full Rounding (Pill-shaped)**. This eliminates harsh corners, making every interaction feel organic and gentle. 

Large containers like cards should use `rounded-xl` (3rem/48px) to feel like smooth river stones or soft upholstery. Small elements like buttons and chips should be fully pill-shaped.

## Components
- **Buttons:** Primary buttons are pill-shaped, using a solid Primary pink with white text. Secondary buttons use a ghost style with a Primary border and Primary text. Hover states should include a subtle scale-up effect (1.02x) rather than a drastic color change.
- **Cards:** Use a white background with `rounded-xl` corners and the signature soft pink-tinted shadow. Content within cards should have generous internal padding (min 32px).
- **Input Fields:** Soft cream background with a 1px border in Secondary color. On focus, the border transitions to Primary with a subtle pink outer glow (blur).
- **Chips:** Fully rounded, using the Secondary color for the background and Tertiary for the text. Ideal for tags or categories.
- **Lists:** Separated by thin, low-opacity horizontal lines in the Tertiary color. Include generous vertical padding between list items to maintain the "airy" feel.
- **Image Treatment:** Images should utilize soft, rounded corners and, where possible, a slight warm-toned filter to harmonize with the cream and pink palette.
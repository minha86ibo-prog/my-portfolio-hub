---
name: Organic Sanctuary
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#43483f'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#74796e'
  outline-variant: '#c3c8bc'
  surface-tint: '#49663b'
  primary: '#49663b'
  on-primary: '#ffffff'
  primary-container: '#7a9a6a'
  on-primary-container: '#15300b'
  inverse-primary: '#aed09c'
  secondary: '#7c571b'
  on-secondary: '#ffffff'
  secondary-container: '#ffcc84'
  on-secondary-container: '#795418'
  tertiary: '#5e5e5b'
  on-tertiary: '#ffffff'
  tertiary-container: '#92918d'
  on-tertiary-container: '#2a2a27'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#caedb6'
  primary-fixed-dim: '#aed09c'
  on-primary-fixed: '#062101'
  on-primary-fixed-variant: '#324e26'
  secondary-fixed: '#ffddb1'
  secondary-fixed-dim: '#efbe78'
  on-secondary-fixed: '#291800'
  on-secondary-fixed-variant: '#614003'
  tertiary-fixed: '#e4e2dd'
  tertiary-fixed-dim: '#c8c6c2'
  on-tertiary-fixed: '#1b1c19'
  on-tertiary-fixed-variant: '#474744'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
  ivory-base: '#FFFFFF'
  soft-beige: '#F2EFE9'
  warm-charcoal: '#333333'
  muted-sage: '#7A9A6A'
  earth-gold: '#E2B26D'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 80px
---

## Brand & Style

This design system embodies a premium lifestyle aesthetic centered on the emotional bond between pets and their owners. The brand personality is **warm, cozy, and sophisticated**, moving away from clinical pet care toward a holistic, "home-first" experience. 

The design style is **Modern Minimalist with Tactile warmth**. It prioritizes generous white space and a structured editorial layout to evoke a sense of calm and safety. By combining high-end serif typography with soft, organic UI elements, the system creates a high-trust environment that feels both professional and deeply personal. The visual direction avoids sharp edges and aggressive colors, opting instead for a "sanctuary" feel that reflects organic, premium quality.

## Colors

The color palette is inspired by natural materials and earth tones to reinforce the "Organic & Safe" brand pillar.

- **Primary (Muted Sage):** Used for growth, health, and key action states. It provides a calming, natural focal point.
- **Secondary (Earth Gold):** Reserved for premium accents, badges, and "pro" features to evoke a sense of high-end quality.
- **Tertiary (Ivory & Beige):** These form the structural foundation of the UI. Use `#F9F7F2` for large background areas to reduce eye strain compared to pure white.
- **Neutral (Warm Charcoal):** Used exclusively for text and deep borders. Avoid pure black (`#000000`) to maintain the "cozy" emotional response; the warmth in the charcoal keeps the interface soft.

## Typography

The typography strategy relies on the contrast between the **authoritative elegance of Playfair Display** and the **functional clarity of Manrope**.

- **Headlines:** Always use Playfair Display. For large display moments, use a tighter letter-spacing to emphasize the premium editorial feel.
- **Body Text:** Manrope provides a contemporary, clean look that ensures readability across long-form content about pet health and wellness.
- **Labels:** Use Manrope in SemiBold or Medium weights. Uppercase treatment should be used sparingly for small labels (like "ORGANIC" or "NEW") to add a touch of sophisticated branding.

## Layout & Spacing

This design system utilizes a **Fixed Grid** on desktop and a **Fluid Grid** on mobile devices. 

- **Desktop:** A 12-column grid with a maximum width of 1280px. Centering the content creates a "boutique" feel. 
- **Rhythm:** Use an 8px base unit. Section vertical spacing is intentionally generous (80px+) to allow the high-end photography and typography to breathe.
- **Mobile:** Transition to a 4-column fluid layout with 20px side margins. Padding within cards and containers should remain ample to maintain the "light and airy" aesthetic.

## Elevation & Depth

Depth is conveyed through **Tonal Layers** and **Ambient Shadows** rather than stark borders.

- **Surface Strategy:** Use the Ivory base (`#FFFFFF`) for the primary canvas and Soft Beige (`#F2EFE9`) for secondary containers or section backgrounds.
- **Shadows:** Shadows must be extremely soft and diffused. Use a "tinted" shadow approach: instead of grey, use a low-opacity version of the warm charcoal or a deep muted sage for elements sitting on green backgrounds. 
- **Blur:** High blur radius (20px+) with very low opacity (5-8%) creates a "lifted paper" effect that feels tactile and high-end.

## Shapes

The shape language is **distinctly organic and rounded**. 

Standard components (buttons, inputs) use a 0.5rem (8px) radius. Larger cards and containers should utilize `rounded-xl` (1.5rem / 24px) to emphasize the "soft and safe" brand promise. Avoid sharp 90-degree angles entirely, as they conflict with the "warm and cozy" emotional goal. Decorative elements or image containers may occasionally use asymmetrical "organic" radii or leaf-like shapes to reinforce the organic theme.

## Components

- **Buttons:** Primary buttons use the Muted Sage background with white text. Secondary buttons should use a Soft Beige background with Sage text. Shapes are consistently rounded.
- **Input Fields:** Use a subtle Ivory background with a 1px Soft Beige border. On focus, the border transitions to Muted Sage. Avoid heavy shadows on inputs to keep them looking clean.
- **Cards:** White or Ivory backgrounds with a "Lifted" shadow style. Use generous internal padding (min 24px) and rounded corners (24px).
- **Chips/Badges:** Use Earth Gold for "Premium" or "Organic" markers with an uppercase Manrope label for an editorial look.
- **Lists:** Use custom icons (like a small leaf or paw) instead of standard bullets. Line heights in lists should be increased to maintain the airy aesthetic.
- **Imagery:** Photography should be warm-toned, featuring pets in soft, natural light within clean, modern home environments.
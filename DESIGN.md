---
name: Athereal Bridal
colors:
  surface: '#fafaeb'
  surface-dim: '#dbdbcd'
  surface-bright: '#fafaeb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f5e6'
  surface-container: '#efefe0'
  surface-container-high: '#e9e9db'
  surface-container-highest: '#e3e3d5'
  on-surface: '#1b1c14'
  on-surface-variant: '#524345'
  inverse-surface: '#2f3128'
  inverse-on-surface: '#f1f2e3'
  outline: '#857374'
  outline-variant: '#d7c1c3'
  surface-tint: '#8c4b55'
  primary: '#8a4853'
  on-primary: '#ffffff'
  primary-container: '#a6606b'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb2bc'
  secondary: '#685d4a'
  on-secondary: '#ffffff'
  secondary-container: '#eddec5'
  on-secondary-container: '#6c614e'
  tertiary: '#6e5659'
  on-tertiary: '#ffffff'
  tertiary-container: '#886e71'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9dd'
  primary-fixed-dim: '#ffb2bc'
  on-primary-fixed: '#3a0915'
  on-primary-fixed-variant: '#70343e'
  secondary-fixed: '#f0e0c8'
  secondary-fixed-dim: '#d3c5ad'
  on-secondary-fixed: '#221b0b'
  on-secondary-fixed-variant: '#4f4533'
  tertiary-fixed: '#fbdbde'
  tertiary-fixed-dim: '#debfc2'
  on-tertiary-fixed: '#281719'
  on-tertiary-fixed-variant: '#574144'
  background: '#fafaeb'
  on-background: '#1b1c14'
  surface-variant: '#e3e3d5'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  subheading-lg:
    fontFamily: Libre Caslon Text
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.5'
  body-rt:
    fontFamily: Poppins
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Poppins
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
  section-gap: 120px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style
The design system is crafted for a high-end bridal artistry experience, blending timeless elegance with modern digital sophistication. The brand personality is ethereal, intimate, and meticulously curated, evoking a sense of calm luxury and "once-in-a-lifetime" importance.

The visual style employs a **refined Glassmorphism** mixed with **Minimalist** layouts. It relies on expansive whitespace to create a "breathable" luxury feel, allowing high-resolution photography of bridal work to remain the focal point. Subtle glows and soft gradients mirror the luminosity of bridal makeup, while thin gold outlines provide a structural, jewelry-like precision to the interface.

## Colors
The palette is a sophisticated harmony of metallic tones and soft organic hues.
- **Primary (Rose Gold):** Used for interactive elements, primary call-to-actions, and key brand moments.
- **Secondary (Champagne Gold):** Utilized for thin decorative borders, icons, and subtle accents that signify premium quality.
- **Tertiary (Soft Pink):** Applied to secondary surfaces, hover states, and gentle highlights.
- **Neutrals (Ivory, Beige, Light Cream):** These form the foundation of the UI, replacing harsh grays to maintain a warm, inviting, and skin-tone-adjacent aesthetic.
- **White:** Used strictly for the highest-level surfaces and background layers to maximize clarity.

## Typography
The typography strategy creates a high-contrast hierarchy between editorial flair and functional clarity.
- **Headlines:** Playfair Display delivers an authoritative, high-fashion editorial feel. Use generous tracking for a more "airy" appearance in uppercase titles.
- **Subheadings:** Libre Caslon Text (serving as a refined alternative to Cormorant) provides a literary, traditional bridal touch. Use italics frequently for testimonials or descriptive labels.
- **Body & UI:** Poppins ensures maximum readability and a modern, clean contrast to the serif headings. It keeps the booking flows and service lists feeling efficient and professional.

## Layout & Spacing
This design system utilizes a **Fixed Grid** for desktop to maintain the integrity of white space and "centered" editorial layouts. 
- **Desktop:** 12-column grid with wide 80px margins to frame the content like a luxury magazine.
- **Section Gaps:** Aggressive vertical spacing (120px+) is used between major sections to emphasize exclusivity and prevent the UI from feeling cluttered.
- **Mobile:** A 4-column fluid grid with 20px margins. Typography scales down significantly to ensure the serif headlines remain elegant and do not wrap awkwardly.

## Elevation & Depth
Depth is communicated through **Glassmorphism** and soft environmental glows rather than traditional shadows.
- **Surfaces:** Use semi-transparent Ivory (#FFFFF0) backgrounds with a 12px-20px backdrop blur for modals and navigation bars.
- **Glows:** Apply a soft, low-opacity outer glow using Rose Gold (#B76E79) for primary buttons and featured cards to simulate a "lit-from-within" radiance.
- **Outlines:** Instead of shadows, use 1px solid or gradient strokes in Champagne Gold (#F7E7CE) at 30-50% opacity to define boundaries.

## Shapes
The shape language is **Soft (0.25rem)**, leaning towards architectural precision. 
- **Cards & Inputs:** Use the base `rounded` (4px) setting to keep the look crisp and modern.
- **Buttons:** Can alternate between sharp corners for high-fashion "Editorial" buttons and pill-shaped for "Functional" booking buttons.
- **Images:** Bridal portraits should occasionally feature an "arch" mask (rounded-top) to mimic classic bridal stationery and cathedral architecture.

## Components
- **Buttons:** Primary buttons use a solid Rose Gold fill with white Poppins text. Secondary buttons are "Ghost" style with a thin Champagne Gold outline and an elegant hover glow.
- **Cards:** Use "Glass" backgrounds with a subtle 1px border. Content inside cards should be center-aligned to enhance the premium feel.
- **Input Fields:** Minimalist design with only a bottom border in Light Beige, which transitions to Rose Gold on focus. Labels use the `label-sm` Poppins style with wide tracking.
- **Lists:** Service lists should use decorative Champagne Gold icons (e.g., a thin sparkle or floral motif) instead of standard bullets.
- **Navigation:** A sticky top bar with a heavy backdrop blur, featuring a centered logo and spaced-out Poppins links in uppercase.
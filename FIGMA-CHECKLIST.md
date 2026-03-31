# Figma Build Checklist (Mapped to This Site)

## 1) Foundation Setup
- Create a Figma page named "Web Starter".
- Set desktop frame width to 1440 and mobile frame width to 390.
- Add an 8px spacing system and use it consistently.
- Add color styles from CSS variables in [css/style.css](css/style.css):
  - `--sage` #8B9D83
  - `--teal` #4A7C7E
  - `--gray-dark` #2C3333
  - `--gray-medium` #6B7280
  - `--gray-light` #F3F4F6
  - `--gold` #C9A961
  - `--white` #FFFFFF

## 2) Type System
- Add text styles for:
  - Display H1 (Fraunces, bold)
  - Section H2/H3 (Fraunces or Manrope depending on emphasis)
  - Body (Manrope regular)
  - Eyebrow label (Manrope bold, uppercase, spaced)
- Keep a clear type scale matching the site hierarchy:
  - H1 large display
  - Subtitle medium
  - Body comfortable reading size

## 3) Components to Create
- Button component:
  - Primary: teal gradient fill, white text, pill shape
  - Secondary: light background, dark text, subtle border
- Card component:
  - Soft white surface
  - Rounded corners
  - Thin border with low-contrast tint
  - Subtle shadow
- Top navigation component:
  - Left logo, right links, active state underline

## 4) Sections to Recreate
- Home hero panel from [index.html](index.html):
  - Eyebrow + H1 + subtitle + supporting paragraph + two buttons
- Feature card strip from [index.html](index.html):
  - 3 cards, equal width on desktop, stacked on mobile
- About page hero and content cards from [about.html](about.html)
- Contact page hero and contact cards from [contact.html](contact.html)

## 5) Responsive Rules
- Desktop: multi-column cards.
- Mobile: stack cards into one column.
- Keep hero padding reduced on mobile.
- Maintain readable line lengths for body text.

## 6) Handoff Checklist
- Name layers using semantic names (Hero/Title, Card/Body, Button/Primary).
- Use Auto Layout in all reusable components.
- Define component variants for hover/default button states.
- Export SVG for icons and PNG/WebP for image assets.
- Validate spacing, font sizes, and colors against [css/style.css](css/style.css).

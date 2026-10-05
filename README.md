# Crave House — WEDE5020 Part 2

## Project
Crave House is a responsive snack-shop website developed for the WEDE5020 Part 2 brief. This version builds on the Part 1 site and applies the Part 2 feedback and CSS/responsive-design requirements.

## GitHub repository
Original remote repository: https://github.com/ST10512270-Thapelo-Sonono/CraveHouse

## Part 2 requirements addressed

- **External stylesheet:** All pages link to `CSS/styles.css`.
- **Base styling:** Consistent typography, colour palette, spacing, reset and `box-sizing` are defined centrally.
- **Typography:** Uses `font-family`, responsive `font-size`, `font-weight`, `line-height`, and `letter-spacing`.
- **Layout:** CSS Grid is used for product/location layouts; Flexbox is used for branding and navigation.
- **Visual styling:** Colours, gradients, borders, rounded corners and box shadows create the existing Crave House Y2K visual identity.
- **Interactive states:** `:hover`, `:focus-visible`, `:active` and `:focus-within` are included for navigation, buttons, forms and product cards.
- **Responsive breakpoints:** Desktop, tablet and mobile layouts are defined with media queries.
- **Relative units:** `rem`, `em`-compatible responsive sizing, `%`, `vw`, `clamp()`, and `min()` are used for responsive dimensions.
- **Responsive images:** Product/logo images include `srcset` and `sizes`; smaller image variants are supplied in `Media/`.
- **Mobile layout:** Product cards change from four columns to two columns and then a single column; navigation also stacks on small screens.
- **Forms:** Enquiry and contact forms have labels, validation and demonstration submit feedback.

## Changelog — Part 2

### Changes made from Part 1
1. Rebuilt all five HTML pages with valid, consistent structure and semantic elements.
2. Corrected inconsistent file paths such as `/CSS/styles.css`, `media/`, and `js/` so the site works from the repository root.
3. Removed duplicate/malformed closing tags from the original header/product markup.
4. Consolidated all visual styling into the external `CSS/styles.css` file.
5. Added Flexbox navigation and branding layout.
6. Added CSS Grid product layouts with responsive desktop/tablet/mobile breakpoints.
7. Added responsive typography and relative spacing units.
8. Added responsive image variants and `srcset`/`sizes` attributes.
9. Added hover, focus, active and focus-within interaction states.
10. Improved form accessibility with labels, autocomplete attributes and live status messages.
11. Added responsive map containers and cleaned up the duplicated location markup on the Contact page.
12. Added this README with the Part 2 changelog and testing evidence.
13. Removed the accidental nested Part 1 repository directory from the working submission copy.

## Testing evidence

The site was tested locally at the following viewport sizes:

| Device target | Viewport | Evidence |
|---|---:|---|
| Desktop | 1440 × 900 | `screenshots/desktop-home.png` |
| Tablet | 768 × 1024 | `screenshots/tablet-products.png` |
| Mobile | 390 × 844 | `screenshots/mobile-products.png` |

### What was checked
- Navigation remains usable at all three widths.
- Product grid changes from 4 columns → 2 columns → 1 column.
- Images scale within their cards without horizontal overflow.
- Typography and spacing remain readable on small screens.
- Buttons have visible hover/focus/active styling.
- Forms remain usable at mobile width.
- All local CSS/JS/image paths point to files inside the project.

## Submission contents

- `index.html`
- `about.html`
- `products.html`
- `enquiry.html`
- `contact.html`
- `CSS/styles.css`
- `JS/script.js`
- `Media/` original and responsive image assets
- `screenshots/` responsive testing evidence
- `README.md`

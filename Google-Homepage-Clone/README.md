# Google Homepage Clone — Week 1 Assignment

A student-made, Google-inspired homepage created for a one-month mentorship program. This is an educational visual clone, not an official Google service. It does not perform real web searches and does not collect user data.

## Project files

- `index.html` — semantic page structure, navigation, search form, buttons, and footer.
- `styles.css` — page styling, layout, typography, focus states, and responsive breakpoints.
- `assets/` — reserved for optional local assets; this version uses inline SVG icons and CSS text for the logo.

## How to open

1. Extract the project folder if it is in a ZIP file.
2. Open `index.html` in a modern browser such as Chrome, Firefox, or Edge.
3. Resize the browser or use Developer Tools' device toolbar to check desktop and mobile layouts.

No build tools or dependencies are required.

## Layout methods used

- **Flexbox** for the top navigation, page shell, and footer link groups.
- **CSS Grid** for the decorative apps icon.
- **Media queries** to adapt spacing and controls for tablet/mobile-sized screens.
- **CSS custom properties** for reusable colours.
- Semantic HTML elements (`header`, `nav`, `main`, `form`, and `footer`) to make the structure easier to understand.

## Accessibility

- The search field has a visually hidden label.
- Decorative SVG icons are hidden from assistive technology.
- Links, buttons, and form controls have visible keyboard focus states.
- The layout supports reduced-motion preferences and narrow screens.

## One challenge solved

Keeping the footer near the bottom on tall screens while allowing the main search section to remain flexible. The page shell uses a column flex layout with the main content set to `flex: 1`, rather than relying on fixed pixel positioning. Media queries also reduce gaps and hide one optional icon on very narrow screens to avoid horizontal overflow.

## Scope note

The search form is intentionally a demo. Submitting it shows a message instead of sending a query to a search engine. No sign-in, authentication, or Google account functionality is included.

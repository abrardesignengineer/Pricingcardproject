Build SaaS pricing table using CSS Flexbox

## Flexbox Pricing Table — HTML & CSS

**Project:** Built a responsive SaaS pricing table with three plans: Basic, Standard and Premium.

### Concepts Practiced

**1. Flexbox fundamentals**
- `display: flex` to create flex containers.
- `flex-direction: row` and `column` to control layout direction.
- Understanding the main axis and cross axis.
- `justify-content` for main-axis alignment.
- `align-items` for cross-axis alignment.
- Understanding why `align-content` is used for multiple flex lines.
- `gap` for consistent spacing between flex items.

**2. Parent and child alignment**
- Used `.pricing-container` to position the three pricing cards.
- Used `.pricing-plan` as an independent flex container to align its internal content.
- Practiced nested Flexbox layouts.
- Used `min-height: 100vh` to provide sufficient vertical space for viewport-level centering.

**3. Sizing and spacing**
- Practiced `width`, `max-width`, and `padding`.
- Used `flex: 1` and observed how flex-grow affects available space.
- Learned the difference between `padding` and `gap`.
- Investigated default browser margins and padding on `<ul>` elements.

**4. Typography and visual styling**
- Integrated Google Fonts (Sono).
- Practiced `font-size` and `font-weight`.
- Styled pricing cards, headings, feature lists and buttons.

### Key Lessons
- Flexbox alignment depends on the available space inside the parent.
- The main axis changes when `flex-direction` changes.
- `justify-content` and `align-items` solve different alignment problems.
- Nested flex containers can independently control parent and child layouts.
- Layout, sizing, spacing and typography are separate parts of CSS styling.

**Outcome:** Recreated a three-column SaaS pricing table from a visual reference using HTML and CSS.

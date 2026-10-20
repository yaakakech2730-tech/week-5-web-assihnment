
# SpendWise Dashboard Shell

## Project Overview

SpendWise is a responsive personal finance dashboard created using HTML5 and CSS3. It presents a visual overview of financial information using static sample data.

## Project Files

- `index.html`: Contains the sidebar, header, financial summaries, six spending category cards, recent transactions, and footer.
- `style.css`: Defines the visual theme, Grid and Flexbox layouts, responsive breakpoints, card interactions, and optional dark theme.
- `README.md`: Documents the project structure and implementation.

## CSS Grid

CSS Grid is used for the overall dashboard layout, financial summary cards, spending category cards, navigation layout on mobile, and responsive form-like content arrangements.

## Flexbox

Flexbox is used to align the sidebar navigation items, header content, category card content, transaction rows, and footer elements.

## Theme Variables

The `:root` selector defines custom properties for brand colour, accent colour, backgrounds, surfaces, borders, and text colours. These variables are reused throughout the stylesheet.

## Responsive Design

Below 768px, the dashboard changes to a single-column page layout. The sidebar becomes a compact navigation area, and the summary and category cards adapt to the available width. Below 480px, the cards stack into a single column.

## Card Micro-interactions

Dashboard category cards use a 200ms transition on hover and keyboard focus. The card moves slightly upward and gains a shadow and accent border. Keyboard users can reach the cards using the Tab key.

## Dark Theme

The optional dark theme uses `prefers-color-scheme: dark` and overrides the root theme variables.

## How to Run

1. Place `index.html`, `style.css`, and `README.md` in the same directory.
2. Open `index.html` in a web browser.
3. Use the browser's DevTools Device Toolbar to test the layout at mobile and desktop widths.
4. An internet connection is required for the Google Fonts.

## Limitations

The financial figures are sample data for demonstration only. The dashboard does not yet store transactions or calculate actual balances. No JavaScript functionality is included.

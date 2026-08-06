## 2025-02-23 - Retrofitting Table-Based Calculator for Accessibility
**Learning:** Legacy tables used for layouts often lack fundamental screen-reader and keyboard accessibility. Retrofitting `role="button"`, `tabindex="0"`, descriptive `aria-label`s, and custom keyboard event listeners to table-cell elements (`<td>`) makes them fully interactive and keyboard-navigable without requiring structural HTML changes.
**Action:** When working on legacy layout grids, apply ARIA properties and map Enter/Space keys to cell click events while ensuring appropriate visual focus-visible indicators.

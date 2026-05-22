## 2025-05-14 - [Accessibility] Table cells as interactive buttons
**Learning:** Using `<td>` elements for calculator buttons without explicit accessibility attributes makes the interface completely unusable for keyboard and screen reader users. Simply adding `onclick` is insufficient for modern web standards.
**Action:** Always inject `role="button"`, `tabindex="0"`, and descriptive `aria-label` attributes to interactive table cells. Ensure keyboard event listeners for 'Enter' and 'Space' are implemented to achieve full parity with mouse interactions.

## 2025-05-14 - Accessible Custom Buttons

**Learning:** When using non-semantic elements like `<td>` as interactive buttons, they are invisible to keyboard and screen reader users unless explicitly enhanced. This requires `role="button"`, `tabindex="0"`, descriptive `aria-label`, and JavaScript listeners for Enter/Space keys.

**Action:** Always verify that interactive elements use semantic tags (like `<button>`) or have full ARIA and keyboard navigation parity if using custom elements.

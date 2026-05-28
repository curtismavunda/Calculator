## 2025-05-14 - Prevent 'undefined' in Calculator Display
**Learning:** In simple JS calculators, uninitialized result variables or missing early returns in the equals handler can lead to 'undefined' being displayed, which is confusing for users. Accessibility attributes like aria-live="polite" are essential for ensuring screen reader users receive calculation results.
**Action:** Always implement early returns for missing operators and ensure display inputs are 'readonly' to prevent invalid manual input while remaining focusable.

## 2025-05-14 - Keyboard Navigation for Custom Table Buttons
**Learning:** Using <td> as buttons requires explicit 'role="button"' and 'tabindex="0"' for accessibility, along with manual listeners for 'Enter' and 'Space' keys. Browser-default focus indicators can be obscured by table borders.
**Action:** Use 'position: relative' and 'z-index: 1' on focused cells to ensure the outline remains visible over adjacent borders.

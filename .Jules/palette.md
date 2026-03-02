## 2025-05-22 - Dynamic Accessibility Enhancement for Legacy Tables
**Learning:** Legacy table-based interfaces can be made highly accessible without restructuring the HTML by dynamically injecting ARIA roles, tabindex, and keyboard listeners via JavaScript.
**Action:** Use a script to loop through interactive elements and apply 'role="button"', 'tabindex="0"', and descriptive 'aria-label' attributes. Implement a global 'keydown' listener for common shortcuts.

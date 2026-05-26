## 2025-05-26 - [Ensuring Accessible Custom Buttons]
**Learning:** In a project using tables or divs as buttons, simply adding `onclick` is insufficient for accessibility. Adding `role="button"`, `tabindex="0"`, and `aria-label` (especially for icons/operators like 'x') alongside keyboard listeners for 'Enter' and 'Space' is essential for keyboard and screen reader support.
**Action:** Always check for non-semantic interactive elements and apply the ARIA role, tabindex, and keyboard listener pattern.

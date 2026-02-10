## 2026-02-10 - [Accessible Table Buttons]
**Learning:** Using '<td>' elements as interactive buttons is a common accessibility anti-pattern. They lack default focusability, ARIA roles, and keyboard support.
**Action:** Use a script to dynamically apply 'role="button"', 'tabindex="0"', and 'keydown' listeners to interactive cells. Use 'event.stopPropagation()' in these listeners to prevent double-triggering when combined with global keyboard shortcuts.

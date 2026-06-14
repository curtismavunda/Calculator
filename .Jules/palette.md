## 2025-05-14 - Retrofitting Accessibility to Legacy Table-UI
**Learning:** Legacy table-based layouts for interactive components (like calculators) often lack basic accessibility (roles, tabindex). These can be efficiently retrofitted using a centralized DOMContentLoaded script to inject 'role="button"', 'tabindex="0"', and ARIA labels without requiring a full HTML redesign.
**Action:** Use centralized script injection for a11y attributes when working with legacy or static HTML that shouldn't be heavily modified.

## 2025-05-14 - Global vs. Local Keyboard Listeners
**Learning:** Adding global keyboard shortcuts (e.g., number keys for a calculator) alongside local listeners on focused elements can lead to double-triggering or state conflicts. Using 'event.stopPropagation()' on local listeners and 'event.preventDefault()' is essential for clean interaction.
**Action:** Always ensure local keyboard listeners stop propagation if they handle a key that is also handled by a global listener.

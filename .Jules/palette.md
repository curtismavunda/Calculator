## 2025-05-14 - Retrofitting Accessibility to Legacy Table UIs
**Learning:** For legacy projects using `<table>` and `<td>` for interactive components (like calculators), a centralized `DOMContentLoaded` script can efficiently inject `role="button"`, `tabindex="0"`, and keyboard listeners. This provides full keyboard and screen reader support without requiring extensive HTML refactoring.
**Action:** Use a centralized script to inject a11y attributes and handle keyboard events (Enter/Space) when working with non-semantic interactive elements.

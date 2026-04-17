## 2025-05-14 - Dynamic Accessibility Injection for Table-based UI
**Learning:** In legacy table-based interfaces where cells function as buttons, dynamic injection of ARIA roles, tabindex, and keyboard listeners via JavaScript is a clean way to improve accessibility without cluttering the HTML or exceeding PR line limits.
**Action:** Use a `DOMContentLoaded` listener to iterate over interactive elements (e.g., `td[onclick]`) and apply `role="button"`, `tabindex="0"`, and custom `aria-labels` based on text content.

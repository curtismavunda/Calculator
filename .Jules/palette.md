## 2025-05-14 - Retrofitting Accessibility to Table-Based UI
**Learning:** Legacy interfaces using non-semantic elements (like <td> for buttons) can be made accessible without a full HTML refactor by using a centralized JavaScript initialization script to apply ARIA roles, tabindex, and event listeners.
**Action:** Use a DOMContentLoaded script to iterate over interactive elements and programmatically enhance them with necessary accessibility attributes and keyboard support.

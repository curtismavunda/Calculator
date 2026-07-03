## 2025-05-14 - Retrofitting Accessibility to Legacy Table UIs
**Learning:** For legacy projects using table-based layouts for interactive elements (like <td> as buttons), a centralized DOMContentLoaded script can efficiently inject ARIA roles, tabindex, and keyboard listeners without requiring a complete HTML refactor.
**Action:** Use a mapping object for ARIA labels and a global keyboard listener to provide physical keyboard support alongside element-level accessibility.

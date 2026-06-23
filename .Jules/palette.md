## 2025-05-14 - Retrofitting Accessibility to Table-Based UI
**Learning:** Retrofitting accessibility (role, tabindex, listeners) to legacy table-based UI elements like <td> using a centralized DOMContentLoaded script is an efficient UX pattern that avoids heavy HTML refactoring while ensuring keyboard and screen reader support.
**Action:** Use a centralized script to inject ARIA attributes and keyboard listeners for legacy components that lack native interactive semantics.

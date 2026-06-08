## 2026-06-08 - Enhanced Accessibility for Table-based UI
**Learning:** Retrofitting accessibility (role, tabindex, listeners) to legacy table-based UI elements like <td> using a centralized DOMContentLoaded script is an efficient UX pattern that avoids heavy HTML refactoring while ensuring keyboard and screen reader support.
**Action:** Use document.querySelectorAll('td[onclick]') to target interactive elements and inject accessibility attributes dynamically when working with legacy table layouts.

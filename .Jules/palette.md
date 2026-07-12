## 2025-07-12 - Retrofitting Accessibility to Legacy Tables
**Learning:** Retrofitting accessibility (role, tabindex, listeners) to legacy table-based UI elements like <td> using a centralized DOMContentLoaded script is an efficient UX pattern that avoids heavy HTML refactoring while ensuring keyboard and screen reader support.
**Action:** Use a mapping object for ARIA labels and a loop to apply attributes/listeners to interactive non-button elements to maintain clean HTML while improving a11y.

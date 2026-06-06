## 2025-05-14 - Accessible Table-based Calculator
**Learning:** Retrofitting accessibility (role, tabindex, aria-label, and listeners) to legacy table-based UI elements like <td> using a centralized DOMContentLoaded script is an efficient UX pattern that avoids heavy HTML refactoring while ensuring keyboard and screen reader support. Adding aria-live to the display input ensures screen reader users hear results immediately.
**Action:** Use a centralized script to inject accessibility attributes and listeners when dealing with legacy or non-semantic interactive elements.

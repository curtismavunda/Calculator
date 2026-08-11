# Palette's Journal

## 2024-08-11 - Dynamic Keyboard and Accessibility Retrofitting
**Learning:** Retrofitting accessibility (role, tabindex, listeners) to legacy table-based UI elements like <td> using a centralized DOMContentLoaded script is an efficient UX pattern that avoids heavy HTML refactoring while ensuring keyboard and screen reader support.
**Action:** Use dynamic JS loops to inject tabindex, role, and ARIA labels on legacy table components, and attach keyboard listeners to trigger clicking on Space/Enter.

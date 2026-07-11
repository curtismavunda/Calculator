## 2026-07-11 - Retrofitting Accessibility to Table-based UI
**Learning:** Legacy table-based layouts often lack keyboard accessibility. Using a centralized `DOMContentLoaded` script to inject `role="button"`, `tabindex="0"`, and keyboard listeners is an efficient way to retrofit accessibility without heavy HTML refactoring.
**Action:** Use `querySelectorAll('td[onclick]')` to dynamically enhance interactive table cells with standard button behaviors.

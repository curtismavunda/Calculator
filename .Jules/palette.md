## 2025-05-15 - Retrofitting accessibility to legacy table-based UI
**Learning:** For legacy table-based layouts where `<td>` elements act as buttons, a centralized `DOMContentLoaded` script is a highly efficient way to inject accessibility (`role="button"`, `tabindex="0"`, `aria-label`) without refactoring the entire HTML structure. This preserves existing styles while ensuring keyboard and screen reader support.
**Action:** Use a DOM mapping object for ARIA labels and a loop to apply attributes and keyboard listeners to interactive elements in one pass.

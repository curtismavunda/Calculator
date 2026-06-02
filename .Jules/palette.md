## 2025-05-14 - Retrofitting Accessibility to Legacy Tables
**Learning:** Legacy table-based layouts (using <td> for buttons) can be made accessible without structural HTML changes by using a centralized DOMContentLoaded script to inject roles, tabindex, and keyboard listeners. This preserves the original layout while meeting modern a11y standards.
**Action:** Use document.querySelectorAll('td[onclick]') to identify interactive cells and apply accessibility attributes dynamically in similar legacy contexts.

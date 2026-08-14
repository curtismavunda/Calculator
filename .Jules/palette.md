## 2023-11-20 - Retrofitting Accessibility to Table-Based Elements
**Learning:** Legacy tabular layouts (`<td>`) can be retrofitted with keyboard accessibility dynamically using JS, adding `tabindex="0"`, `role="button"`, ARIA labels, and keydown event handling without refactoring the raw HTML structure.
**Action:** Use centralized `DOMContentLoaded` listeners in HTML files to inject accessibility parameters for table-cell buttons to keep PR diffs under 50 lines.

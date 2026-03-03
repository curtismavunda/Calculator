## 2025-03-03 - Accessible Table-based Buttons
**Learning:** Table cells (`<td>`) used as buttons require `role="button"`, `tabindex="0"`, and specific CSS (`z-index: 1`, `position: relative`) to ensure focus outlines aren't clipped by adjacent cell borders. Dynamic injection keeps HTML clean while meeting a11y standards.
**Action:** Use a JS loop to inject ARIA roles/labels and apply relative positioning to `:focus-visible` states in table-based layouts.

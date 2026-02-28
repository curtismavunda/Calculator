## 2025-05-15 - Enhancing Table-Based Calculator Accessibility
**Learning:** Retrofitting accessibility onto table-based components (using <td> as buttons) requires dynamic injection of roles and tabindices via JavaScript to maintain concise HTML while ensuring keyboard and screen reader support. Using 'z-index' and 'position: relative' on focused elements prevents layout-induced clipping of focus indicators.
**Action:** Use a JS loop for ARIA/tabindex injection and ensure :focus-visible rules handle layering in table/grid layouts.

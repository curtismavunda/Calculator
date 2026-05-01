## 2025-05-15 - Focus Visibility in Table Layouts
**Learning:** In table-based layouts, focus outlines on cells can be clipped by adjacent cell borders because table cells do not establish a new stacking context by default.
**Action:** Apply 'position: relative' and 'z-index: 1' to 'td:focus-visible' to ensure the outline is rendered above neighboring elements.

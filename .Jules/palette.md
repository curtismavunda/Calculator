## 2025-05-15 - Improving Accessibility on Table-Based Layouts
**Learning:** In table-based layouts with `border-collapse: collapse`, standard focus outlines can be clipped by adjacent cell borders. Applying `position: relative` and `z-index: 1` to the `:focus-visible` state ensures the focus indicator remains fully visible above neighboring elements.
**Action:** Always use `position: relative` and `z-index: 1` for focus states on elements within collapsed tables.

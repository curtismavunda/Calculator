## 2025-05-14 - Ensuring visible focus in collapsed table layouts
**Learning:** In tables using `border-collapse: collapse`, adjacent cell borders can clip the focus outline of the active cell. Applying `z-index: 1` and `position: relative` to `td:focus-visible` ensures the outline remains fully visible on top of neighboring cells.
**Action:** Always use `z-index: 1` and `position: relative` alongside focus indicators for interactive elements within a table grid.

## 2026-05-14 - Keyboard Navigation for Table-based UI
**Learning:** Custom focus outlines on table cells (<td>) can be obscured by the borders of adjacent cells due to standard box model behavior.
**Action:** Use 'z-index: 1' and 'position: relative' on ':focus-visible' states to ensure the focus indicator remains fully visible over cell boundaries.

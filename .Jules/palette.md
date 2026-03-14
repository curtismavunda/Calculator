# Palette's Journal

## 2026-03-14 - Accessible Table-Based Buttons
**Learning:** Using '<td>' elements for interactive buttons lacks native keyboard support and ARIA semantics. Standard click listeners don't fire for Enter/Space on focused table cells.
**Action:** Inject 'role="button"', 'tabindex="0"', and a custom 'keydown' listener to '<td>' elements to restore accessibility. Use 'position: relative' and 'z-index: 1' on ':focus-visible' states to ensure outlines are not clipped by adjacent table borders.

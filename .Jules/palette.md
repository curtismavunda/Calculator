## 2026-03-21 - [Accessibility for Table-Based UI]
**Learning:** Using `<td>` elements for interactive components requires explicit `role="button"` and `tabindex="0"` for screen readers and keyboard users. Additionally, `z-index: 1` and `position: relative` on focused cells are necessary to prevent border-clipping in collapsed table layouts.
**Action:** Always inject appropriate ARIA roles and ensure focus visibility with proper stacking context when repurposing table cells as buttons.

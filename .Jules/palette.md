## 2025-08-25 - Table Cell Keyboard Focus Ring & Accessibility

**Learning:** Retrofitting legacy table cells (`<td>`) as buttons requires `role="button"` and `tabindex="0"`, but standard focus outlines are clipped by adjacent table borders when `border-collapse: collapse` is used. Elevating focused cells with `position: relative` and `z-index: 1` prevents visual outline clipping.
**Action:** Always include `position: relative` and `z-index: 1` on `td:focus-visible` when adding focus states to table-based layouts.

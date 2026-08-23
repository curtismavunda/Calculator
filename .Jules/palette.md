# Palette's Journal

## 2025-08-23 - Table cell button accessibility & focus indicators
**Learning:** Table cells (`<td>`) acting as buttons require explicit `role="button"`, `tabindex="0"`, and keyboard handlers (Enter/Space) to be accessible. Custom focus outlines on table cells need `position: relative` and `z-index: 1` to prevent neighboring cell borders from obscuring the outline.
**Action:** Always pair `tabindex="0"` on `<td>` with `:focus-visible` styling (`z-index: 1`) and an Enter/Space keydown listener with `preventDefault()`.

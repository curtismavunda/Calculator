## 2025-05-14 - Accessible Table-Cell Buttons
**Learning:** For legacy table-based UIs, dynamic injection of `role="button"` and `tabindex="0"` via JS keeps HTML diffs clean. When combining local button listeners (for Enter/Space) with global shortcut listeners, `event.stopPropagation()` on the local listener is essential to prevent double-triggering.
**Action:** Use a JS loop for bulk ARIA attribute injection and always stop propagation on focused interactive elements to isolate their keyboard behavior from global shortcuts.

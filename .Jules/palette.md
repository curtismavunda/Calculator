# Palette's Journal

## 2025-02-14 - Retrofitting Legacy Table-Based Calculator for Modern UX
**Learning:** Legacy tabular calculator layouts often lack standard button elements, resulting in a complete absence of keyboard focus and screen reader accessibility. By dynamically appending appropriate attributes (`role="button"`, `tabindex="0"`) and wiring keyboard events with `event.preventDefault()` and `event.stopPropagation()`, we can retrofit modern accessibility to existing elements seamlessly without complex HTML refactoring.
**Action:** When working on table-based layouts, programmatically assign keyboard semantics to avoid manually restructuring HTML, and ensure custom CSS focus visible outlines use `position: relative` and `z-index: 1` to prevent border overlap hiding the focus ring.

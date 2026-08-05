# Palette's Journal - Critical Learnings Only

## 2023-10-27 - Retofitting Keyboard Accessibility on Legacy Table Layouts
**Learning:** Table-based layouts using native `<td>` tags with simple `onclick` handlers are completely invisible to screen readers and keyboard users by default. Rather than performing a heavy layout overhaul, keyboard accessibility can be retrofitted elegantly using a centralized JS hook to attach `tabindex="0"`, `role="button"`, custom ARIA labels matching screen-reader conventions, and a keydown listener to trigger clicks. Special care must be taken with `z-index` and `position: relative` on focus rings to ensure adjacent table borders do not obscure the keyboard outline.
**Action:** Apply the centralized DOMContentLoaded retrofitting script alongside targeted CSS focus-visible declarations with elevated z-index for any table-based or non-semantic button grids encountered in the future.

# Palette's Journal

This journal tracks critical UX and accessibility learnings from working with this application.

## 2025-07-19 - Legacy Table Element Accessibility Retrofitting
**Learning:** Legacy table-based calculator buttons (using td elements) do not naturally support keyboard focus, roles, or ARIA labels. Retrofitting accessibility dynamically via JavaScript on DOMContentLoaded provides full keyboard navigation, role tags, and screen-reader accessibility without requiring massive HTML structure edits. Using focus-visible with a negative offset ensures high-contrast keyboard-only focus rings without visual clutter for mouse users.
**Action:** Next time, use DOMContentLoaded dynamic attribute retrofitting for legacy table/div interfaces, pairing tabIndex="0", role="button", precise keydown handlers, and offset focus-visible CSS rules.

## 2026-09-03 - Active Operator Feedback & Live Display Accessibility
**Learning:** Adding explicit `.active-operator` state highlighting on operation selection provides immediate visual confirmation of the pending calculator mode, while adding `readonly` and `aria-live="polite"` to the display box ensures screen reader compatibility without triggering accidental text editing or soft keypads.
**Action:** When working with input-driven UI state, combine visual active states on trigger elements with polite live regions on output elements to provide clear, multi-modal feedback.

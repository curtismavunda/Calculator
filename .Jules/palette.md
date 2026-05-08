## 2025-05-08 - Accessible Table-Based Interactive Elements
**Learning:** For legacy projects using non-semantic elements (like `<td>`) with `onclick` handlers, a concise way to achieve accessibility is via dynamic JavaScript injection of `role="button"`, `tabindex="0"`, and keyboard listeners. This ensures keyboard and screen reader support while keeping the HTML diff minimal.
**Action:** Use `document.querySelectorAll` with attribute selectors (e.g., `td[onclick]`) to target interactive elements and inject accessibility features in a central loop.

## 2023-10-27 - Dynamic ARIA Injection for Minimal Diffs
**Learning:** In projects where interactive elements are implemented using non-semantic tags (like <td>) and have strict line-count constraints, injecting ARIA attributes via a JavaScript loop is an efficient way to improve accessibility without cluttering the HTML.
**Action:** Identify interactive elements by common attributes (e.g., onclick) and use a mapping for descriptive aria-labels.

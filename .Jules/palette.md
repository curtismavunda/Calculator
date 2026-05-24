## 2025-05-22 - Keyboard Support for Table-Based Buttons
**Learning:** When interactive elements are implemented using non-semantic tags like 'td', adding 'role="button"' and 'tabindex="0"' is necessary but not sufficient for accessibility; manual keyboard listeners for 'Enter' and 'Space' must also be added to match standard button behavior.
**Action:** Use a DOMContentLoaded listener to inject these attributes and listeners dynamically for all interactive table cells to ensure a consistent keyboard experience without duplicating HTML attributes.

## 2025-05-22 - Focus Visibility in Grids
**Learning:** Standard focus outlines on table cells can be partially obscured by adjacent cell borders.
**Action:** Apply 'position: relative' and 'z-index: 1' to ':focus-visible' states for table cells to ensure the focus indicator is fully visible and rendered above neighboring elements.

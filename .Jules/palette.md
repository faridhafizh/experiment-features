## 2026-05-16 - Improved PJP Dashboard Empty State
**Learning:** Replaced a simple text empty state with an engaging UI block including an icon and call-to-action button, successfully improving the visual guidance for first-time users without adding any new CSS classes.
**Action:** When adding empty states, always consider adding an actionable button and a visual icon using existing utilities to guide users.

## 2026-07-08 - Empty State Visual Enhancements for Tables
**Learning:** Adding empty states to data tables provides better visual feedback to users when data arrays are empty, preventing confusing blank space below table headers. Utilizing a combination of standard `colspan` matching the header count, a faded icon, and centered text creates an effective micro-UX improvement within EJS views.
**Action:** When working with EJS templates that render tables iterating over an array, always include an `if (data && data.length > 0)` check and provide an `else` block containing an empty state `<tr>` with the appropriate `colspan`.

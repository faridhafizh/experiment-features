## 2026-05-16 - Improved PJP Dashboard Empty State
**Learning:** Replaced a simple text empty state with an engaging UI block including an icon and call-to-action button, successfully improving the visual guidance for first-time users without adding any new CSS classes.
**Action:** When adding empty states, always consider adding an actionable button and a visual icon using existing utilities to guide users.

## 2023-10-25 - Table Empty States and Form Accessibility
**Learning:** Replaced blank tables with explicit empty states using an SVG icon and a helpful message explaining how to populate the data. This significantly improves UX by removing ambiguity about whether the system is broken or just empty. Additionally, adding explicit `id`/`for` links between `<input>` and `<label>`, and showing a `*` for required fields improves accessibility and form clarity. Finally, providing immediate feedback on form submission ("Memproses...") prevents double-submits and reassures users that an action is taking place.
**Action:** Always implement empty states for tables, link labels to inputs properly, indicate required fields visually, and add loading feedback to forms to improve accessibility and perceived performance.

## 2026-05-16 - Improved PJP Dashboard Empty State
**Learning:** Replaced a simple text empty state with an engaging UI block including an icon and call-to-action button, successfully improving the visual guidance for first-time users without adding any new CSS classes.
**Action:** When adding empty states, always consider adding an actionable button and a visual icon using existing utilities to guide users.

## 2024-05-18 - [Merchants List Page UX & A11y]
**Learning:** EJS templates for simple CRUD interfaces often lack friendly empty states, making them look broken when no data exists. Additionally, basic forms often miss `for` attributes on labels and simple loading states, leading to poor screen reader experiences and potential double-submissions.
**Action:** Always check for an `if/else` block rendering an empty state when updating or reviewing tables in EJS. Add inline `onsubmit` disable logic to submit buttons. Ensure all labels have matching `for` attributes for inputs.

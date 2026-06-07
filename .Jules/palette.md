## 2026-05-16 - Improved PJP Dashboard Empty State
**Learning:** Replaced a simple text empty state with an engaging UI block including an icon and call-to-action button, successfully improving the visual guidance for first-time users without adding any new CSS classes.
**Action:** When adding empty states, always consider adding an actionable button and a visual icon using existing utilities to guide users.

## 2026-06-07 - Table Wrapping for Responsiveness
**Learning:** HTML tables inside simple `<div class="card">` containers will overflow and break layouts on small screens if not explicitly wrapped. The project CSS includes a `.table-wrapper` specifically to handle horizontal scrolling for tables.
**Action:** Always wrap `<table class="table">` elements in `<div class="table-wrapper">` when modifying or creating views with tabular data to ensure mobile responsiveness without custom CSS.

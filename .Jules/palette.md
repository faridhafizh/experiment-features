## 2024-06-15 - Improved Empty State & Button Focus UX
**Learning:** Adding empty states to tables (`Belum ada data...`) prevents confusion when users view newly created dashboards without data. Also, native `:focus-visible` is necessary for accessibility on `.btn` elements that override default outlines.
**Action:** Always check for empty array edge cases before rendering EJS table rows. Ensure all custom buttons and links include `:focus-visible` styling globally in `app.css`.

## 2026-05-16 - Improved PJP Dashboard Empty State
**Learning:** Replaced a simple text empty state with an engaging UI block including an icon and call-to-action button, successfully improving the visual guidance for first-time users without adding any new CSS classes.
**Action:** When adding empty states, always consider adding an actionable button and a visual icon using existing utilities to guide users.

## 2026-05-17 - Added Form Accessibility and Submit Feedback in Dashboard Forms
**Learning:** Legacy EJS templates often lacked proper `for` and `id` bindings between labels and inputs, as well as missing visual indicators for `required` fields. Additionally, double submissions were possible because submit buttons weren't disabled after clicking.
**Action:** Implemented a standard pattern of linking labels with `for` and `id`, adding `<span aria-hidden="true" style="color: var(--danger)">*</span>` for required fields, and appending an inline `onsubmit="const btn = this.querySelector('button[type=submit]') || this.querySelector('button'); if(btn){ btn.disabled = true; btn.textContent = 'Memproses...'; }"` handler to forms to improve both accessibility and interaction feedback without writing new CSS or JS files.

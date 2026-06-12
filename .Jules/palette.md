## 2026-05-16 - Improved PJP Dashboard Empty State
**Learning:** Replaced a simple text empty state with an engaging UI block including an icon and call-to-action button, successfully improving the visual guidance for first-time users without adding any new CSS classes.
**Action:** When adding empty states, always consider adding an actionable button and a visual icon using existing utilities to guide users.

## 2026-06-12 - Reusable Form Loading Pattern
**Learning:** Found an effective inline JS pattern for forms to prevent double-submission and provide feedback (`onsubmit="const btn = this.querySelector('button[type=submit]'); if(btn) { btn.disabled = true; btn.textContent = 'Memproses...'; }"`). This is especially critical for this app where the backend doesn't have native PRG (Post/Redirect/Get) safeguards on all forms.
**Action:** Use this inline `onsubmit` snippet for all basic HTML forms in this EJS app to handle loading states without adding extra script blocks.

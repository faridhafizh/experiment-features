## 2026-05-16 - Improved PJP Dashboard Empty State
**Learning:** Replaced a simple text empty state with an engaging UI block including an icon and call-to-action button, successfully improving the visual guidance for first-time users without adding any new CSS classes.
**Action:** When adding empty states, always consider adding an actionable button and a visual icon using existing utilities to guide users.
## 2024-05-24 - HTML Document Structure
**Learning:** EJS views in this app rely on `partials/footer.ejs` to correctly close layout wrappers (`</div>`), `</body>`, and `</html>` tags. Hardcoding closing body tags directly in view files breaks the layout containment.
**Action:** Always inspect the footer partial before closing HTML structures manually in templates.

## 2024-05-24 - Vanilla JS Form Submit Protection
**Learning:** Adding a simple inline `onsubmit` handler (`const btn = this.querySelector('button[type=submit]'); if(btn){ btn.disabled = true; btn.textContent = 'Memproses...'; }`) to traditional SSR EJS forms provides instant feedback and protects against double-submission without requiring external UI libraries.
**Action:** Use this lightweight, zero-dependency pattern for immediate UX wins on SSR forms.

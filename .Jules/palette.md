## 2026-05-16 - Improved PJP Dashboard Empty State
**Learning:** Replaced a simple text empty state with an engaging UI block including an icon and call-to-action button, successfully improving the visual guidance for first-time users without adding any new CSS classes.
**Action:** When adding empty states, always consider adding an actionable button and a visual icon using existing utilities to guide users.

## 2023-10-24 - HTML Document Closure Pattern in EJS
**Learning:** Found several EJS views manually closing `</body></html>` while also having a `<div class="container">` opened but not properly closed if missing the correct partial. The application relies on `<%- include('partials/footer') %>` to close both the container and the HTML document.
**Action:** When updating older or newer views, ensure `<%- include('partials/footer') %>` is used instead of manual HTML closing tags to maintain consistent layout wrappers and prevent unclosed tags.

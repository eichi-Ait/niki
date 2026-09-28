# niki

Initial files added by GitHub Copilot on user request.

Included:
- `assets/css/styles.css` — global styles (blue/gray card-style layout, sans-serif font).
- `templates/article-list.html` — example article list HTML snippet that uses the stylesheet and keeps semantic structure (ul/li/a/article) so existing JS should continue to work.

Usage:
- Include `assets/css/styles.css` in your site HTML (`<link rel="stylesheet" href="/assets/css/styles.css">`) or import it in your build pipeline.
- Replace or adapt your article list template with `templates/article-list.html` as needed. The styles use class names like `.article-list`,`.article-card`,`.article-title` — if your JS expects different class names, update the selectors accordingly.

This commit only adds CSS/HTML and does not change any JavaScript logic.

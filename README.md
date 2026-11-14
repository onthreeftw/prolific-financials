# Prolific Financials site

- `/` : version 2 (form at the top, 3-step form)
- `/v1/` : version 1 (form lower on the page)
- `/v3/` : version 3 (white + black + light green, form at the top, animated report)

Every push to `main` redeploys on Netlify automatically.
Form submissions include a `page_version` field (v1 or v2) so you can compare which page converts better.

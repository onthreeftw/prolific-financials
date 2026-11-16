# Prolific Financials site

- `/` : version 3 (main page: white + black + light green, English/Spanish switch)
- `/v2/` : version 2 (black and gold, form at the top)
- `/v1/` : version 1 (black and gold, form lower on the page)
- `/v3/` redirects to `/` so old links keep working. `/?lang=es` opens in Spanish.

Every push to `main` redeploys on Netlify automatically.
Form submissions include `page_version` (v1, v2 or v3) and `language` (v3 only).

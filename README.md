# leanr-site

The public website for the LEANR Android app. Currently one page: the privacy
policy, which Google Play requires to be reachable at a public URL and checks
during review.

Served by **GitHub Pages** from branch `main`, folder `/` (root).

- `privacy.html` — the policy. The app links to it from Settings and the paywall.
- `index.html` — redirects the bare URL to the policy.
- `.nojekyll` — stops GitHub running Jekyll over the folder.

The source of truth lives in the app repo at `docs/privacy.html`; copy changes
from there rather than editing here, so the two cannot drift.

# leanr-site

The public website for the LEANR Android app. Two pages, both of which Google
Play requires to be reachable at public URLs and checks during review:

- `privacy.html` — the privacy policy. Linked from Settings and the paywall.
- `terms.html` — the terms of use. Linked from the paywall.
- `index.html` — redirects the bare URL to the privacy policy.
- `.nojekyll` — stops GitHub running Jekyll over the folder.

Served by **GitHub Pages from the `gh-pages` branch**. Pages was never enabled
through the repo settings; pushing that branch auto-publishes it. Keep `main`
and `gh-pages` in step, or the live site will lag behind.

## The source of truth is elsewhere

Both pages are maintained in the **app repo** under `docs/`. Edit them there
and copy across. Editing here instead makes the published documents drift from
the app they describe — and the app's behaviour is checked against them.

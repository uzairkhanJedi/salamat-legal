# Privacy policy — moved

**Not the policy. Nothing reads this file.**

The privacy policy lives at <https://outingapp.io/privacy>, served from
`infrastructure/well-known/privacy/index.html` in the app repo
(`uzairkhanJedi/salamat`). That is the URL the app itself opens, and the only
copy with legal effect.

`index.html` in this repo now redirects there.

## Why

On 2026-09-03 the policy existed in three places — this repo's `index.html`,
this markdown file, and the app repo's served HTML. PostHog analytics shipped
in v0.31.0 and only two of the three were updated; the one the app links was
missed. For roughly twenty minutes the app collected analytics under a policy
that did not name the processor.

## Still live in this repo, deliberately

- **`delete-account.html`** — an App Store requirement, and linked from the
  policy's *Your choices* section. Do not redirect or remove it.
- **`join.html`** — the older join landing page.

The redirect is scoped to the policy page only. Do not widen it to the site.

# pub/AS — NUUC-Dispatch Spike S1 harness

Static GitHub Pages content for Spike S1 (`GTaskSheet-79dw.1` in the GActionSheet bd
tracker): a GIS sign-in page that calls the NUUC-Dispatch GAS backend
(`../../../NUUC-Dispatch`) to verify a Google identity from a genuinely cross-origin
static page. See `../../../GActionSheet/docs/verified-board-portal-plan.md` §5 for the
full spike design.

- `index.html` — the sign-in + verification harness. Two placeholders need real values
  once `../../../NUUC-Dispatch/SETUP.md` is complete: `GIS_CLIENT_ID_PLACEHOLDER` and
  `WEBAPP_EXEC_URL_PLACEHOLDER`.
- `privacy/`, `terms/` — OAuth-consent-screen-linked pages, adapted from GActionSheet's
  `assets/store-details/{privacy,terms}` for NUUC-Dispatch's much narrower scope
  (identity verification only, `openid email`, no Drive/Doc access).
- `icon-{32,48,96,128}.png` — copied from GActionSheet's `assets/store-details/` as a
  starting visual identity.
- `consent-screen-text.md` — the exact text/links to paste into the GCP OAuth consent
  screen form.

Not yet live — GitHub Pages configuration for this repo (`sdonaldson-nl/NUUC-Static`)
hasn't been confirmed enabled; check via repo Settings → Pages, or
`gh api repos/sdonaldson-nl/NUUC-Static/pages`.

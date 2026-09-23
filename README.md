# LinkFlow Help Center — client-facing

Static, single-page help/FAQ site for LinkFlow users. Unlisted (not linked from the
main IYM site's nav) — reached only via the button in the LinkFlow dashboard.

## Deploy (GitHub Pages)

1. Create a new GitHub repo (public is fine — no secrets or app source in here).
2. Push this folder's contents as the repo root (`index.html` + `CNAME` at top level).
3. Repo Settings → Pages → enable Pages from the `main` branch, root folder.
4. At your DNS provider, add a `CNAME` record: `linkflow` → `<your-github-username-or-org>.github.io`.
5. GitHub Pages reads the included `CNAME` file automatically and serves this at
   `linkflow.ignite-your-marketing.com` once DNS propagates.

## Keeping it current

This is the client-facing counterpart to `linkflow-team-manual` (separate repo,
gated). Client-facing content only — no pricing, no onboarding process, no
workflow-wiring internals. If a LinkFlow feature ships or changes, update both
this file and the team manual's copy so they don't drift.

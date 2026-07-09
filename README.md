# web-cap2UI5-built

Built output of [`cap2UI5/web-cap2UI5`](https://github.com/cap2UI5/web-cap2UI5).

The `main` branch of this repo holds the **fully built static cap2UI5 browser
site** — one commit per deployment. It is written automatically by the
`build web` workflow in `web-cap2UI5`; **don't push to it by hand.** Each
deploy commit carries the upstream cap2UI5 sha, the tooling sha and a link to
the workflow run, so `git log` is the deployment audit trail and
`git diff <old>..<new>` shows exactly what changed between two deployments.

GitHub Pages serves this branch directly: **Settings → Pages → Deploy from a
branch → `main` / `root`**. The `.nojekyll` file stops Pages from
Jekyll-processing the bundle. Pushing a new build here *is* the deploy.

The build tooling, the "how it works" documentation and local build
instructions live in [`web-cap2UI5`](https://github.com/cap2UI5/web-cap2UI5).

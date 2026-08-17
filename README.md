# web-cap2UI5-build

**This repository is a build artifact. Do not edit it — every deploy wipes
and rewrites it.**

The static, backend-less build of [cap2UI5](https://github.com/cap2UI5/cap2UI5),
served at <https://cap2ui5.github.io/web-cap2UI5-build/>. The whole framework
runs in the browser: roundtrips that would go to the CAP server are answered
in-process, drafts live in memory, and the tab is the session.

| | |
|---|---|
| Built by | [builder-cap2UI5-web](https://github.com/cap2UI5/builder-cap2UI5-web) |
| Built from | [cap2UI5/cap2UI5](https://github.com/cap2UI5/cap2UI5) — see `BUILD_INFO.json` for the exact commit |
| Report a problem | with the playground: [builder-cap2UI5-web](https://github.com/cap2UI5/builder-cap2UI5-web/issues) · with the framework: [cap2UI5](https://github.com/cap2UI5/cap2UI5/issues) |

Each commit here is one deployment; its message names the upstream commit it
was built from, so `git log` is the deployment history.

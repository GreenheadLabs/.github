# AGENTS.md

## Cursor Cloud specific instructions

This repository is a **GitHub organization profile repository** (`greenheadlabs/.github`). It is
content-only: the sole tracked file is `profile/README.md`, which GitHub automatically renders as the
organization's public profile page at `https://github.com/greenheadlabs`.

Key facts for future agents:

- There is **no application code, no package manifest/lockfile, no build system, no test suite, and no
  lint configuration**. There is nothing to install, compile, or run as a service, and the update
  script is intentionally a no-op.
- The "product" is the rendered profile page. The meaningful development action is editing
  `profile/README.md` and previewing how it renders as GitHub-flavored Markdown (tables, lists, links).
- GitHub-specific rendering caveat: only `profile/README.md` (at that exact path) is shown on the org
  profile. The top-level `README.md` is not used for the profile page. Keep profile content in
  `profile/README.md`.
- To preview the rendering locally (nothing is committed for this), you can render the Markdown with a
  GitHub-flavored Markdown renderer, e.g. outside the repo:
  `npx marked profile/README.md` (add `github-markdown-css` for GitHub styling), then open the HTML
  in a browser. This tooling is deliberately not added as a repo dependency.
- Since content is Markdown, "testing" is visual/structural verification that the page renders with
  correct headings, tables, and links — there are no automated tests to run.

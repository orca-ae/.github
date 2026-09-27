# orca-ae/.github: instructions for agents

This repository holds the public profile of the [orca-ae](https://github.com/orca-ae) GitHub
organization and the organization's default community health files.

| Path | What GitHub does with it |
|---|---|
| `profile/README.md`, `profile/assets/` | Shows the README on the organization's public profile page. |
| `CODE_OF_CONDUCT.md`, `SECURITY.md` | Shows them in every repository of the organization that has no file of its own, whatever that repository's visibility. |
| `LICENSE`, `.github/CODEOWNERS` | Apply to this repository only. |

## Rules

1. **Everything here is public.** Write for people outside the project. Don't write internal
   hostnames, private repository names, internal issue numbers, customer names, personal paths,
   credentials or AI session links.
2. **Identity.** The project is Orca. The CLI binary is `ork`, the domain is runorca.ai, the npm
   package is `@runorca/orca-sdk`, the PyPI package is `runorca`, and images live on
   `ghcr.io/orca-ae/*`. The copyright holder is The Orca Authors. Don't present a company as Orca's
   owner, sponsor or steward.
3. **Say exactly what's open.** Name what is open source and what ships only as Apache-2.0 packages,
   binaries or images. Don't promise dates or features.
4. **Link only to pages that load without signing in.** Check every new link while logged out.
5. **Use absolute URLs in `CODE_OF_CONDUCT.md` and `SECURITY.md`.** GitHub shows them inside other
   repositories, where a relative link would resolve against the wrong repository.
6. **Keep the organization-wide defaults to `CODE_OF_CONDUCT.md` and `SECURITY.md`.** Default issue
   templates, a pull request template or a `CONTRIBUTING.md` here would apply to every repository in
   the organization, including private ones. Each public repository carries its own.
7. **Stay consistent with Orca Agent Engine.** When you change `CODE_OF_CONDUCT.md` or
   `SECURITY.md`, compare them with the engine's versions and keep the two in step.

## Commits

- Sign off every commit with the Developer Certificate of Origin (`git commit -s`). Only a human
  signs off: an agent never adds `Signed-off-by`.
- When an AI tool helped, add one `Assisted-by:` trailer, such as `Assisted-by: Claude Code`. Don't
  credit a tool with `Co-authored-by:`.
- Changes go through a pull request that a code owner approves.

# Instructions — owner-display-name `.github`

Guide for maintainers and coding agents working on the **public organization meta-repository** (`owner-username/.github`).

## What this repository is

| Path | Role |
|------|------|
| [`profile/README.md`](profile/README.md) | **Public org profile** on [github.com/owner-username](https://github.com/owner-username) |
| [`README.md`](README.md) | Landing page when browsing this repo |
| [`INSTRUCTIONS.md`](INSTRUCTIONS.md) | This file |
| [`CHANGELOG.md`](CHANGELOG.md) | Notable changes to this meta-repo |
| [`docs/`](docs/README.md) | Workflows and GitHub UI files **in this repo** |

Application source code lives in [**dropafile**](https://github.com/owner-username/dropafile). Keep the org profile focused on what visitors need — link to the repo and summarize in one line; do not duplicate the full project README here.

---

## Editing the org profile README

[`profile/README.md`](profile/README.md) supports GitHub-flavored markdown plus limited HTML (e.g. `<div align="center">`).

Guidelines:

- Lead with what the organization ships and who it is for.
- List repositories in the **Repositories** table: **Repository** | **Summary**.
- Keep links absolute to `https://github.com/owner-username/<repo>`.
- Avoid secrets, internal URLs, or operational detail on this **public** page.

Preview: push to `main` and open [github.com/owner-username](https://github.com/owner-username).

When **dropafile** gains major features or positioning changes, update the summary row in `profile/README.md` and mirror any quick-reference tables in [`README.md`](README.md).

---

## Automation in this repo

| Asset | Role |
|-------|------|
| `.github/dependabot.yml` | Dependency update PRs |
| `.github/workflows/dependabot-signature.yml` | `Co-authored-by` on Dependabot commits |
| `.github/CODEOWNERS` | Review ownership |

Details: [docs/README.md](docs/README.md).

---

## Agent checklist

1. Read [`profile/README.md`](profile/README.md) and this file.
2. Confirm whether a change belongs in the **org profile** (this repo) or **dropafile** (application repo).
3. Update the repository table row when dropafile's public summary changes; sync [`README.md`](README.md) if needed.
4. Append [`CHANGELOG.md`](CHANGELOG.md) for meta-repo changes.

---

## Repository documents

[README](README.md) | **INSTRUCTIONS** | [CHANGELOG](CHANGELOG.md) | [CONTRIBUTING](CONTRIBUTING.md) | [SECURITY](SECURITY.md) | [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md)

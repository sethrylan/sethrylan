# agents.md

This repository (`sethrylan/sethrylan`) is the organization-level default configuration source for [`gh-repolint`](https://github.com/sethrylan/gh-repolint).

`gh-repolint` uses a two-level configuration hierarchy:

1. **Org defaults** — `.repolint.yml` and associated files in the `<owner>/<owner>` repo (this repo) provide the baseline rules applied to all repos under the `sethrylan` GitHub account.
2. **Repo overrides** — a `.repolint.yml` in an individual repo's root takes precedence over these defaults for that repo.

Files in `.repolint/` (such as `.golangci.yml` and workflow templates) are reference files that `gh-repolint` can enforce are present and up-to-date in downstream repos.

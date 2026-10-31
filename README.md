# Repository Template

[![License](https://img.shields.io/github/license/bruzit-test/template)](LICENSE)
[![Last commit](https://img.shields.io/github/last-commit/bruzit-test/template)](https://github.com/bruzit-test/template/commits)

<!-- Badges: license, last commit, then one GitHub workflow badge per required workflow in pipeline order: linting, formatting, verification, unit tests, integration tests, end-to-end tests, release, deployment. -->

Purpose of the project in one sentence or one short paragraph.

**This repository:**

Standardized repository scaffold for BruzIT projects. Pre-configured with semantic-release, license boilerplate, README structure, and initial v0.0.0 tag.

## Features

<!-- Optional: delete when empty. -->

Feature list or key capabilities; subsections as needed.

**This repository:**

- README outline with required and optional sections.
- MIT License: [`LICENSE`](LICENSE).
- No linting or release configuration yet (Integration and Deployment).

## Requirements

<!-- Optional: delete when empty. -->

Platforms, tools, dependencies, and versions needed.

**This repository:**

- Platform: GitHub.

## Installation and Setup

How to install and set up the project, step by step.

**This repository:**

1. Create the repository from this template, by hand ("Use this template") or as code with [BruzIT GitHub Organization as Code](https://github.com/bruzit/github-organization-as-code), which can also manage its settings, rulesets, environments and secrets.
2. Environments `release` and `autofix` are provisioned by BruzIT GitHub Organization as Code; no workflow uses them yet.
3. Tag the initial commit `v0.0.0`, so the first release is `0.x` instead of `1.0.0`:

   ```shell
   git tag v0.0.0 "$(git rev-list --max-parents=0 HEAD)" && git push origin v0.0.0
   ```

4. Make it yours:
   - In every section, replace the general line and the **This repository:** block with your project's content.
   - Make the first sentence of the description match the repository's GitHub description.
   - Search and replace `bruzit-test/template` in the badge URLs; add a workflow badge per required workflow in pipeline order.
   - Delete empty optional sections and the HTML comments.

## Usage

Common tasks with minimal examples.

**This repository:**

Copy this outline; replace each section's content (Installation and Setup, step 4).

## Maintenance

<!-- Optional: delete when empty. -->

How to keep it updated and healthy: updates, upgrades, backup and restore, uninstall.

**This repository:**

- Keep this README aligned with the outline.

## Support

Where to ask for help and report problems; for paid products, the service level.

**This repository:**

Community, best effort; [open a GitHub issue](../../issues).

## Development

<!-- Optional: delete when empty. -->

Local development environment and project layout.

**This repository:**

No tooling; Markdown and [`LICENSE`](LICENSE) only.

## Testing

<!-- Optional: delete when empty. -->

How to run checks and tests.

**This repository:**

No tests or linters.

## Integration and Deployment

<!-- Optional: delete when empty. -->

Workflows that integrate, release, and deploy the project.

**This repository:**

No workflows. The `main` ruleset requires the check `Required (MegaLinter)`, which no workflow reports yet.

## Contributing

How to propose changes.

**This repository:**

Open a pull request to `main`. Commits follow the [Conventional Commits 1.0.0 specification](https://www.conventionalcommits.org/en/v1.0.0/) with a lowercase subject, enforced by the `main` ruleset.

## License and Copyright

License and copyright holder.

**This repository:**

MIT License: [`LICENSE`](LICENSE)  
Copyright © 2026 Martin Bružina

## References

<!-- Optional: delete when empty. -->

Related projects and documentation.

**This repository:**

- [BruzIT GitHub Organization as Code](https://github.com/bruzit/github-organization-as-code)

## Stats

<!-- Optional: delete when empty. -->

Repository figures; stable products add selected usage or customer figures.

**This repository:**

| Metric           | Badges                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Commits          | [![Commits total](https://img.shields.io/github/commit-activity/t/bruzit-test/template?label=commits%20total)](https://github.com/bruzit-test/template/commits/main)                                                                                                                                                                                                                                                                                       |
| Issues           | [![Issues open](https://img.shields.io/github/issues/bruzit-test/template?label=issues)](https://github.com/bruzit-test/template/issues) [![Issues total](https://img.shields.io/github/issues-search?query=repo%3Abruzit-test%2Ftemplate%20is%3Aissue&label=issues%20total)](https://github.com/bruzit-test/template/issues?q=is%3Aissue)                                                                                                                 |
| Pull requests    | [![Pull requests open, not draft](https://img.shields.io/github/issues-search?query=repo%3Abruzit-test%2Ftemplate%20is%3Apr%20is%3Aopen%20draft%3Afalse&label=PRs%20open)](https://github.com/bruzit-test/template/pulls?q=is%3Apr+is%3Aopen+draft%3Afalse) [![Pull requests total](https://img.shields.io/github/issues-search?query=repo%3Abruzit-test%2Ftemplate%20is%3Apr&label=PRs%20total)](https://github.com/bruzit-test/template/pulls?q=is%3Apr) |
| Checks on `main` | [![Checks on main](https://img.shields.io/github/check-runs/bruzit-test/template/main?label=checks%20%28main%29)](https://github.com/bruzit-test/template/actions?query=branch%3Amain)                                                                                                                                                                                                                                                                     |
| Releases         | [![Latest release](https://img.shields.io/github/v/release/bruzit-test/template)](https://github.com/bruzit-test/template/releases/latest) [![Commits since latest release](https://img.shields.io/github/commits-since/bruzit-test/template/latest)](https://github.com/bruzit-test/template/releases)                                                                                                                                                    |
| Community        | [![Stargazers](https://img.shields.io/github/stars/bruzit-test/template)](https://github.com/bruzit-test/template/stargazers) [![Forks](https://img.shields.io/github/forks/bruzit-test/template)](https://github.com/bruzit-test/template/forks) [![Contributors](https://img.shields.io/github/contributors/bruzit-test/template)](https://github.com/bruzit-test/template/graphs/contributors)                                                          |

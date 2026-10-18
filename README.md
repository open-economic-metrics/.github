# Open Economic Metrics — shared organization defaults

This repository contains the public organization profile, shared community guidance, and default issue/pull-request templates for [Open Economic Metrics](https://github.com/open-economic-metrics).

It is **not** the statistical engine, an authoritative dataset, or a repository of third-party source data.

## Shared resources

- [Organization profile](profile/README.md)
- [Contributing](CONTRIBUTING.md)
- [Code of conduct](CODE_OF_CONDUCT.md)
- [Security reporting](SECURITY.md)
- [Support](SUPPORT.md)
- [Governance](GOVERNANCE.md)
- [Statistical integrity](STATISTICAL_INTEGRITY.md)
- [Issue forms](.github/ISSUE_TEMPLATE)
- [Pull request template](.github/PULL_REQUEST_TEMPLATE.md)

## How defaults work

GitHub supplies supported community-health files and templates from this public repository to other organization repositories **only when the destination repository does not define its own counterpart**. The files are not copied into the target repository or its release artifacts. A repository's own issue-template configuration overrides the shared issue-template set.

The governance and statistical-integrity documents in this repository express organization-wide expectations and are linked from contributor templates. Do not assume they are automatically packaged into another repository.

Every project must independently document its scope, supported data sources, methodology, validated results, and release process. Each software repository must choose and include its own license. Licenses and redistribution permissions for third-party data are separate from software licensing.

## Status

The organization is being established. The first planned research project is **Open Labor Metrics**, focused on reproducible labor-market measurement. No new statistic is presented here as validated or published.

To propose changes to these shared defaults, open an issue or pull request against this repository.

# Contributing to Open Economic Metrics

Contributions are welcome, including corrections, reproducibility tests, source inventories, statistical research, API improvements, documentation, and accessibility fixes.

## Before starting

1. Check existing issues and documentation in the repository affected by the change.
2. For nontrivial or potentially breaking methodology changes, open a research issue describing the authoritative reference, intended measurement, and acceptance criteria before implementing.
3. Keep each contribution narrowly scoped. Prefer an independently testable change over an unrelated collection of improvements.

## Changes to statistics or data

Read the [statistical integrity policy](https://github.com/open-economic-metrics/.github/blob/main/STATISTICAL_INTEGRITY.md). In particular:

- Identify the authoritative organization, source release, statistical definition/version, population, period, geography, and units.
- Preserve established definitions. Propose changed assumptions as separately identified, versioned derivations or profiles.
- Reproduce and reconcile authoritative published results wherever the source provides reference values.
- Document weighting, uncertainty, rounding, transforms, missing-data handling, and limits to comparability as applicable.
- Record source licensing, attribution, permitted processing, and redistribution terms. Do not commit third-party datasets or bulk-extract restricted sources without permission.
- Do not present exploratory or modeled outputs as published observed facts.

If appropriate validation is not yet possible, describe what was inspected, what was tested, and what remains unverified.

## Pull requests

- Explain the problem, scope, solution, and evidence.
- Include the commands and results for tests you actually ran; do not mark unrun checks as passed.
- Flag API/schema compatibility changes and statistical definition/version changes.
- Identify new dependencies and any licensing or data-handling implications.
- Let each repository's own contribution guidance or workflows take precedence where more specific.

A pull request is not a claim of acceptance, statistical validation, or publication readiness. Maintainers review those decisions separately.

## Contribution rights

Only submit material you have the right to contribute. Do not include personal, confidential, licensed-for-limited-use, or credential data in issues or pull requests. Project-specific licenses govern contributions; the organization does not impose a software or data license through this shared repository.

Follow our [code of conduct](https://github.com/open-economic-metrics/.github/blob/main/CODE_OF_CONDUCT.md).

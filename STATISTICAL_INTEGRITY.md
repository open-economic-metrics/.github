# Statistical integrity policy

This policy applies to research software, statistical definitions, data transformations, published measures, and public API representations maintained by Open Economic Metrics.

## Non-negotiable principles

1. **Definitions are first-class resources.** Give every statistical definition a stable identity, an explicit version, responsible source or authority, calculation contract, and applicability conditions.
2. **Canonical source definitions are preserved.** Multiple authoritative organizations may have valid but different definitions. Keep each source-native baseline independently; do not rewrite, relabel, or silently replace it.
3. **Reproduce established reference statistics first.** Before promoting a new calculation, independently reproduce reference values where published and document reconciliation tolerances, rounding, discrepancies, and evidence.
4. **Extensions are explicit derivations.** Nonstandard age cohorts, hours thresholds, geography mappings, living-wage benchmarks, and other profiles receive separate identifiers/versions and parent-definition lineage.
5. **Record provenance and limitations.** A reported value identifies its sources and release vintages; numerator, denominator, units, population, time basis, geography and geographic vintage; weighting and uncertainty methodology; and calculation version.
6. **Do not manufacture comparability.** Explicitly identify changes in definitions, series breaks, geography mismatches, unavailable observations, and estimates that cannot be validly aligned. Never silently fill gaps, extrapolate geographic precision, or substitute providers.
7. **Distinguish evidentiary states.** Registered definitions, implemented calculations, validated outputs, and publicly released statistics are separate states. Record whether values are observed, derived, or modeled.
8. **Publication rights are independent.** Legal access to a dataset is not proof of redistribution rights. Document licenses, attribution, acquisition constraints, and distribution eligibility per source and release.

## Canonical and derived measures

A canonical definition is a documented specification used by an identified authority—not a claim that it is the only correct perspective. For example, BLS publishes an overall employment-population ratio for the civilian noninstitutional population aged 16 and older, and uses 25–54 for prime-age comparisons. Source-specific conventions for full-time hours must also remain explicit.

Custom cohorts (such as ages 22–60) and alternative hours thresholds are potential derived profiles, **not replacements for canonical baselines**. They may be published only with distinct names, derivation chains, validation results, and comparability labels.

## Minimum evidence for a statistical change

A research issue or pull request affecting a published measure should make it possible to find:

- The problem and intended population/quantity.
- Authoritative sources, release dates, definitions, and permitted data inputs.
- The full transformation method, calculation settings, weighting, and uncertainty handling.
- A reference-result reconciliation or a precise reason one is unavailable.
- Before/after differences, known caveats, comparability impact, and the versioning decision.
- The evidence supporting publication approval, separate from code review.

## Practical publication rule

**Register → implement → reconcile and validate → publish.** Validation does not itself grant rights to redistribute data. Published results must carry enough information for API consumers to distinguish established source observations from project-derived or modeled statistics.

Project-specific methodology specifications and software tests may add requirements; they must not silently weaken these principles.

# CEOS-RP-001 — Reproducibility and Replication Statement

## Current reproducibility class

**Architecture-and-evidence preprint with a proposed experimental program.**

The paper includes formal models, repository observations, external literature synthesis, and proposed adversarial experiments. It does not claim that the full comparative benchmark has already been executed.

## Historical implementation anchor

Repository observations in the initial preprint were made against the CEOS Infrastructure revision recorded in METADATA.yaml. Replication of those historical observations requires access to the referenced source and relevant validation evidence.

If the implementation repository is not publicly available, external readers cannot independently reproduce private-repository observations solely from this public research repository. That limitation must remain explicit.

## External-source replication

Claims based on external standards or publications should be checked against the cited primary source and the version/date applicable to the paper.

## Future benchmark package

A publication-grade empirical benchmark should eventually include:

1. threat model;
2. exact CEOS version;
3. exact incumbent baseline and configuration;
4. workload corpus;
5. adversarial scenarios;
6. proof obligations;
7. expected safe outcomes;
8. falsification conditions;
9. environment and dependency versions;
10. execution scripts or equivalent procedures;
11. raw results;
12. analysis code;
13. random seeds where applicable;
14. hardware/runtime description where material;
15. negative results and unresolved outcomes.

## Priority adversarial scenarios

- stale authority after material state drift;
- revocation race;
- credential overreach;
- prompt-injected reasoner;
- ambiguous external outcome;
- concurrent canonical promotion;
- forged or inapplicable evidence;
- crash/restart between dispatch and observation;
- stale lease;
- provider timeout;
- duplicate execution;
- partial persistence;
- lower-layer bypass attempt.

## Replication principle

A replication failure should not be silently normalized away. Differences in version, environment, policy, workload, or evidence must be recorded before interpreting the result.

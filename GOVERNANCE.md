# Research Repository Governance

## Scope

This repository governs CEOS public research publications and supporting research artifacts. It does **not** govern CEOS runtime authority, deployment, releases, infrastructure mutation, or canonical implementation state.

## Semantic boundary

- **CEOS implementation repositories** own implementation history and their applicable engineering governance.
- **CEOS-Research-Papers** owns publication organization, paper versions, research metadata, public supplementary material, and correction history.
- A research commit cannot authorize an implementation change.
- An implementation commit does not automatically amend a released paper.

## Publication identifiers

Papers use stable identifiers of the form **CEOS-RP-NNN**.

## Versioning

A publication release should be tagged. Material post-release changes require a new publication version. Draft branch state should not be cited as if immutable.

## Review

Substantive new papers and material revisions should normally be proposed through a reviewable branch or pull request before becoming a tagged publication release.

## Canonical research artifact

For a released paper, the tagged release and its checksummed publication artifact are the preferred historical reference. A future DOI-backed archival deposit should become the preferred scholarly citation when available.

## Corrections and retractions

Errors should be corrected transparently. If a paper's central result is invalidated, the repository should preserve the historical artifact while prominently marking the affected version as superseded, corrected, or retracted as appropriate.

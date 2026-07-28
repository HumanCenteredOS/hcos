# HCOS™ CHANGELOG Guidelines

**Document Type:** Governance Standard\
**Status:** Draft\
**Version:** 1.0.0\
**Last Updated:** July 2026

------------------------------------------------------------------------

# Purpose

The HCOS™ CHANGELOG documents the meaningful evolution of standards,
prompts, instruments, methods, examples, and supporting documentation.

A changelog provides a concise, transparent record of what changed, why
it changed, and when the change became part of the framework.

The goal is to improve traceability---not to reproduce the entire
document history.

------------------------------------------------------------------------

# Guiding Principles

A good HCOS changelog should be:

-   Accurate
-   Concise
-   Transparent
-   Chronological
-   Helpful to contributors and users
-   Consistent across repositories

Record meaningful changes rather than every minor edit.

------------------------------------------------------------------------

# Relationship to the Release Process

Every reviewed release should include:

Develop → Review → Commit → **CHANGELOG** → Git Tag → Release

The changelog summarizes the approved changes included in that release.

------------------------------------------------------------------------

# Recommended Structure

Each `CHANGELOG.md` should begin with:

``` markdown
# CHANGELOG

All notable changes to this project are documented in this file.

This project follows the HCOS Release Process and Semantic Versioning.
```

Document versions in reverse chronological order (newest first).

------------------------------------------------------------------------

# Version Format

Use Semantic Versioning:

    MAJOR.MINOR.PATCH

Examples:

-   1.0.0
-   1.1.0
-   1.1.1
-   2.0.0

------------------------------------------------------------------------

# Recommended Categories

When applicable, organize changes under the following headings:

## Added

New content or capabilities.

## Improved

Enhancements to existing content.

## Changed

Meaningful revisions that alter wording, organization, or guidance.

## Fixed

Corrections of errors, inconsistencies, broken references, or formatting
issues.

## Removed

Content intentionally removed or deprecated.

## Validation

Updates related to review, testing, or external validation.

## Known Limitations

Important limitations or areas still requiring future work.

Use only the sections that apply to a release.

------------------------------------------------------------------------

# Example

``` markdown
# CHANGELOG

## [1.1.0] – July 2026

### Added

- Resume Review Checklist
- ATS Optimization Guide

### Improved

- Expanded examples of human-centered language.
- Clarified evidence-based improvement guidance.

### Fixed

- Corrected terminology for review status.

### Validation

- Internal review completed.
- Recruiter feedback incorporated.

### Known Limitations

- External validation remains ongoing.
```

------------------------------------------------------------------------

# What to Include

Document changes that users or contributors would reasonably want to
know, such as:

-   new sections
-   expanded guidance
-   structural improvements
-   new examples
-   significant clarifications
-   validation milestones
-   compatibility updates
-   retired content

------------------------------------------------------------------------

# What Not to Include

Avoid documenting:

-   spelling corrections
-   punctuation fixes
-   whitespace changes
-   formatting-only edits
-   draft notes
-   temporary working changes

unless they materially affect understanding.

------------------------------------------------------------------------

# Writing Style

Use concise, action-oriented language.

Prefer:

-   Added validation guidance.
-   Expanded implementation examples.
-   Clarified review expectations.

Avoid lengthy explanations that belong in release notes.

------------------------------------------------------------------------

# Relationship to Git

The changelog summarizes approved releases.

Git history preserves detailed commit history.

Use both together:

-   Git commits explain individual revisions.
-   CHANGELOG.md summarizes released versions.
-   Git tags identify approved versions.
-   GitHub Releases provide public release notes.

------------------------------------------------------------------------

# Maintaining the Changelog

Update the changelog immediately before creating the release tag.

Each version should appear only once.

Do not rewrite previous entries except to correct factual errors.

------------------------------------------------------------------------

# Guiding Principle

A changelog should help readers quickly understand how the HCOS
framework has evolved.

It should communicate meaningful progress with clarity, honesty, and
consistency while preserving a transparent record of continuous
improvement.


CHANGELOG_GUIDELINES.md

Purpose

Where CHANGELOG belongs

Formatting

Examples

Added

Improved

Removed

Deprecated

Fixed

What NOT to include

Good examples

Poor examples

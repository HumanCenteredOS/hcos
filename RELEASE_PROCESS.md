# HCOS™ Release Process

All HCOS standards, prompts, instruments, examples, and supporting documents should follow the same development lifecycle:

> Develop → Review → Commit → CHANGELOG → Git Tag → Release

This process helps preserve clarity, accountability, version history, and trust as the HCOS framework evolves.

---

## 1. Develop

Create or revise the document in its appropriate repository folder.

During development:

- Confirm the document's purpose and intended audience.
- Use the appropriate HCOS naming convention.
- Align the document with related HCOS foundations, standards, and disciplines.
- Mark unfinished documents as `Draft`.
- Update the version number only when the revision is ready for release.

Example document header:

```markdown
**Status:** Draft  
**Version:** 1.1.0  
**Last Updated:** July 2026

## Step 2 — Review

Review the document according to the HCOS Review Standard.

See:

➡️ REVIEW_STANDARD.md

## Step 3 — Commit


## Step 4 — CHANGELOG

Update the standard-level CHANGELOG according to:

➡️ CHANGELOG_GUIDELINES.md


## Step 5 — Git Tag

Create a Git tag following the HCOS Versioning Standard.

See:

➡️ VERSIONING.md

## Step 6 — GitHub Release


## Required Release Checklist

Before publishing an HCOS release, confirm:

- [ ] The document has been developed in the correct repository folder.
- [ ] The filename follows HCOS naming conventions.
- [ ] The document status is current.
- [ ] The document version is current.
- [ ] The content has been reviewed.
- [ ] Related HCOS documents have been checked for consistency.
- [ ] The changes have been committed to GitHub.
- [ ] The standard-level `CHANGELOG.md` has been updated.
- [ ] The Git tag matches the document version.
- [ ] The GitHub Release has been created.
- [ ] The release notes accurately describe the changes.
- [ ] Known limitations or pending validation are disclosed.
### Release Decision

- [ ] This version is ready to be identified as a reviewed and referenceable HCOS release.

---

# GitHub Pull Request Integration

Every proposed HCOS change should be submitted through a GitHub Pull Request whenever practical.

The Pull Request serves as the documented review point before a change becomes an official HCOS release.

Each Pull Request should include:

- A clear description of the proposed change.
- The purpose of the revision.
- The affected standard(s), prompt(s), instrument(s), or supporting documents.
- The proposed version number.
- Confirmation that the Required Release Checklist has been completed.
- Any known limitations or areas requiring future validation.

The Pull Request should also document whether the revision represents:

- A new standard
- A clarification
- A correction
- A structural refactor
- A documentation improvement
- A major conceptual revision

## Before Opening a Pull Request (short version)

Before requesting review, please confirm that you have completed the steps described in **RELEASE_PROCESS.md**, including:

- Updating the document version (if applicable)
- Reviewing the content for accuracy and consistency
- Updating the appropriate `CHANGELOG.md`
- Preparing the revision for release

The Pull Request template will guide you through the remaining release requirements.

Reviewers should verify that the proposed revision:

- Preserves human dignity.
- Aligns with HCOS principles.
- Maintains consistency with related standards.
- Clearly communicates any assumptions or limitations.
- Is appropriate for the proposed version number.

Approval of a Pull Request indicates that the revision is ready to proceed through the remaining HCOS release process.

A Pull Request does not replace formal review or validation. It documents the collaborative review process leading to an official release.





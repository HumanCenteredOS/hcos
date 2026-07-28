# HCOS™ Release Process

All HCOS™ standards, prompts, instruments, examples, and supporting documents should follow the same development lifecycle:

> **Develop → Review → Commit → CHANGELOG → Git Tag → Release**

This process helps preserve clarity, accountability, consistency, and traceability as the HCOS framework evolves.

---

## Step 1 — Develop

Create or revise the document in its appropriate repository folder.

During development:

- Confirm the document’s purpose and intended audience.
- Use the appropriate HCOS naming convention.
- Align the document with related HCOS foundations, standards, disciplines, and supporting documents.
- Mark unfinished documents as `Draft`.
- Update the version number only when the revision is ready to move toward release.

### Example Document Header

```markdown
**Status:** Draft  
**Version:** 1.1.0  
**Last Updated:** July 2026
```

---

## Step 2 — Review

Review the document according to the HCOS Review Standard.

The review should consider content quality, human dignity, systems awareness, safety, consistency, readability, and potential unintended harm.

See:

➡️ [`REVIEW_STANDARD.md`](REVIEW_STANDARD.md)

The review status should be stated clearly within the document or release notes.

Examples:

```markdown
**Review Status:** Internal review completed
```

```markdown
**Review Status:** External validation pending
```

---

## Step 3 — Commit

Commit the reviewed changes to GitHub using a clear and descriptive commit message.

Recommended format:

```text
<type>: <brief description>
```

Examples:

```text
feat: add HCOS 302 compassionate response examples
```

```text
docs: clarify HCOS 302 safety guidance
```

```text
fix: correct inconsistent terminology in HCOS 302 prompt
```

```text
refactor: reorganize HCOS 302 document structure
```

Suggested commit types:

- `feat` — New content or capability
- `docs` — Documentation revision
- `fix` — Correction
- `refactor` — Structural improvement without changing the core meaning
- `style` — Formatting or presentation change
- `chore` — Repository maintenance

Whenever practical, each commit should represent one understandable group of changes.

---

## Step 4 — Update the CHANGELOG

Update the standard-level `CHANGELOG.md` according to the HCOS Changelog Guidelines.

See:

➡️ [`CHANGELOG_GUIDELINES.md`](CHANGELOG_GUIDELINES.md)

The changelog should summarize meaningful changes under the appropriate version number.

Do not reproduce the full document in the changelog.

Document only the most important additions, improvements, corrections, removals, limitations, and validation updates.

---

## Step 5 — Create a Git Tag

Create a Git tag after the final release commit.

Follow the HCOS Versioning Standard.

See:

➡️ [`VERSIONING.md`](VERSIONING.md)

The Git tag should:

- Match the document or repository version.
- Point to the exact commit representing the approved release.
- Use the appropriate HCOS naming convention.

Example for an individual standard:

```text
hcos-302-v1.1.0
```

Example for a repository-wide release:

```text
v1.1.0
```

---

## Step 6 — Publish a GitHub Release

Create a GitHub Release from the approved Git tag.

The release should include:

- Release title
- Version number
- Release date
- Brief summary
- Important additions
- Important revisions
- Known limitations
- Validation or review status
- Links to the primary documents

### Example Release Title

```text
HCOS 302 — Compassionate Human-Centered Response v1.1.0
```

### Example Release Notes

```markdown
## Summary

This release expands the HCOS 302 examples and strengthens guidance related to system influences, human agency, accountability, and immediate safety.

## Added

- Six additional response examples
- Immediate-safety response guidance
- Explanatory alignment notes

## Improved

- Systems-aware framing
- Preservation of dignity and agency
- Distinction between compassion and accountability

## Review Status

Internal review completed. External validation remains ongoing.
```

A GitHub Release identifies a specific, reviewed, and referenceable version of the HCOS framework.

---

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

A Pull Request provides a visible and documented review point before a change becomes part of an official HCOS release.

A Pull Request supports the release process, but it does not replace formal review, validation, tagging, or release publication.

## Pull Request Requirements

Each Pull Request should include:

- A clear description of the proposed change.
- The purpose of the revision.
- The affected standards, prompts, instruments, examples, or supporting documents.
- The proposed version number.
- Confirmation that the applicable release requirements have been addressed.
- Any known limitations or areas requiring future validation.

The Pull Request should also identify the type of revision.

Examples include:

- New standard
- New supporting document
- Content expansion
- Clarification
- Correction
- Structural refactor
- Documentation improvement
- Major conceptual revision
- Formatting-only change

---

## Before Opening a Pull Request

Before requesting review, confirm that the applicable steps in this release process have been completed.

This includes:

- Developing the document in the correct folder.
- Confirming that the filename follows HCOS naming conventions.
- Updating the document status and version, when applicable.
- Reviewing the content for accuracy and consistency.
- Checking related HCOS documents for alignment.
- Updating the appropriate `CHANGELOG.md`.
- Identifying any known limitations or pending validation.
- Preparing the revision for review and release.

The GitHub Pull Request template should guide contributors through the remaining requirements.

---

## Pull Request Review

Reviewers should verify that the proposed revision:

- Preserves human dignity.
- Aligns with HCOS principles.
- Recognizes relevant system influences.
- Preserves personal agency.
- Maintains consistency with related standards and documents.
- Uses clear and accessible language.
- Addresses safety and escalation concerns when relevant.
- Clearly communicates assumptions, limitations, and validation status.
- Uses an appropriate version number.
- Is ready to proceed through the remaining release steps.

Approval of a Pull Request indicates that the revision is ready to continue through the HCOS release process.

Approval does not necessarily mean that external validation has occurred.

The review and validation status should always be stated honestly.

---

## Relationship Between Pull Requests and Releases

A Pull Request documents the proposed change and its review.

A Git commit records the approved change.

A `CHANGELOG.md` explains what changed.

A Git tag identifies the exact approved version.

A GitHub Release makes that version visible and referenceable.

Together, these steps create a transparent record of how the HCOS framework develops over time.

> **Develop → Review → Commit → CHANGELOG → Git Tag → Release**





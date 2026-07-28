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

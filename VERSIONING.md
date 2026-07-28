# HCOS™ Versioning

## Purpose

HCOS™ uses Semantic Versioning to provide a consistent, transparent approach to documenting changes across standards, prompts, instruments, examples, and supporting documentation.

Consistent versioning improves transparency, traceability, and long-term stewardship across the HCOS framework.

---

## Semantic Versioning

HCOS follows the format:

```text
MAJOR.MINOR.PATCH
```

---

## Version Definitions

| Version | Meaning |
|----------|---------|
| **1.0.0** | Initial published release |
| **1.1.0** | New examples, expanded guidance, additional sections, or other enhancements that do not substantially change the intent or interpretation of the published standard |
| **1.1.1** | Typographical corrections, wording clarifications, formatting improvements, or other minor refinements |
| **2.0.0** | Major conceptual or architectural revisions that substantially change the meaning, structure, or application of the standard |

---

## Guiding Principle

Use Semantic Versioning consistently across the HCOS framework.

Consistent versioning helps align:

- Document versions
- `CHANGELOG.md` entries
- Git tags
- GitHub Releases

This approach makes HCOS documents easier to navigate, cite, compare, and reference over time.

---

## Git Tags

Git tags should identify the exact approved version represented by a release.

### Individual Standard

```text
hcos-302-v1.1.0
```

### Repository Release

```text
v1.1.0
```

The Git tag should always point to the exact commit representing the approved release.

---

## Repository Releases

Repository releases represent approved snapshots of the HCOS framework.

Each GitHub Release should include:

- Version number
- Release title
- Release date
- Summary
- Major additions
- Major improvements
- Known limitations
- Review or validation status
- Links to primary documents

---

## Document Releases

Individual standards may evolve independently.

Each standard should maintain its own:

- Version number
- `CHANGELOG.md`
- Review status
- Release history

This allows standards to mature independently while remaining aligned with the broader HCOS framework.

---

## Related Documents

- [`RELEASE_PROCESS.md`](RELEASE_PROCESS.md)
- [`REVIEW_STANDARD.md`](REVIEW_STANDARD.md)
- [`CHANGELOG_GUIDELINES.md`](CHANGELOG_GUIDELINES.md)
- [`CONTRIBUTING.md`](CONTRIBUTING.md)


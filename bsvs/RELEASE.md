# BSVS Release Policy

Browser security evolves rapidly, so BSVS must update more often than most standards. At the same time, adopters, auditors, and tooling vendors need stable identifiers they can cite. This document defines the release model that balances those two goals.

## Versioning Scheme

BSVS uses a two-part version number:

```text
v<MAJOR>.<MINOR>
```

Examples: `v0.1`, `v1.0`, `v1.01`, `v2.0`.

- **MAJOR** changes when chapters or sections are added, removed, restructured, or when control objectives change.
- **MINOR** changes when requirements are added, removed, or materially modified within the existing chapter and section structure.

Patch-level fixes (typos, link corrections, language polish that does not change a requirement's meaning) are applied directly to the in-progress version and do not produce a separate version number.

## Scope Rules by Change Type

### Patch fix (in-branch, no version bump)

Allowed:

- Typo and grammar fixes.
- Broken or relocated reference links.
- Editorial clarifications that do not change which evidence an auditor would request or accept.

Not allowed:

- Changing the verifiable condition of a requirement.
- Changing a requirement's level.
- Adding or removing requirements.

### Minor release (e.g., `v1.0` to `v1.01`)

Allowed:

- Adding new requirements within an existing section.
- Removing requirements that are obsolete, duplicated, or superseded.
- Materially modifying requirement text, including level changes.
- All patch-level changes accumulated since the previous minor.

Not allowed:

- Adding, removing, or renaming chapters.
- Adding, removing, or renaming sections within a chapter.
- Changing a chapter's control objective.

### Major release (e.g., `v1.x` to `v2.0`)

Allowed:

- Anything a minor release allows.
- Adding, removing, or restructuring chapters and sections.
- Revising control objectives.
- Renumbering requirements where structural change requires it.

## Repository Layout

Each released version lives in its own folder. Once a version is released its folder is locked, and the next version is opened in a new folder:

```text
bsvs/
├── 0.1/         <- current draft
├── 1.0/         <- future stable release (locked after release)
├── 1.01-dev/    <- next minor release in progress
```

## Referencing Across Versions

Use the full versioned form when citing requirements:

```text
BSVS-v<version>-V.S.R
```

For example, `BSVS-v0.1-3.2.1`. The unversioned form `BSVS-3.2.1` resolves to the latest version, which works for casual reference but should be avoided in anything that needs to remain stable.

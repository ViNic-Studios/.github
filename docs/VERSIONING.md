# Versioning

This project follows Semantic Versioning using the format:

**MAJOR.MINOR.PATCH**

Example: `1.4.2`

The purpose of versioning is to clearly communicate the impact of changes and keep releases predictable.

## Version Number Breakdown
### MAJOR version

Increment the MAJOR version when we introduce **breaking changes**.

Examples:
- Removing or significantly changing existing features
- Changes that require users to update behavior or data
- Major architectural or design changes

Example bump:
`1.0.0` → `2.0.0`

### MINOR version

Increment the MINOR version when adding **new features** that are **backward-compatible**.

Examples:
- Adding a new screen or feature
- Enhancing existing functionality without breaking current behavior

Example bump:
`1.2.0` → `1.3.0`

### PATCH version

Increment the PATCH version for **bug fixes and small improvements**.

Examples:
- Bug fixes
- Performance improvements
- Minor UI tweaks that do not change behavior

Example bump:
`1.2.3` → `1.2.4`

## How We Use Versioning in This Project
- Version numbers are updated when changes are released, not for every commit.
- The version number should be updated as part of the release pull request.
- Pull requests should indicate which type of change they introduce:
    - PATCH (bug fix or small improvement)
    - MINOR (new feature)
    - MAJOR (breaking change)

## Pre-1.0.0 Versions

Before reaching version `1.0.0`, the app is considered early development.

During this phase:
- Breaking changes may occur in MINOR versions
- We still follow the same versioning structure for consistency

Examples:
- `0.3.0` → `0.4.0` (new feature)
- `0.4.1` → `0.4.2` (bug fix)

## Summary

| Change Type        | Version Bump |
|--------------------|--------------|
| Breaking change    | MAJOR        |
| New feature        | MINOR        |
| Bug fix / cleanup  | PATCH        |
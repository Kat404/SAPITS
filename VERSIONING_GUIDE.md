# SAPITS Versioning Guide

## 📌 Introduction

This guide outlines the simplified versioning system for the SAPITS project, adapted to better suit our current needs.

## 🔢 Version Format

We use a simple format: `MAJOR.UPDATE.FIX`

- **MAJOR (X.0.0)**: Significant milestones or major changes
- **UPDATE (1.X.0)**: New features or improvements
- **FIX (1.0.X)**: Minor bug fixes

Example: `1.2.3`

## 📋 Versioning Rules

### 1. Initial Version
- Start at `0.1.0`
- Version `1.0.0` marks the first stable release

### 2. When to Increment

#### MAJOR (X.0.0) when:
- Reaching a significant milestone
- Major methodology changes
- Completing a major development phase

#### UPDATE (1.X.0) when:
- Adding new features
- Making significant improvements
- Updating core documentation

#### FIX (1.0.X) when:
- Fixing minor bugs
- Correcting typos
- Minor formatting adjustments

## 🔄 Release Process

1. **Development**
   - Use `main` branch for active development
   - New features in `feature/*` branches

2. **Release**
   - Create `vX.Y.Z` tag for releases
   - Update `CHANGELOG.md`

## 📅 Versioning Example

```
0.1.0 - Initial project version
0.2.0 - Added basic documentation
0.3.0 - Implemented methodology guide
0.3.1 - Minor documentation fixes
1.0.0 - First stable release
1.1.0 - Added contribution guide
1.1.1 - Formatting fixes
```

## 📝 CHANGELOG Maintenance

Maintain `CHANGELOG.md` with:
- New features
- Notable changes
- Bug fixes

## 📚 Resources

- [Semantic Versioning](https://semver.org/)
- [Keep a Changelog](https://keepachangelog.com/)

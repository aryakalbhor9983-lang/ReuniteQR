# Changelog

All notable changes to the ReuniteQR project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Planned
- Multilingual support for improved accessibility.
- Emergency notification functionality.
- Enhanced privacy controls for QR-linked profiles.
- Improved lost-and-found matching and record management.
- Additional location-sharing and reunification assistance features.

## [1.0.0] - 2025-XX-XX

### Added
- Initial release of ReuniteQR.
- QR code generation linked to user profiles.
- QR code scanning to access profile and contact details.
- Google sign-in via Firebase Authentication.
- User profile management with emergency contact details.
- Location assistance using interactive maps (Leaflet + OpenStreetMap).
- Lost-and-found record management.
- Administrative portal for managing records, users, and settings.
- Responsive web interface for desktop and mobile browsers.
- Firestore security rules for access control.
- Docker support with Dockerfile and docker-compose.yml.
- Capacitor integration for Android builds.

### Security
- Firebase Authentication for secure user login.
- Firestore security rules to restrict unauthorized access.
- Environment variables excluded from version control.

---

## How to Update This File

When releasing a new version, add a new section at the top:

```markdown
## [X.Y.Z] - YYYY-MM-DD

### Added
- New features.

### Changed
- Changes to existing functionality.

### Deprecated
- Features that will be removed soon.

### Removed
- Features that were removed.

### Fixed
- Bug fixes.

### Security
- Security-related changes.

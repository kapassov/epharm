# Changelog

All notable production changes to Epharm are recorded here. The format follows
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/) and release tags use semantic versioning.

## [Unreleased]

## [1.0.1] - 2026-09-15

- Fixed App Store Connect release signing for CI/TestFlight builds.

## [1.0.0] - 2026-09-15

### Added

- First TestFlight candidate of the Epharm pharmacist mobile application.
- Production API configuration for `https://epharm.inkar.kz`.
- iOS privacy declarations, deep links, receipt camera and training QR support.

- Production-grade PostgreSQL and MinIO backup, retention, isolated restore testing and backup metrics.
- Prometheus, Alertmanager, Grafana, exporters and actionable availability/SLO/capacity alerts.
- Sentry integration points for backend, admin frontend and Flutter mobile application.
- Immutable release identity, deploy verification and rollback tooling.
- A k6 workload model for a 500-cash-desk fleet.
- Automated mobile release gates, privacy manifest and deep-link declarations.

## [0.1.0] - 2026-09-08

### Added

- Initial versioned baseline for the existing backend, admin, mobile and POSM applications.

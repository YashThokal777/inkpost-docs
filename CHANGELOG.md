# Changelog

## [2.0.0] - 2026-10-15

### Changed

- Increased the API rate limit from 300 to 600 requests per minute.
- The Free plan now includes 3,000 emails per month, up from 2,000.
- Pro plan price changed from $20 to $25 per month.
- Deprecated `POST /v1/send`. Use `POST /v1/messages` instead.

### Removed

- Removed `GET /v1/stats`. Use `GET /v1/events` instead.

## [1.3.0] - 2026-07-01

### Added

- Attachments up to 10 MB per message.
- New `GET /v1/events` endpoint.

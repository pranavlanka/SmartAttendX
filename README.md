# SmartAttendX - Software Requirements Specification

This repository contains the SRS and versioned change history for SmartAttendX.

## Versioning
- v1.0 - Baseline SRS (initial).

### v1.1 - Liveness Detection & Enrollment (date: YYYY-MM-DD)
- Added enrollment procedure (5 images, normalization).
- Added liveness detection (blink/head-turn/smile).
- Added failure logic: fallback to QR after 3 fails.

### v2.0 - QR Code: Dynamic + Validation (date: YYYY-MM-DD)
- Added dynamic QR spec (session_id, expiry, nonce, HMAC).
- Defined single-use and time-limited QR behavior.
- Specified fallback behavior for failed QR verification.

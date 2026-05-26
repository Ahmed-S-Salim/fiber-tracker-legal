# Privacy Policy — Fiber Unit Tracker

**Effective date: 2026-05-25**

Fiber Unit Tracker ("the app", "we") is published by Ahmed Sabah Salim. This policy explains what data the app handles and how.

## TL;DR

The app stores everything **locally on your device**. It does not transmit data to us or to any third party. There is no account, no cloud, no analytics, no ads.

## What the app collects

The app stores the following data **on your device only**:

| Data | Why | Stored |
|---|---|---|
| Device serial numbers and barcode scans | Core inventory feature | Local Room database |
| Work order numbers and details (OCR results) | Core feature | Local Room database |
| Technician names and PIN hash | Multi-user login | Local Room database (PINs are one-way hashed, never stored in plaintext) |
| Optional GPS coordinates of scans | Show where a unit was last seen | Local Room database |
| Photos captured for OCR/batch scan | Processing only — discarded after extraction | Not persisted unless you explicitly save |

## What the app does NOT do

- Does NOT send any of the above data to us or to any external server.
- Does NOT include third-party analytics, advertising, tracking, or crash-reporting SDKs.
- Does NOT require an account or internet connection.
- Does NOT share data between users.

## Permissions

| Permission | Reason |
|---|---|
| Camera | Required for barcode scanning, OCR, and batch photo scanning. Used only while the camera screen is open. |
| Fine / Coarse Location | Optional. If you grant it, the app tags each scan with GPS coordinates so you can see where a unit was last handled. Disable any time in Android Settings. |
| Biometric / Fingerprint | Optional. Used for biometric login as an alternative to your PIN. The fingerprint never leaves the Android secure enclave. |
| Vibrate | Haptic feedback on successful scans. |

## Data export

You can export your local data to Excel, CSV, or PDF at any time. Exported files are written to your device's storage. What you do with them after that is up to you.

## Data deletion

To delete all data, uninstall the app, or use Settings → Clear Database inside the app.

## Children

The app is not directed to children under 13. It is a tool for working technicians.

## Changes

If this policy ever changes, the new version will replace this file and the effective date will be updated.

## Contact

Questions? Email **ahmedsabahsalim@gmail.com**.

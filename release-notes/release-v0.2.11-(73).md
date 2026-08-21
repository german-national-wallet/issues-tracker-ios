### Release Notes - v0.2.11 (73)

Features
- Added the revocation onboarding screens
- Added the credential dashboard and credential detail screens
- Switched the EAA issuance flows to their final UI
- Updated the PIN screen to the new design
- Added push notification support
- Re-issuing an EAA credential from the same issuer now replaces the existing one instead of storing both
- Displayed the credential logo instead of the issuer logo for EAA credentials
- Added reusable templates for the content screens
- Unified iOS and Android error handling, including error traces that were previously dropped
- Made the exported logs readable and complete for review, with sensitive values, network bodies and the authorization code redacted
- Reduced feature flag fetching to once a day
- Key attestations are now included in the DPoP proof sent to the token endpoint
- Restricted the TLS handshake to compliant algorithms on newer iOS versions
- Issuance now takes the client id solely from the wallet attestation, and the unused hardcoded one was removed
- PID credential configuration identifiers are now set per environment and can be overridden by feature flags
- Added dynamic configuration support under settings

Fixes
- Presentation request popup did not appear when the wallet was opened from a cold start (fixes issue #8)
- White space and the status bar were visible on the splash screen
- Close buttons in the EAA issuance flow did not work
- Colors were inconsistent between the EAA offer and the credential dashboard
- Changing the device passcode permanently broke the wallet, and only deleting and reinstalling recovered it

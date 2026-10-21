### Release v0.4.3 (81)

**Features**
- Added an Activity list: users can see all credential activity (issuance and presentations) in the wallet dashboard, including a details view for each entry.
- Retry action added to failed presentations.
- Production access and registration certificates added.
- Re-issued sandbox trust anchors added.
- The first PID/EAA presentation now shows the overview screen.
- A minimum RSA key size is now enforced.
- The simulated eID card now uses a random pseudonym key.

**Fixes**
- The wallet rejection is now sent back to the relying party when the user declines a presentation.
- A valid MDVM token is now ensured before calls that need one, and the app recovers from an `ACCOUNT_NOT_FOUND` error during startup registration.
- The consent screen loading state is fixed.
- PIN view focus handling is fixed.
- Failed AES-GCM authentication now throws an error instead of failing silently.

**Known issues**
- PID credentials may display incorrectly or not at all (issue #20).

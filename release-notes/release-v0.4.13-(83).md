### Release v0.4.13 (83)

**Features**
- The app detects when the device is offline at the network layer and shows an accessible "no internet" dialog during presentation, issuance, onboarding and PID deletion.
- Timeouts are handled gracefully during startup, issuance and presentation.
- The number of credentials requested per PID batch is now 5 by default (previously 10).

**Security**=
- Credential request and response encryption now depends on the issuer's metadata (response encryption is supported, not forced). (Fixes Issue #29.)
- Keychain write failures for the encryption key and MDVM registration are now handled.
- Initialisation of the wallet data encryption key is now atomic.

**Fixes**
- The presentation request is now fetched only once.
- Presentation rate limit errors are shown correctly.
- Presentation error handling was updated for changed upstream errors.
- The eID card PIN retry after a wrong PIN is fixed.
- Keyboard navigation on iOS 27 is fixed.
- Accessibility focus on the "no internet" popup is fixed.

**Known issues**
- To be confirmed by the team.

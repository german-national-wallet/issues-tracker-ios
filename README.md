# issues-tracker-ios

A public repository for issues management and bug reporting for Germany's iOS Wallet Application

Current version: 0.2.4 (59)

## Supported features

| Area | Feature | Status | Version |
|---|---|---|---|
| OpenID4VCI | Issue PID credentials in both mdoc and SD-JWT VC formats | ✅ | 0.2.4 (59) |
| OpenID4VCI | Issue EAA credentials from issuer offers and the in app list | ✅ | 0.2.4 (59) |
| OpenID4VCI | Open and issue from an issuer credential offer link | ✅ | 0.2.4 (59) |
| OpenID4VCI | Secure issuance with PAR, DPoP and wallet attestation | ✅ | 0.2.4 (59) |
| OpenID4VCI | Complete deferred credentials | ✅ | 0.2.4 (59) |
| OpenID4VCI | Re issue PID credentials using the stored refresh token | ✅ | 0.2.4 (59) |
| OpenID4VP | Present PID and EAA credentials to verifiers | ✅ | 0.2.4 (59) |
| OpenID4VP | Verify the verifier identity (x509_hash and x509_san_dns) | ✅ | 0.2.4 (59) |

## Upcoming features

| Area | Feature | Expected |
|---|---|---|
| OpenID4VCI / OpenID4VP | Present a credential during issuance of another credential | June 2026 |
| OpenID4VCI | Validate signed issuer metadata | August 2026 |
| OpenID4VCI | Encrypt credential issuance requests | August 2026 |
| OpenID4VP | Present credentials through the browser or OS Digital Credentials API | August 2026 |

## Changelog

### v0.2.4 (59)

- Pin retry counter reduced to 3
- Fixed multiple EAA issuance
- Fixed PID presentation that showed no value for nationality and resident city
- Fixed enabling and disabling the platform authenticator
- Fixed the CAN flow

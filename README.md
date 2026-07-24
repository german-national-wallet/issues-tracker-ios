# issues-tracker-ios

A public repository for issues management and bug reporting for Germany's iOS Wallet Application

Current version: [v0.2.7 (68)](/release-notes/release-v0.2.7-(68).md)

## Supported features

| Area | Feature | Status | Version |
|---|---|---|---|
| OpenID4VCI | Issue PID credentials in both mdoc and SD-JWT VC formats | ✅ | 0.2.4 (59) |
| OpenID4VCI | Issue EAA credentials, in both mdoc and SD-JWT VC formats, both wallet initiated and issuer initiated flows | ✅ | 0.2.4 (59) |
| OpenID4VCI | Resolve a Credential Offer, both by value and by reference | ✅ | 0.2.4 (59) |
| OpenID4VCI | Use PAR Endpoint for issuance | ✅ | 0.2.4 (59) |
| OpenID4VCI | Use DPoP to sender-constrain Access Tokens | ✅ | 0.2.4 (59) |
| OpenID4VCI | Send Wallet Attestations | ✅ | 0.2.4 (59) |
| OpenID4VCI | Send Key Attestations for PID Issuance | ✅ | 0.2.4 (59) |
| OpenID4VCI | Re-issue credentials using refresh tokens | ✅ | 0.2.4 (59) |
| OpenID4VP | Present PID and EAA credentials to verifiers | ✅ | 0.2.4 (59) |
| OpenID4VP | Verify the verifier identity, supported client_id_schemes are <ul><li>x509_san_dns</li> and <li>x509_hash</li></ul> | ✅ | 0.2.4 (59) |
| OpenID4VP | Send encrypted presentation responses to verifiers | ✅ | 0.2.4 (59) |

## Upcoming features

| Area | Feature | Expected |
|---|---|---|
| OpenID4VCI / OpenID4VP | Present a credential during issuance of another credential | July 2026 |
| OpenID4VCI | Validate signed issuer metadata | August 2026 |
| OpenID4VCI | Obtain information about the issuer using Issuers' Registration Certificates included in the issuer metadata | August 2026 |
| OpenID4VCI | Support non key-bound EAAs | September 2026 |
| OpenID4VCI | Send Key Attestations during Key-bound EAA Issuance | September 2026 |
| OpenID4VCI | Encrypt credential issuance requests and responses | September 2026 |
| OpenID4VP | Prevent overasking using RP Registration Certificates included in the presentation requests | Q3 2026 (Conditional to Reference Implementation's implementation) |

note that no support for Digital Credentials API is planned due to the lack of support on iOS

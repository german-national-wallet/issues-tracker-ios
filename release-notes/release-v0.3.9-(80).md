### Release Notes - v0.3.9 (80)

Features
- Built the settings screen, including wallet loss protection
- Added the app intro and platform authentication setup screens
- Issuer metadata must now be signed, and is checked against bundled trust anchors
- Presentation requests are refused when the relying party is not registered to ask for the data
- Presentation errors are now shown in designed dialogs, with a specific message for each
- Each app variant now bundles its own trust anchors
- Updated the wallet kit and RASP libraries

Fixes
- Unsatisfiable presentation or declining one now notifies the verifier
- Calls to rWSCA and the wallet backend used a stored MDVM token without checking it was still valid
- eID developer mode was on in apps that do not offer PID simulation
- The retry button after a failed PID issuance went to the wrong screen
- SBOMs named the wrong supplier for packages that do not name one

Known issues
- PID credentials are displayed incorrectly or not at all (issue #20)
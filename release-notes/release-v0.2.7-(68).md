### Release Notes - v0.2.7 (68)

Features
- Implement new color tokens and fonts
- Integrate splash screen
- Validate NiScy's OpenID4VP response encryption implementation
- implement presentation during issuance
- Implement delete RWSCA endpoint and clean the key deletion

Fixes
- Remove Scaleway X-Auth-Token from refreshUrL to PID Provider
- After disabling and re-enabling PA, the wallet is deleted, but PID can only be issued after app restart
- Ensure that the actual requested claims are disclosed
- When disabling and re-enabling platform authentication, after re-issuing the PID, it only shows up in the wallet after restarting the application

Known issues
- Transport pin flow is not working as expected
- please reinstall the app if you still have 0.2.4 (59)



| Authenticator Type | Example | Notes |
|--------------------|---------|-------|
| Memorized Secret | Password | |
| | PIN | | |
| Look-Up Secret | [Apple Recovery Key](https://support.apple.com/en-us/HT208072) |
| | [Google Backup Codes](https://support.google.com/accounts/answer/1187538?hl=en) | |
| Out-of-Band | [Auth0 Guardian](https://auth0.com/docs/multifactor-authentication/guardian/user-guide) |
| | [Duo Push](https://duo.com/product/trusted-users/two-factor-authentication/authentication-methods/duo-push)
| Single-Factor OTP | [Google Authenticator](https://support.google.com/accounts/answer/1066447?visit_id=1-636451702615247824-1299740415&hl=en&rd=1) |
| | [Bluink App](htttps://bluink.ca/key)
| | [SecurID](https://www.rsa.com/en-us/products/rsa-securid-suite/rsa-securid-access/securid-hardware-tokens.html) | |
| | [DIGIPASS GO](https://www.vasco.com/products/two-factor-authenticators/hardware/one-button/index.html)
| | [SecureOTP](https://www.securemetric.com/two-factor-authentication-solution/)
| Multi-Factor OTP | [SafeNet GOLD OTP Authenticator](https://safenet.gemalto.com/multi-factor-authentication/authenticators/one-time-password-otp/gold-challenge-response-token/) |
| Single-Factor Cryptographic Software | Client TLS certificate |
| | [SSH key](https://www.ssh.com/key/)
| Multi-Factor Cryptographic Software | Password-protected Client TLS certificate
| Single-Factor Cryptographic Device | [FIDO U2F authenticator](https://fidoalliance.org/approach-vision/) |
| | [Bluink Key](htttps://bluink.ca/key)
| | [USBAuth](http://usbauth.com)
| | [Keydo Fido U2F](https://www.neowave.fr/US/keydo_fido_u2f.html)
| | [Yubikey](https://www.yubico.com/) | 1
| Multi-Factor Cryptographic Device | [FIDO UAF authenticator](https://fidoalliance.org/approach-vision/)
| | [Badgeo ID 2.0](https://neowave.fr/US/badgeo_ID_2.html)
| | [PIV](https://csrc.nist.gov/publications/fips/fips201-1/FIPS-201-1-chng1.pdf) and CAC cards
| | [Tyfone Side-X](https://tyfone.com/products/side-x-digital-endpoint-security/)
| | [Smart Card](http://www.smartcardalliance.org/smart-cards-intro-standards/#isoiec-standards)


Notes:

1. Only verifier-impersonation resistant when used in FIDO U2F mode


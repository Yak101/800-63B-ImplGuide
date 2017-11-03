| Authenticator Type | Example | Notes |
|--------------------|---------|-------|
| Memorized Secret | Password | |
| | PIN | | |
| Look-Up Secret | [Apple Recovery Key](https://support.apple.com/en-us/HT208072) |
| | [Google Backup Codes](https://support.google.com/accounts/answer/1187538?hl=en) | |
| Out-of-Band | [VASCO Virtual DIGIPASS](https://www.vasco.com/products/two-factor-authenticators/software/sms/virtual-digipass.html) | Restricted
| | [SMS Passcodes](https://duo.com/product/trusted-users/two-factor-authentication/authentication-methods/sms-passcodes) | Restricted
| | [Duo Push](https://duo.com/product/trusted-users/two-factor-authentication/authentication-methods/duo-push)
| Single-Factor OTP | [Google Authenticator](https://support.google.com/accounts/answer/1066447?visit_id=1-636451702615247824-1299740415&hl=en&rd=1) |
| | [RSA SecurID](https://www.rsa.com/en-us/products/rsa-securid-suite/rsa-securid-access/securid-hardware-tokens.html) | |
| | [VASCO DIGIPASS GO](https://www.vasco.com/products/two-factor-authenticators/hardware/one-button/index.html)
| Multi-Factor OTP | [SafeNet GOLD OTP Authenticator](https://safenet.gemalto.com/multi-factor-authentication/authenticators/one-time-password-otp/gold-challenge-response-token/) |
| Single-Factor Cryptographic Software | Client TLS certificate |
| Multi-Factor Cryptographic Software | Password-protected Client TLS certificate
| Single-Factor Cryptographic Device | [FIDO U2F authenticator](https://fidoalliance.org/approach-vision/) |
| | [Yubikey](https://www.yubico.com/) | 1
| Multi-Factor Cryptographic Device | [FIDO UAF authenticator](https://fidoalliance.org/approach-vision/)
| | [PIV](https://csrc.nist.gov/publications/fips/fips201-1/FIPS-201-1-chng1.pdf) and CAC cards
| | [Smart Card](http://www.smartcardalliance.org/smart-cards-intro-standards/#isoiec-standards)


Notes:

1. Only verifier-impersonation resistant when used in FIDO U2F mode


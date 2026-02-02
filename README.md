# otp-authenticator-webapp [![starline](https://starlines.qoo.monster/assets/qoomon/otp-authenticator-webapp)](https://github.com/qoomon/starlines)

[![Build Workflow](https://github.com/appmakervishal/authenticator/workflows/Build%20&%20Deploy/badge.svg)](https://github.com/appmakervishal/authenticator)

A *Google Authenticator* like offline webapp.

Hosted at github pages: https://appmakervishal.github.io/authenticator/

> [!Important] 
> ☂️ No External Services are used, local JavaScript execution only ☂️

### Features
* generate TOTP codes
* show remaining valid seconds for totp code
* generate QR-code with OTPAuth URL
  * click on QR-code to copy OTPAuth URL
* parse OTPAuth URLs in the `secret` input field
  * e.g. `otpauth://totp/john.doe?secret=N2SJSUOXCKQM5MAX7N7J3NBUQ4WTL66G&issuer=example.org`
  
### Host in Your Own GitHub Account
* Fork this repo
* Go to your forked Repository -> `Settings` -> `GitHub Pages`
  * Ensure `Source` is set to `gh-pages`
  * Find your link to the app `Your site is published at https://USERNAME.github.io/otp-authenticator-webapp/`

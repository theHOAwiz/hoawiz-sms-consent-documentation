# The HOA Wiz — SMS Consent Documentation

SMS consent documentation for Twilio A2P 10DLC campaign verification.

## Overview

The HOA Wiz is an iOS mobile application for HOA (Homeowners Association) management. During account registration, users are required to provide a phone number for identification purposes. SMS consent for receiving one-time verification codes is **optional** — users can complete registration without opting in to SMS.

## Opt-In Flow

1. User enters their phone number (required for account identification)
2. An **optional** SMS consent checkbox is displayed (unchecked by default)
3. The checkbox is clearly labeled "(Optional)" and is **not required** to submit the registration form
4. Users who do not check the box can still register and use the app fully — email verification is used instead

## Consent Language Displayed

The optional SMS consent checkbox displays the following text:

> **(Optional)** I consent to receive one-time SMS verification codes from **The HOA Wiz** for account authentication and security purposes. Message frequency varies. Message and data rates may apply. Reply STOP to opt out or HELP for assistance. See our [Terms of Service](https://thehoawiz.github.io/legal/terms-of-service.html) and [Privacy Policy](https://thehoawiz.github.io/legal/privacy-policy.html).

## Screenshots

The screenshots below show the registration flow within the iOS app:

- **hoawiz-signup-consent-overview.png** — Registration form with phone number field and optional SMS consent checkbox (unchecked, default state)
- **hoawiz-signup-consent-detail.png** — Close-up of the SMS consent checkbox area showing "(Optional)" label and full disclosure text
- **hoawiz-signup-consent-checked.png** — SMS consent checkbox in checked state (user has voluntarily opted in)

## Legal Documents

- **Privacy Policy:** https://thehoawiz.github.io/legal/privacy-policy.html
- **Terms of Service:** https://thehoawiz.github.io/legal/terms-of-service.html

## Contact

- **Email:** thehoawiz@gmail.com
- **Phone:** (310) 430-5116

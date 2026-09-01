# Fiuu Mobile XDK Integration Documentation

Welcome to the **Fiuu Mobile XDK Integration Guide** — a documentation site for merchants integrating **Fiuu Mobile XDK** into native and cross-platform apps.

## Overview

**Fiuu Mobile XDK** is a mobile payment SDK that connects merchant apps to the Fiuu payment gateway. This site covers payment parameters, e-wallet app-to-app flow, deeplink return, Apple Pay, response handling, and framework-specific setup.

## Getting Started

1. Visit the documentation site: https://fiuupayment.github.io/XDK-Webview/
2. Open **Documentation**.
3. Follow the guide for your framework.
4. Test in Sandbox (`mp_core_env = "4"`) before going live.

## Key Features

- **12 frameworks** — Android, iOS, Flutter, React Native, Expo, Ionic Capacitor, Cordova, .NET MAUI, and more
- **Shared `mp_*` parameters** across all SDKs
- **E-wallet app-to-app flow** — TNG, GrabPay, ShopeePay, Boost
- **Deeplink return** after wallet and online banking payments
- **Apple Pay and Google Pay** setup
- **Checksum and IPN** verification guidance

## Documentation Structure

- **Introduction**: What Fiuu Mobile XDK is and how integration works
- **Overview & Prerequisites**: Supported SDKs, versions, and platform requirements
- **Payment Parameters**: Full `mp_*` reference
- **E-Wallet Payment Flow**: App-to-app sequence, deeplink return, and server callback
- **Core Integration**: Environments, express mode, and channel filtering
- **Response Handling**: Result JSON, checksum, and IPN
- **Deeplink Setup**: Return to the merchant app after wallet / banking flows
- **Apple Pay**: Merchant ID, certificates, and XDK parameters
- **Framework Guides**: Native Android, native iOS, and cross-platform
- **Support & Resources**: Contact channels and official repositories

## Requirements

- Registered Fiuu merchant credentials (Sandbox and/or Production)
- App URL / deeplink registered in the Fiuu Merchant Portal for e-wallet return
- Platform toolchain matching the framework guide (Android minSdk 26+, iOS 16+, and so on)

## Support

If you encounter any issues or need assistance, please reach out to our integration team:

- Email: support@fiuu.com

## License

This documentation is proprietary and intended for authorized partners and merchants only.

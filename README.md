# Fiuu Mobile XDK Integration Documentation

Welcome to the **Fiuu Mobile XDK Integration Guide** — a documentation site designed to help partners and merchants seamlessly integrate secure payment capabilities into mobile applications across multiple platforms and frameworks.

## Overview

The **Fiuu Mobile XDK** is a mobile payment software development kit (SDK) that provides a pre-integrated connection to the Fiuu payment gateway. It handles payment initiation, channel selection, status tracking, and in-app redirection — so you do not need to build complex payment flows from scratch.

## Getting Started

To begin your integration journey:

1. Visit the documentation site: https://fiuupayment.github.io/XDK-Webview/
2. Navigate to the **Introduction** section.
3. Review [Overview & Prerequisites](https://fiuupayment.github.io/XDK-Webview/docs/overview-and-prerequisites/).
4. Follow the integration guide for your framework.

## Key Features

- **12 framework guides** — Native Android, iOS, Flutter, React Native, Expo, Ionic Capacitor, Cordova, and .NET MAUI
- **Complete `mp_*` parameter reference** — Mandatory fields, optional settings, Apple Pay, Google Pay, and cash channel support
- **Environment configuration** — Production, UAT, and Sandbox environments
- **Express mode** — Direct channel routing for subscribed payment methods
- **Deeplink redirection** — E-wallet and online banking return-to-app flows
- **Response handling** — Payment result parsing and checksum verification

## Documentation Structure

- **Introduction**: What is Fiuu Mobile XDK and how it works
- **Overview & Prerequisites**: Platform requirements and SDK repositories
- **Payment Parameters**: Full `mp_*` parameter reference
- **Core Integration**: Environment configuration, express mode, and channel filtering
- **Response Handling**: Payment result parsing and checksum verification
- **Deeplink Setup**: Mobile application deeplink redirection configuration
- **Apple Pay Setup**: Apple Merchant ID and payment processing certificate setup
- **Framework Integration Guides**: Step-by-step guides for each supported platform
- **Support & Resources**: Contact channels, SDK repositories, and developer resources

## Supported Frameworks

| Category | Frameworks |
| -------- | ---------- |
| **Native Android** | Android Library (Java), Android Kotlin |
| **Native iOS** | Swift, Objective-C, SwiftUI, CocoaPods Framework |
| **Cross-Platform & Hybrid** | Flutter, React Native, Expo, Ionic Capacitor, Cordova, .NET MAUI |

## Requirements

- Registered Fiuu merchant account with API credentials
- Mobile development environment matching your framework's prerequisites
- Deeplink scheme registered on the Fiuu Merchant Portal (for e-wallet and banking flows)

## Support

If you encounter any issues or need assistance, please reach out to our integration team:

- Email: [support@fiuu.com](mailto:support@fiuu.com)
- Developer Forum: [t.me/FiuuDeveloperForum](https://t.me/FiuuDeveloperForum)

## License

This documentation is proprietary and intended for authorized partners and merchants only.

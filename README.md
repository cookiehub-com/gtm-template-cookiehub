# CookieHub CMP template for Google Tag Manager

This repository contains the official CookieHub tag template for Google Tag Manager, the easiest way to add the CookieHub Consent Management Platform (CMP) to your GTM container.

## Installation

1. In Google Tag Manager, open **Templates** and search for **CookieHub** in the Community Template Gallery, then add the template to your workspace.
2. Create a new tag using the CookieHub CMP template and enter your 8 character domain code, available in the [CookieHub dashboard](https://dash.cookiehub.com) under Domain overview.
3. Set the tag to fire on the **Consent Initialization - All Pages** trigger and publish.

Detailed setup instructions are available in the [CookieHub docs](https://docs.cookiehub.com/installation/google-tag-manager).

## Features

- **Google Consent Mode v2** — sets default consent states (globally and per region), restores stored consent before the container loads, and updates consent state as visitors make their choices
- **IAB TCF and GPP** — optionally injects the Transparency & Consent Framework and Global Privacy Platform stub scripts
- **60+ languages** — override the dialog language per container or dynamically through a variable
- **Flexible configuration** — URL passthrough, consent lifetime, cross-domain consent linking, UI visibility controls and more

To use the template you must create a CookieHub account. You can register at [cookiehub.com](https://www.cookiehub.com) — a free plan and a 14-day trial of the premium features are available.

## License

Licensed under the [Apache License 2.0](LICENSE).

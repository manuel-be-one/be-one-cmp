# Be One CMP

Lightweight, configurable Consent Management Platform (CMP) for the web.
Includes a Google Tag Manager template and a minimal JS UI with GA4 consent mode support.

## Features
- GA4 Consent Mode integration (setDefaultConsent, consent updates)
- Simple UI: accept, refuse, configure; per-service toggles
- Optional logo (image URL + alt)
- Multilingual copy (EN/FR/NL/DE/IT/ES auto-detected)
- Works with Webflow, WordPress, PrestaShop, any site

## Events
Emits GA4-friendly events via `dataLayer`:
- `cookie_banner_first_display`
- `cookie_banner_accept_all`
- `cookie_banner_refuse`
- `cookie_banner_configure`
- `cookie_banner_save_preferences` (with granted/denied service lists)
- `consent_ready` after updates

## License
All rights reserved. This repository is proprietary.
See LICENSE for details.

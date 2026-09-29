# Awesome-Consent-Preference-Management

# Top Consent Preference Management Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Cookie Consent, Preference Centers, GDPR/CCPA Compliance, IAB TCF, Google Consent Mode & Privacy Banners*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Consent Preference Management** (CMP). These systems collect, store, and signal user consent for cookies, tracking, and data processing—supporting GDPR, ePrivacy, CCPA, IAB TCF, and Google Consent Mode.

**Examples** include OneTrust, Usercentrics, Cookiebot, Didomi, TrustArc, Osano, Iubenda, Crownpeak Consent, Consentmanager, and Termly (the category leaders).

**Open-source emphasis**: Enterprise CMPs with TCF certification and multi-domain governance are largely commercial. Strong open options exist for self-hosted banners and script blocking—**Klaro**, **CookieConsent**, **tarteaucitron.js**, and related libraries. This section expands those projects while remaining realistic about certification and audit gaps.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[OneTrust](https://www.onetrust.com/)**  
  Enterprise privacy and consent platform with CMP, preference centers, and broad regulatory coverage (GDPR, CCPA, TCF, and more).

- **[Usercentrics](https://usercentrics.com/)**  
  Consent management platform with web and mobile SDKs, TCF support, and Google Consent Mode integration.

- **[Cookiebot](https://www.cookiebot.com/)**  
  Widely used cookie consent and scanning platform for websites, with automatic cookie discovery and consent logging.

- **[Didomi](https://www.didomi.io/)**  
  Consent and preference management platform for web, apps, and publishers with TCF and multi-channel support.

- **[TrustArc](https://trustarc.com/)**  
  Privacy management platform including consent, cookie compliance, and broader privacy program capabilities.

- **[Osano](https://www.osano.com/)**  
  Consent and cookie compliance platform with scanning, banners, and consent record features (also maintains an open cookie consent library).

- **[Iubenda](https://www.iubenda.com/)**  
  Privacy and cookie solution suite—policies, consent, and cookie banners for websites and apps.

- **[Crownpeak Consent](https://www.crownpeak.com/)**  
  Enterprise digital experience and consent management capabilities for large multi-site organizations.

- **[Consentmanager](https://www.consentmanager.net/)**  
  CMP focused on publishers and multi-domain consent, with TCF support and acceptance-rate optimization features.

- **[Termly](https://termly.io/)**  
  Privacy policy, cookie consent, and compliance toolkit aimed at small and mid-size websites.

## Open-Source GitHub Projects
- **[Klaro](https://github.com/kiprotect/klaro)**  
  Open-source, privacy-friendly consent manager—self-hosted banner, service blocking, purpose grouping, and GDPR-oriented configuration (BSD-3).

- **[CookieConsent (orestbida)](https://github.com/orestbida/cookieconsent)**  
  Popular lightweight open-source cookie consent library (MIT)—vanilla JS, configurable categories, and widely used for self-hosted banners.

- **[Osano Cookie Consent](https://github.com/osano/cookieconsent)**  
  Open-source cookie consent library (MIT) from Osano—simple, customizable banner with callback-based script control.

- **[tarteaucitron.js](https://github.com/AmauriC/tarteaucitron.js)**  
  Open-source French-origin consent manager with a large service catalogue and native Consent Mode–oriented patterns.

- **[c15t / community CMP projects](https://github.com/)**  
  Modern open-source consent stacks with loaders, Consent Mode support, and optional TCF-oriented add-ons.

- **[ConsentStack CMP](https://github.com/ConsentStack/cmp)**  
  Open-source, developer-focused consent management platform experiments for human-centric preference UX.

- **[IAB Tech Lab reference implementations](https://github.com/InteractiveAdvertisingBureau)**  
  Open reference code and specifications for TCF and related consent string standards used by certified CMPs.

- **[Google Consent Mode open integration patterns](https://developers.google.com/tag-platform/security/guides/consent)**  
  Documentation and community examples for wiring consent signals to Google tags from open or commercial CMPs.

- **[Self-hosted preference center open templates](https://github.com/)**  
  Community templates for storing and updating granular marketing/analytics preferences beyond cookie banners.

- **[Documentation and open CMP playbooks](https://klaro.org/)**  
  Guides for deploying self-hosted consent UIs, script blocking, and first-party consent storage.

### Additional Strong Open-Source Options
- Using **Klaro** or **CookieConsent** for fully self-hosted, no-vendor-lock-in cookie banners.
- Adopting **tarteaucitron.js** when a rich built-in service catalogue is useful.
- Wiring open banners to **Google Consent Mode v2** via custom callbacks.
- Accepting that IAB TCF certification, Google-certified CMP status, multi-domain enterprise governance, consent proof/audit logs at scale, and mobile SDKs still favor commercial platforms (OneTrust, Usercentrics, Didomi, Cookiebot, Consentmanager, etc.).
- Focusing open-source efforts on privacy (no third-party CMP script), cost control, and full ownership of consent UI and storage.

**Frameworks for building custom systems**: Deploy Klaro/CookieConsent → declare services and purposes → block scripts until consent → store first-party consent records → emit Consent Mode / TCF signals where required. Suitable for marketing sites, documentation sites, and privacy-focused products. Ad-funded publishers and large enterprises typically need certified commercial CMPs.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Consent tools support legal compliance but do not guarantee it. Open-source CMPs require correct configuration, record-keeping, and legal review for your jurisdiction. This list is not legal advice.

---
**Made for privacy engineers, marketers, and open-source consent advocates.**
Let's keep consent transparent, user-controlled, and as open as practical.

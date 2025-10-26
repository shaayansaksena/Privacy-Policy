---
title: Untangle – Privacy Policy
layout: default
---

**Untangle – Privacy Policy**

**Last updated:** Oct 26 2025

**Overview**  
Untangle helps you understand your screen habits through clear, on-device analytics. All processing happens locally on your computer. Untangle does not send data to any server or third party.

**The use of information handled by Untangle adheres to the Chrome Web Store User Data Policy, including the Limited Use requirements.**

**What information we process (locally)**  
Untangle computes and stores only the minimum needed to show time and insights:

- Domain-level time and daily aggregates: seconds per domain, minute-level activity, number of switches, tab churn, deep/micro sessions, longest focus streak, and derived features (productive %, switches/hr, day vs. night minutes).
- Daily labels and suggestions: an interpretable label (e.g., Focused, Fragmented) with confidence, plus optional “things to look out for”.
- Your settings and overrides: site categories you enter and whether you mark sites as Productive/Unproductive/Misc.
- On-device model: when enough days exist, Untangle stores a small local clustering model (centroids, standardization stats, cluster→label mapping). No data leaves your device.
- Runtime snapshot (session storage): ephemeral state (e.g., last tick time) to make tracking robust across service worker restarts.

*Note:* Under Chrome’s definitions, hostnames and visit times are “Web history” data even if stored only on-device and even if the History API is not used.

**What we do not process**  
- No personally identifiable information (PII), emails/messages, health or financial data.  
- No page content, keystrokes, mouse clicks, or scroll logs.  
- No full browsing history list. We only extract the hostname of the active tab (e.g., docs.google.com) for time attribution; paths/parameters are not stored.  
- No IP, GPS, or device location.

**How we use the information**  
- To compute and display domain-level time, daily labels, focus metrics, and trends.  
- To personalize labels on-device after you’ve accumulated enough days, mapped back to clear categories.  
- To export your data to CSV/JSON and to honor “Delete all data”.

**What we share**  
Nothing. Untangle does not transmit or share your data with any external server, third party, or analytics provider.

**Permissions and why we request them**  
- `tabs`: Observe active tab changes, attribute time to domains, and manage session timing; no page content is read or modified.
- `windows`: Count time only when Chrome is focused (foreground use).
- `idle`: Respect away/locked state and apply a brief reading grace to avoid over/under‑counting.  
- `alarms`: A lightweight 1‑minute pulse that wakes the service worker to keep time accurate during long reads.  
- `storage`: Store settings, daily aggregates, and the on‑device model in Chrome storage (local + session). Users can export or delete data in Options.

**Security**  
- All data is kept in Chrome’s local storage on your device.  
- No external transmission; no remote servers or third-party SDKs receive your data.

**Data retention, access, and deletion**  
- **Retention:** Data remains on your device until you delete it or uninstall the extension.  
- **Access:** View summaries and export CSV/JSON in Options.  
- **Deletion:** Use “Delete all data” in Options to remove all stored data. Uninstalling the extension also removes stored data.

**User choices and controls**  
- Enable or disable tracking in Options or the popup.  
- Edit categories and productivity flags (Productive/Unproductive/Misc).

**Limited Use disclosure**  
The use of information adheres to the Chrome Web Store User Data Policy, including the Limited Use requirements. We collect and use browsing activity only to provide user-facing features described in our Web Store listing and UI.

**Changes to this policy**  
We may update this policy to reflect product or regulatory changes. We will revise the “Last updated” date and publish updates on this page.

**Contact**  
If you have questions, contact: shaayan.saksena1@gmail.com


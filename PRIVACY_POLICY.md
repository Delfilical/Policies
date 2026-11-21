# NosoNotes — Privacy Policy

**Effective date:** 14 November 2026 (previous: 24 October 2026)
**Applies to:** the NosoNotes by Delfilical browser extension (Chrome / Edge), release v0.9.2 and the releases it supersedes (v0.9.1, v0.9.0, v0.8.0, v0.7.0, v0.6.2-beta). *v0.9.2 note: no change to data practices; still no network requests and nothing transmitted. The docked panel's position down the window is now remembered alongside its width, and the separate certificate import on the settings page is removed, so an imported certificate is no longer stored (any stored copy is deleted).* *v0.9.1 note: no change to data practices. A guidance pack may now carry a signing date and an expiry date set by the trust that made it; these are part of the pack file you load and are shown on screen, and nothing new is stored or transmitted.* *v0.9.0 note: no change to data practices — still no network requests and nothing transmitted. The release adds two locally stored preference items, described under Preferences below: a per-document count of how often you have opened a reference document online (used only to show you a one-time "consider downloading it" tip on your own screen) and whether you dismissed that tip. The counts never leave your browser.* *v0.8.0 note: no change to data practices — the release was user-interface only (search-term pills, result-view defaults). It stores strictly less than v0.7.0: result-band view choices are no longer saved between searches, and the extension suppresses the browser's own autofill dropdown on the site's search box (no data is read, written or transmitted by that change).*
**Developer contact:** Philip Taylor — Delfilical · support@delfilical.co.uk

## Summary

NosoNotes collects no data. Nothing you do in the extension is transmitted, uploaded, synced, or shared with the developer or any third party. Everything the extension stores stays on your computer, inside your own browser profile.

## What the extension stores, and where

NosoNotes is a reference search tool for clinical coders. It stores the following, all locally on your device:

**Personal coder notes.** Notes you write (title, text, associated codes, keywords) are stored in the browser's extension storage (`chrome.storage.local`) on your device. They are created by you, readable only by you, and never leave your browser. You can export them to a file, import them from a file, or delete them at any time from the extension's settings page.

**Reference PDFs.** Copies of the published coding standards documents that you load yourself are stored in the extension's local IndexedDB database on your device, so they reopen automatically. They are never uploaded anywhere. You can remove them at any time with the × button in the viewer.

**Local guidance packs.** If you load a trust's signed guidance pack, the pack (its coding guidance, including its licence certificate — public verification data only) is stored in the extension's local IndexedDB. Packs are loaded by you and never transmitted; you can remove them at any time from the settings page. The certificate contains no secret or identifying data — it is only the public material used to check, on your device, that a pack is genuinely your trust's.

**Reference documents (the guidance shelf, from v0.9.0).** If you load a signed shelf file indexing a published reference document, it is stored like a guidance pack. Attaching your own downloaded copy of such a document stores it like a reference PDF. Neither is transmitted anywhere.

**Preferences.** Display, search-layer and guidance-source settings are stored locally in extension storage and the page's local storage. From v0.9.0 this also includes the panel's width and whether it is open (from v0.9.2 also its position down the window), and your choice of panel or classic layout (the layout choice is mirrored into the page's local storage so it can be read before the extension draws). Also from v0.9.0: the NosoForge licence state, which is the name of the licensed trust and the certificate's expiry date, derived from a loaded signed pack (until v0.9.2 also from a trust certificate imported on the settings page; that import is removed in v0.9.2 and any stored copy deleted). Nothing about the licence is transmitted anywhere. One detail for completeness: the layout choice and the licensed trust's name are mirrored into the Classifications Browser page's own local storage (the layout so the panel can be drawn before the extension's storage is read), which means they are readable by that site's scripts in your browser, in the same way as anything else stored for that site. No other NosoNotes data is stored there. From v0.9.0 this includes, per reference document, a count of how many times you have opened it online and whether you dismissed the resulting "consider downloading a copy" tip — used only to decide whether to show you that tip, stored only on your device, and removable like any other stored data.

## What the extension does not do

- It does not collect, transmit, or share any personal information, health information, patient data, or staff data.
- It makes no network requests. The extension requests no host permissions and contains no code paths that send data to any server. There is no backend.
- It contains no analytics, telemetry, tracking, advertising, or crash reporting.
- It does not read pages other than the NHS Classifications Browser (classbrowser.nhs.uk), the only site it runs on.
- It does not use cookies and does not identify you in any way. The developer has no means of knowing who uses the extension or how.

## Data categories (store disclosure)

For the purposes of the Chrome Web Store and Microsoft Edge Add-ons privacy declarations: NosoNotes does not collect personally identifiable information, health information, financial information, authentication information, personal communications, location data, web history, user activity, or website content. All categories: **not collected**.

## Patient data

NosoNotes is a guidance reference tool only. It has no access to patient record systems and processes no patient data. If a coder chooses to type information into a personal note, that note exists only in their own browser; users should follow their organisation's information governance policies on what they record in notes.

## Your control

All data the extension stores is yours and is under your control: export or delete notes from the settings page, remove PDFs from the viewer, or remove the extension to delete its stored data entirely. Because the developer holds no copy of any of your data, there is nothing for the developer to access, correct, or erase on your behalf.

## When you contact Delfilical

NosoNotes sends nothing to Delfilical. Delfilical (the trading name of Philip Taylor, a sole trader in England) does hold a small amount of personal data outside the app, and is responsible for it:

- **Emails to support@delfilical.co.uk:** your name, email address and what you write. Used only to answer you and fix problems. Deleted 2 years after the last message.
- **NosoNotes Web testing:** while NosoNotes Web is in testing it sits behind a sign-in run by Cloudflare. Your work email is on the testers' list so you can sign in. It is removed when testing ends, or sooner if you ask.
- **Trust contacts:** names, roles and work emails of people at trusts who have asked about or use NosoNotes, so we can arrange trials, licences and support.

We use this data because we have a legitimate interest in answering you and running the service. We never sell it or use it for marketing without asking. Only the services that carry it see it: Microsoft (Outlook email) and Cloudflare (email forwarding and NosoNotes Web sign-in). Both may handle it in the United States, under the UK-US data bridge.

You can ask for a copy of your data, or ask us to correct or delete it, by emailing support@delfilical.co.uk. If you are unhappy with how we handle it, you can complain to the Information Commissioner's Office at ico.org.uk/make-a-complaint or on 0303 123 1113.

## Legal basis

The app collects and sends no personal data, so for the app itself Delfilical is not a data controller under UK GDPR. Data you store in your browser stays under your (or your organisation's) control. For the data described under "When you contact Delfilical", Delfilical is the controller.

## Changes to this policy

If a future version of NosoNotes changes how data is handled (for example, optional shared note packs), this policy will be updated before that version is released, the version's changelog will say so, and the store listings will link to the updated policy.

## Contact

Questions about this policy or the extension: Philip Taylor — support@delfilical.co.uk

# Privacy Policy

Last updated: September 19, 2026

Versh is a local-first lyrics and songwriting notebook for Android and iOS. This Privacy Policy explains what information the app handles, how it is used, and what choices you have.

Features and data handling depend on your platform, app version, and settings. The in-app advertising section applies to builds where advertising is enabled; earlier or ad-disabled builds do not request in-app advertisements.

## Information Versh Handles

Versh stores content you create or import, including song titles, lyrics, sections, chords, tablature, notation, projects, tags, snapshots, custom chord voicings, guitar tunings, settings, voice or melody recordings, and section video recordings.

Versh may also process:

- Images, camera captures, PDFs, and text files that you explicitly select for import.
- Words that you explicitly request a dictionary definition for.
- Google account identity information when you choose to connect Google Drive
  backup on Android.
- Purchase and entitlement information needed to provide Premium features.
- In ad-supported builds, technical advertising information and advertising privacy choices, as described under **In-App Advertising and Advertising Privacy** below.
- App usage events and crash diagnostics. Starting with version 0.1.3, collection is enabled by default, while previously saved opt-outs remain honored. Earlier versions with telemetry controls collect according to the choices made in those versions.

## Local Storage

Songs, recordings, imported content, and settings are stored locally on your device by default. Versh does not operate its own server for your songwriting content.

If you uninstall Versh or clear its app data, locally stored content may be
deleted unless you exported a backup or enabled cloud backup.

## Imports, Camera, Photos, and OCR

When you choose a file, photo, or camera scan, Versh processes it to extract lyrics, chords, or tablature. OCR uses Google ML Kit's on-device text recognition. Selected content is used only for the import you start and is not sent by Versh to Firebase Analytics, RevenueCat, or advertising providers.

ML Kit does not send the input images or recognized text to Google servers, but its SDK sends technical usage and diagnostic information, such as installation identifiers, app/device metadata, feature usage, processing latency, and error codes. Google uses this information for diagnostics, usage analysis, and improving its services under the [ML Kit terms](https://developers.google.com/ml-kit/terms). Versh's saved Firebase analytics or Crashlytics opt-outs do not control ML Kit's separate SDK telemetry.

Versh may create temporary local images while reading PDFs or scans. These temporary files are not intended to be retained as part of your library after processing.

## Microphone, Camera, Audio, and Video

Versh uses microphone access only when you start an audio recording,
note-recognition feature, or section video recording. It uses camera access only
when you explicitly open section video capture. The camera preview and selected
section lyrics or chords are displayed together for reference, but the lyrics
and chords are not burned into the captured video.

Audio and video recordings remain on your device unless you explicitly share,
export, or include them in an optional backup. Versh does not intentionally send
camera imagery, microphone audio, or recordings to analytics, diagnostics,
dictionary, advertising, consent-management, or purchase providers.

## Dictionary Lookups

Current versions provide definitions, synonyms, and rhymes from bundled or downloaded offline language packs. These lookups do not send selected words or lyric text to a remote service. When you browse or download language packs, the catalog and download hosts receive ordinary network information such as your IP address, request time, and the requested pack URL.

Earlier versions that use `api.dictionaryapi.dev` send the selected word when you request a definition, but not the surrounding lyric line or full song. That service may receive ordinary network information under its own practices.

## Cloud Backup

Cloud backup is optional. It uses the platform's private, app-managed storage:

- On Android, Versh requests access only to Google Drive's hidden
  `appDataFolder`. The app receives basic Google account information, including
  account identifier, display name, and email address, so it can show which
  account is connected. Versh does not use or store the Google profile picture.
- On iOS, Versh stores backups in its private iCloud Drive container when you
  enable the feature and are signed in to iCloud Drive. The backup is not shown
  as a normal document in the Files app. Versh does not receive your Apple
  Account email address or profile information.

Cloud backups may contain songs, lyrics, chords, tabs, projects, tags,
snapshots, settings, chord voicings, tunings, recording metadata, audio files,
and section video files. Versh keeps up to three complete backup generations
and reuses unchanged media objects to avoid duplicate uploads. Backup manifests also contain a locally generated device identifier, device hostname, app version, and technical metadata needed to distinguish and restore generations. After you connect Drive backup, Versh can synchronize changes automatically as well as when you request a manual backup. Backups use encrypted network transport, but Versh does not apply end-to-end encryption to the backup payload. The developer cannot browse these backups through a Versh-operated server.

Disconnecting Google Drive stops future access but does not automatically delete existing hidden app data. You can delete that data through Google Drive's **Manage apps** settings.

Disabling iCloud backup in Versh stops future backup activity but does not
automatically delete existing backup data from your iCloud storage. You can
manage Versh's stored data and iCloud storage through Apple's system settings.

Google processes account and Drive information according to the
[Google Privacy Policy](https://policies.google.com/privacy). Apple processes
iCloud information according to the
[Apple Privacy Policy](https://www.apple.com/legal/privacy/).

## Usage Analytics

Versh uses Firebase Analytics to understand app usage and improve the app. Starting with version 0.1.3, collection is enabled by default for new installations and installations where no telemetry choice was previously made. A previously saved analytics opt-out remains honored on upgrade; the default policy is not recorded as an affirmative consent decision.

Analytics events may include app screens, feature actions, editor tool usage, backup outcomes, purchase-flow outcomes, app version, device type, operating system version, approximate region derived from IP addresses, session information, and event timestamps. The SDK also uses app-instance identifiers and records in-app purchase/subscription events. Earlier Android builds may access the Android advertising identifier where available. Ad-supported Android builds omit the advertising-ID permission, as described below. Versh does not intentionally send lyrics, song titles, recordings, imported documents, chord content, tag names, or project names to Firebase Analytics.

Versh links Analytics with Google Ads to measure acquisition campaigns, including installation, activation, and purchase conversions. Google Ads personalization and Analytics sharing with Google products and services are enabled. Consequently, Google may also use eligible Analytics data for its products and advertising services under its applicable policies; Analytics is not used solely as a developer-directed service provider. This acquisition measurement is separate from the in-app AdMob advertising described below. Google Signals is currently disabled.

Version 0.1.3 and later do not provide an in-app analytics switch or consent prompt. Earlier versions that include **Settings > Privacy** allow you to disable analytics there. When a saved opt-out applies, Versh disables future collection and resets analytics data stored by the app on the device. Clearing app data or reinstalling may remove the saved choice, in which case the current version's defaults apply.

## Crash Diagnostics

Versh uses Firebase Crashlytics to diagnose crashes and technical failures. Starting with version 0.1.3, collection is enabled by default for new installations and installations where no telemetry choice was previously made. A previously saved diagnostics opt-out remains honored on upgrade.

Crash reports may include stack traces, app and operating-system versions, device model, current app screen, Premium status, active song count, technical logs related to the failure, and installation identifiers used to distinguish affected app installations. Linked Firebase Analytics may also receive an automatic app-exception event when a crash occurs. Versh does not intentionally include songwriting content in crash reports.

Version 0.1.3 and later do not provide an in-app diagnostics switch or consent prompt. Earlier versions that include **Settings > Privacy** allow you to disable diagnostics there. Versh deletes unsent local crash reports when a saved diagnostics opt-out applies. Clearing app data or reinstalling may remove the saved choice.

Firebase services are provided by Google and are subject to the [Google Privacy Policy](https://policies.google.com/privacy).

## In-App Advertising and Advertising Privacy

### When advertisements are shown

In ad-supported builds, free users may see Google AdMob full-screen advertisements at eligible screen changes. Ads are not displayed on app launch or while writing, recording, playing recordings, or rehearsing. Premium removes these in-app ads. Versh does not use your lyrics or other songwriting content to select advertisements.

Versh requests **non-personalized ads** rather than ads selected from your interests or activity across other apps and websites. Non-personalized does **not** mean anonymous or data-free: advertising can still involve technical identifiers, approximate location, device storage, measurement, and fraud-prevention processing. Depending on the applicable requirements and privacy choices, Google may allow non-personalized or limited ads, or ads may not be requested.

### Advertising and consent information

Google's Mobile Ads SDK, User Messaging Platform (UMP), and participating advertising providers may process information such as:

- Your IP address and an approximate location inferred from it. Versh does not request precise GPS location for advertising.
- App and device information, such as app identifiers and version, device type, operating-system version, language, and network information.
- App-, device-, or developer-scoped technical identifiers, such as Android app set IDs, subject to platform restrictions and the configuration described below.
- Ad requests, impressions, taps, video-ad views, and related interaction or attribution information. These concern advertising interactions, not the contents of your audio or video recordings.
- SDK performance and diagnostic information, such as load failures, app launch time, hangs, and energy usage. Versh disables the Mobile Ads SDK's separate iOS crash reporter; this does not disable other SDK diagnostics or Firebase Crashlytics.
- Consent status, opt-out choices, and related privacy signals needed to select the applicable privacy message and apply your choices.

This information is used to deliver and measure advertising, operate consent controls, maintain service performance, and detect fraud or abuse. Google may share relevant information with advertising participants for these purposes under its policies and the applicable privacy choices.

Versh does not add lyrics, song titles, lookup words, recordings, imported documents, filenames, song or section identifiers, tag names, or project names to ad requests or consent messages. Advertising does not give advertisers access to your songwriting library or cloud backups.

In ad-supported Android builds, Versh removes the Android `AD_ID` permission instead of requesting access to the Android advertising identifier. On iOS, Versh does not request App Tracking Transparency authorization or access to IDFA. The iOS integration supports Apple's SKAdNetwork attribution mechanism without obtaining IDFA. These restrictions do not eliminate all technical identifiers, network data, or advertising measurement.

### Consent and privacy choices

In ad-supported builds, Versh uses Google's UMP to refresh advertising consent information before requesting ads. Where applicable, a European regulations message provides consent choices for the EEA, UK, and Switzerland; a US state regulations message provides applicable opt-out choices. The message you receive depends on your region and the requirements determined by UMP. Consent messages and choices are processed by Google and may be communicated to participating advertising providers so they can apply them.

When UMP requires a privacy-options entry point, Versh displays **Settings > Ad privacy**. Use it to review or change available choices, including withdrawing consent or exercising applicable advertising opt-outs. These controls can remain available after upgrading to Premium. If consent status cannot be checked successfully, or UMP does not permit an ad request, Versh skips ads rather than blocking your writing.

Advertising consent is **separate** from Firebase Analytics and Crashlytics collection, ML Kit SDK telemetry, RevenueCat purchase processing, and optional backups. Ad privacy choices do not change those services' settings or automatically disable them. In particular, current versions' Firebase defaults and previously saved opt-outs continue to work as described in **Usage Analytics** and **Crash Diagnostics**.

Premium stops new in-app ad requests and discards preloaded ads after the entitlement is recognized. UMP may still refresh the availability of existing privacy choices or display the privacy-options form when you request it. Premium does not disable other services described in this policy or delete information already processed by providers.

### Advertising storage and further information

Versh stores first-use and last-ad-attempt timestamps locally to enforce its advertising grace period and cooldown. These timestamps are not sent through Versh's analytics events or included in Versh song backups. UMP and advertising SDKs may separately store consent choices and technical information on the device. Clearing app data or uninstalling removes local app data but does not necessarily delete information already received by Google or other providers.

For information about Google's processing, see the [Google Privacy Policy](https://policies.google.com/privacy) and [How Google uses information from sites or apps that use its services](https://policies.google.com/technologies/partner-sites).

## Purchases

Versh uses RevenueCat to manage Premium products and entitlement status. RevenueCat may process an app user identifier, product identifiers, entitlement status, purchase and transaction status, app/device information, and related purchase metadata. The SDK initializes and checks entitlements at app startup, not only when you make a purchase. It generates a pseudonymous app user identifier when no explicit identifier is supplied; this does not create a named Versh account. RevenueCat collection is separate from Firebase telemetry preferences.

Payments are processed by Google Play or Apple's App Store. Versh does not receive your complete payment-card details. Purchases are subject to the relevant store's terms and privacy practices. RevenueCat processes information according to its [Privacy Policy](https://www.revenuecat.com/privacy/).

## Data Sharing

Versh does not sell or license your songwriting content to advertisers. Limited information is disclosed for features you use, analytics and diagnostics, advertising and consent management in ad-supported builds, purchase management, app distribution, legal compliance, or security, as described in the relevant sections above.

Versh does not intentionally provide your songwriting library to Firebase Analytics, Firebase Crashlytics, RevenueCat, or advertising providers. Offline writing-tool lookups remain local; the selected-word disclosure for older online dictionary features is described under **Dictionary Lookups**.

Some privacy laws define the sale or sharing of personal information broadly, including certain advertising-related disclosures even when no money changes hands. Advertising and Google Analytics/Google Ads processing should not be understood as a blanket promise of no such sharing. Where applicable, use the advertising privacy choices described above or contact the developer to exercise your rights.

When you use system sharing or export, the destination you select receives the exported content under that destination's own terms and privacy practices.

## Retention and Deletion

- Local content remains until you delete it, clear app data, or uninstall Versh.
- Archived songs remain recoverable until you choose **Delete forever**.
- Exported files remain wherever you save or share them until deleted there.
- Cloud backups remain until Versh replaces older generations or you delete the
  app-managed data through Google Drive or iCloud.
- Analytics and diagnostics are retained according to the configured Firebase retention settings and Google's applicable policies.
- Local advertising-frequency timestamps and SDK privacy preferences remain until cleared by the app or SDK, or removed with local app data. Google and participating advertising providers retain advertising, consent, diagnostic, and fraud-prevention records according to their policies and applicable requirements; changing a choice does not automatically delete previously collected records.
- Purchase and entitlement records may be retained by RevenueCat and the app stores as needed to provide purchases, prevent fraud, and meet legal obligations.

Versh does not provide a Versh account, so there is no separate Versh account to delete. To request information or deletion relating to data under the developer's control, email [vinsho.read@gmail.com](mailto:vinsho.read@gmail.com) with the subject **Versh data deletion** and describe the data you want deleted. Do not send lyrics, recordings, passwords, or payment-card details. The developer may ask for limited additional information needed to locate the relevant records. Some pseudonymous analytics records may not be identifiable from an email address alone. Purchase records may need to be retained for legal obligations. Use the local-content and cloud-provider deletion controls described above for data stored on your device or in your own backup account.

## Your Choices and Rights

You can:

- Use Versh without enabling cloud backup.
- Keep previously saved analytics and diagnostics opt-outs when upgrading without clearing app data. Version 0.1.3 and later have no in-app telemetry controls; earlier versions with **Settings > Privacy** retain their version-specific controls.
- In ad-supported builds, review or change advertising choices through **Settings > Ad privacy** when that entry is required and available, including applicable consent withdrawal and opt-out choices. You can also contact the developer about privacy rights.
- Use Premium without in-app advertisements; this does not disable the other services described in this policy.
- Manage microphone, camera, and photo access through system settings.
- Delete songs and recordings in Versh.
- Clear local app data or uninstall Versh.
- Export a local backup before deleting local data.
- On Android, disconnect Google Drive backup; on iOS, disable iCloud backup. Separately manage or delete stored backup data through the applicable provider.
- Manage or cancel subscriptions through Google Play or Apple's App Store.
- Contact the developer to exercise privacy rights available under applicable law, including access, correction, deletion, restriction, objection, or withdrawal of consent.

Withdrawing consent does not affect processing that occurred before withdrawal.

## International Processing

Google, Apple, RevenueCat, participating advertising providers, app stores, and other service providers may process
information in countries other than your own. Their processing and transfer
safeguards are governed by their own terms, privacy policies, and applicable
data-protection agreements.

## Children's Privacy

Versh is intended for a general audience and is not specifically directed to children. Parents or guardians should supervise minors' use where required by applicable law. If you believe a child has provided personal information requiring deletion, contact the developer through the store listing.

## Security

Versh uses mobile-platform storage, permissions, provider authentication, and
provider security controls. Google Drive backup data is stored in the connected
account's private app-data area. iOS backup data is stored in Versh's private
iCloud container. Cloud providers transfer backup data using encrypted network
connections. No storage or transmission method is perfectly secure, so you
should keep your own exports of important work.

## Changes to This Policy

This Privacy Policy may be updated as Versh changes. The updated version will be identified by the **Last updated** date above. Material changes may also be communicated in the app or store listing where appropriate.

## Contact

For privacy questions or requests, email
[vinsho.read@gmail.com](mailto:vinsho.read@gmail.com) or visit
[Versh Support](versh-support.md).

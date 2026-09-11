# Privacy Policy

Last updated: September 11, 2026

Versh is a local-first lyrics and songwriting notebook for Android and iOS. This Privacy Policy explains what information the app handles, how it is used, and what choices you have.

## Information Versh Handles

Versh stores content you create or import, including song titles, lyrics, sections, chords, tablature, notation, projects, tags, snapshots, custom chord voicings, guitar tunings, settings, and voice or melody recordings.

Versh may also process:

- Images, camera captures, PDFs, and text files that you explicitly select for import.
- Words that you explicitly request a dictionary definition for.
- Google account identity information when you choose to connect Google Drive
  backup on Android.
- Purchase and entitlement information needed to provide Premium features.
- App usage events and crash diagnostics. Starting with version 0.1.3, collection is enabled by default, while previously saved opt-outs remain honored. Earlier versions with telemetry controls collect according to the choices made in those versions.

## Local Storage

Songs, recordings, imported content, and settings are stored locally on your device by default. Versh does not operate its own server for your songwriting content.

If you uninstall Versh or clear its app data, locally stored content may be
deleted unless you exported a backup or enabled cloud backup.

## Imports, Camera, Photos, and OCR

When you choose a file, photo, or camera scan, Versh processes it to extract lyrics, chords, or tablature. OCR uses Google ML Kit's on-device text recognition. Selected content is used only for the import you start and is not sent to Firebase Analytics or RevenueCat.

Versh may create temporary local images while reading PDFs or scans. These temporary files are not intended to be retained as part of your library after processing.

## Microphone and Audio

Versh uses microphone access only when you start a recording or note-recognition
feature. Recordings remain on your device unless you explicitly share, export,
or include them in an optional cloud backup.

Versh does not intentionally send microphone audio or recordings to analytics, diagnostics, dictionary, or purchase providers.

## Dictionary Lookups

When you request a definition, Versh sends the selected word to `api.dictionaryapi.dev`. Versh does not send the surrounding lyric line or full song. The service may receive ordinary network information such as your IP address and request time under its own practices.

Offline rhyme suggestions do not send lyric text to a remote service.

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
snapshots, settings, chord voicings, tunings, recording metadata, and audio
files. Versh keeps up to three complete backup generations and reuses unchanged
audio objects to avoid duplicate uploads. The developer cannot browse these
backups through a Versh-operated server.

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

Analytics events may include app screens, feature actions, editor tool usage, backup outcomes, purchase-flow outcomes, app version, device type, operating system version, approximate region, session information, and event timestamps. Versh does not intentionally send lyrics, song titles, recordings, imported documents, chord content, tag names, or project names to Firebase Analytics.

Version 0.1.3 and later do not provide an in-app analytics switch or consent prompt. Earlier versions that include **Settings > Privacy** allow you to disable analytics there. When a saved opt-out applies, Versh disables future collection and resets analytics data stored by the app on the device. Clearing app data or reinstalling may remove the saved choice, in which case the current version's defaults apply.

## Crash Diagnostics

Versh uses Firebase Crashlytics to diagnose crashes and technical failures. Starting with version 0.1.3, collection is enabled by default for new installations and installations where no telemetry choice was previously made. A previously saved diagnostics opt-out remains honored on upgrade.

Crash reports may include stack traces, app and operating-system versions, device model, current app screen, Premium status, active song count, and technical logs related to the failure. Versh does not intentionally include songwriting content in crash reports.

Version 0.1.3 and later do not provide an in-app diagnostics switch or consent prompt. Earlier versions that include **Settings > Privacy** allow you to disable diagnostics there. Versh deletes unsent local crash reports when a saved diagnostics opt-out applies. Clearing app data or reinstalling may remove the saved choice.

Firebase services are provided by Google and are subject to the [Google Privacy Policy](https://policies.google.com/privacy).

## Purchases

Versh uses RevenueCat to manage Premium products and entitlement status. RevenueCat may process an app user identifier, product identifiers, entitlement status, purchase and transaction status, app/device information, and related purchase metadata.

Payments are processed by Google Play or Apple's App Store. Versh does not receive your complete payment-card details. Purchases are subject to the relevant store's terms and privacy practices. RevenueCat processes information according to its [Privacy Policy](https://www.revenuecat.com/privacy/).

## Data Sharing

Versh does not sell personal data and does not display third-party advertising.

Limited information is shared with service providers for features you use, analytics and diagnostics as described above, purchase management, app distribution, legal compliance, or security. Songwriting content is not intentionally shared with Firebase Analytics, Firebase Crashlytics, RevenueCat, or the dictionary service.

When you use system sharing or export, the destination you select receives the exported content under that destination's own terms and privacy practices.

## Retention and Deletion

- Local content remains until you delete it, clear app data, or uninstall Versh.
- Archived songs remain recoverable until you choose **Delete forever**.
- Exported files remain wherever you save or share them until deleted there.
- Cloud backups remain until Versh replaces older generations or you delete the
  app-managed data through Google Drive or iCloud.
- Analytics and diagnostics are retained according to the configured Firebase retention settings and Google's applicable policies.
- Purchase and entitlement records may be retained by RevenueCat and the app stores as needed to provide purchases, prevent fraud, and meet legal obligations.

Versh does not provide a Versh account, so there is no separate Versh account to delete. To request information or deletion relating to data under the developer's control, contact the developer using the contact details on Versh's store listing.

## Your Choices and Rights

You can:

- Use Versh without enabling cloud backup.
- Keep previously saved analytics and diagnostics opt-outs when upgrading without clearing app data. Version 0.1.3 and later have no in-app telemetry controls; earlier versions with **Settings > Privacy** retain their version-specific controls.
- Manage microphone, camera, and photo access through system settings.
- Delete songs and recordings in Versh.
- Clear local app data or uninstall Versh.
- Export a local backup before deleting local data.
- Disconnect Google Drive or disable iCloud backup, and separately manage or
  delete Versh's stored backup data through the applicable provider.
- Manage or cancel subscriptions through Google Play or Apple's App Store.
- Contact the developer to exercise privacy rights available under applicable law, including access, correction, deletion, restriction, objection, or withdrawal of consent.

Withdrawing consent does not affect processing that occurred before withdrawal.

## International Processing

Google, Apple, RevenueCat, app stores, and other service providers may process
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

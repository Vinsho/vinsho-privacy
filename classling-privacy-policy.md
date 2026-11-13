# Classling Privacy Policy

Last updated: November 13, 2026

Classling (also known as Class Ledger) is a classroom management app provided by Vinsho. This policy explains how the app handles information. Features may vary by platform and version.

## Classroom records and local storage

Classling stores the information you enter or import on your device: classes and terms, student names and identifiers, student photos and custom fields, enrollments, assignments, grades, rubrics, attendance, groups, seating plans, private notes and attached photos. App preferences and purchase status are also stored locally.

Classling does not require a Classling account or operate a server for your classroom records. Records are not automatically sent to the developer. They leave the device when you enable sync or use a backup, export, sharing or other service described below. Android automatic OS backup and device transfer are disabled for Classling; explicit app backups and sync remain available. Other platforms may apply their own device-backup settings.

## Files, photos, reports and sharing

Classling accesses files and photos you select to import or attach. Spreadsheet imports, grade calculations and report generation run on your device. Exported spreadsheets, PDFs and backups can contain personal student information. When you save or share a file, the destination or recipient you select receives that information under its own privacy practices.

Backups are not encrypted by Classling and can include archived records, private notes and photos. Store and share them only with people and services authorized to receive that information. A backup checksum detects corruption; it does not protect the file from being read.

## Optional backups

On Android and iOS, you can connect Google Drive to save backups in an app-managed folder in your Drive. Classling uses Google Sign-In and the limited `drive.file` permission to work with files it creates or that you authorize for the app; it does not request access to all of your Drive files. Google account identifiers and authentication credentials are used to connect the chosen account and authorize backup operations. Google receives the backup contents and ordinary connection information when you use this feature.

On iOS, you can select a backup folder through the system document picker, including an iCloud Drive folder. Classling stores access to that selected folder and writes backup files there. The document provider manages any cloud upload; a successful local write does not guarantee that remote synchronization has finished.

When automatic backup is enabled, Classling can write later backups to the connected destination without asking you to select it again. Disabling or disconnecting backup stops future app-managed backup activity but does not delete files already saved. Manage those files through Google Drive, Files or the selected provider. Backup history may be rotated by the app; keep independent copies of important records.

Google's processing is covered by the [Google Privacy Policy](https://policies.google.com/privacy); Apple's by the [Apple Privacy Policy](https://www.apple.com/legal/privacy/). Other document providers have their own policies. Classling uses Google user data only to provide the backup and sync functionality you authorize, not for advertising or selling that data. Its use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

## Optional Google Drive sync

On Android and iOS, you can connect Google Drive to sync saved classroom records between devices. Sync uses Google Sign-In and the limited `drive.appdata` permission to read and write Classling's hidden app-data storage. It does not read your other Drive documents. Sync is separate from the backup feature above.

When enabled, sync transfers classes, students, student photos and custom fields, grades, attendance, groups, seating plans, schedules, lesson plans, notes, attached files, rubrics and templates to the selected Google account. Account identifiers and credentials authorize the connection; enrollment credentials stay in platform secure storage. Google receives these records and ordinary connection information. Changes, including deletions, sync while Classling is open; offline work waits for a later connection. Devices connected to the same library can receive the shared records.

Sync files are compressed, not encrypted by Classling. Transfers use HTTPS and access is protected by Google account permissions; there is no separate recovery password. Historical edits and deletion markers can remain in sync files to support reconciliation and recovery from interrupted transfers. A deletion hides the current record on connected devices but does not immediately erase every historical copy. Pausing or disconnecting stops this device's transfers without deleting local or cloud records. Cloud data can be managed through Google Drive's app-data controls.

Google user data is used only for the backup and sync features you authorize, not for advertising or sale. The Google API Services User Data Policy, including its Limited Use requirements, applies to these uses.

## Optional iCloud sync

Instead of Google Drive, you can connect iCloud to sync the same classroom records between devices. Only one sync service is active for a library at a time. Sync stores records in Classling's container in your private iCloud database. The developer cannot access your private iCloud data.

On iPhone and iPad, sync uses the Apple Account signed in on the device. On Android, you sign in to your Apple Account in a browser page provided by Apple; Classling receives a web access token for its iCloud container and keeps it in platform secure storage. Apple receives the synced records and ordinary connection information.

Sync data is compressed, not encrypted by Classling; Apple's iCloud account protections and transport security apply. As with Google Drive sync, historical edits and deletion markers can remain to support reconciliation, and pausing or disconnecting does not delete local or iCloud records. On iPhone or iPad, you can delete Classling's iCloud data in Settings under your Apple Account, iCloud storage. Apple's processing is covered by the [Apple Privacy Policy](https://www.apple.com/legal/privacy/).

## Purchases

Classling uses RevenueCat to check and manage Premium access. In builds with purchases configured, the SDK initializes and checks entitlement status when the app starts, even if you have not purchased Premium. It uses a generated pseudonymous app user identifier and processes product identifiers, purchase history, transaction or receipt information, entitlement status, and relevant app and platform information. This supports purchase validation, restoration, fraud prevention and purchase reporting.

Classling does not send student names, grades, notes, photos or other classroom records to RevenueCat. Payments are processed by Google Play or Apple's App Store; Classling does not receive your full payment-card details. See [RevenueCat's Privacy Policy](https://www.revenuecat.com/privacy/) and the relevant store's policies.

## Advertising, analytics and support

Classling does not serve advertisements. Android and iOS release builds use Google Analytics for Firebase to understand app usage (such as screen visits, first opens and purchase actions) and Firebase Crashlytics to diagnose crashes and errors. Successful purchase events include the product identifier, price and currency. These services process app-instance or installation identifiers, app and device information, usage events, approximate location derived from masked IP addresses, and technical diagnostics. Advertising identifier collection and advertising personalization are disabled. Debug and isolated QA builds do not enable this reporting.

Classling does not attach student names, classroom identifiers, grades, notes, photos, imported files or account details to analytics events or app-reported errors. Screen events use fixed route templates. App-reported errors include the error type and stack trace; free-text exception messages and contextual record values are removed. Firebase may also collect native crash diagnostics and basic device information. The class analytics feature calculates classroom statistics locally. See [Firebase privacy information](https://firebase.google.com/support/privacy) and the [Google Privacy Policy](https://policies.google.com/privacy).

If you contact support, the developer receives your email address, message and any attachments you choose to send. Support actions do not automatically attach classroom records or diagnostic files. Please avoid sending student information unless necessary and authorized. Opening external links, including these documents on GitHub, exposes ordinary browsing information to the destination under its own policies.

## Website

The Classling homepage and legal pages use local static assets. They do not request Google sign-in, access Drive, or include app analytics or advertising scripts. Cloudflare, the website host, may process IP addresses, requested URLs and ordinary request or security information to deliver and protect the site. See [Cloudflare’s Privacy Policy](https://www.cloudflare.com/privacypolicy/). Following a store, support or other external link is subject to the destination's policies.

## Purposes and sharing

Information is processed to provide the features you request, manage purchases, respond to support, protect the service and meet legal obligations. Where applicable data-protection law requires a legal basis, these purposes rely on performance of the service contract, your consent for optional processing, legitimate interests in support and security, or legal obligations, as appropriate. You can withdraw optional access through app or system settings; withdrawal does not undo earlier lawful processing.

The developer does not sell classroom records or use them for targeted advertising. Information may be disclosed to the providers described above, recipients you select, or where legally required or necessary to protect rights and security.

## Retention, deletion and your rights

Local records remain until deleted in the app, cleared with app data, or removed through uninstalling, subject to operating-system backup and restore behavior. Archiving is not deletion. Deleting a record does not remove copies in earlier backups, exports or recipients' systems; delete those separately. Disconnecting a cloud account is not a request to delete existing cloud backups.

Purchase providers and stores retain transaction records as needed to provide entitlements, prevent fraud and meet legal obligations. Support correspondence is retained only as needed to handle requests and related legal or security requirements.

You may have rights to access, correct, export or delete personal information, restrict or object to processing, withdraw consent, and complain to a data-protection authority. For information controlled by the developer, contact [vinsho.read@gmail.com](mailto:vinsho.read@gmail.com) with the subject **Classling privacy request**. Provide only enough information to identify the request; do not send passwords, payment-card details or a full student database. The developer cannot retrieve or erase classroom records stored only on your device or in your own backup account. Some purchase records may need to be retained by the relevant provider.

## Students and children

Classling is intended for teachers and other authorized adults, not as an account-based service for children. It can nevertheless contain personal information about students, including children. The teacher or institution decides which student data to record and is responsible for having the necessary authority, notices, permissions and retention rules. Students or parents seeking access to classroom records should contact the teacher or institution that holds them. Contact the developer if you believe student information has been disclosed to the developer improperly.

## Security and international processing

Classling relies on operating-system storage and access controls, and the authentication and security controls of connected providers. It does not provide its own encryption for the classroom database, exported backups or sync files. Protect your device and backup destinations; no storage or transmission method is completely secure.

Google, Apple, RevenueCat, Cloudflare, GitHub and email or document providers may process information outside your country under their policies and applicable transfer safeguards.

## Changes and contact

This policy may be updated as Classling changes. The date above identifies the current version; material changes will receive additional notice where required.

Contact: [vinsho.read@gmail.com](mailto:vinsho.read@gmail.com). See also the [Classling Terms of Service](classling-tos.md).

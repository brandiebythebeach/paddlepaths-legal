---
layout: default
title: Beta Privacy Policy
---

# Paddle Paths — Beta Privacy Policy

**Effective September 12, 2026.** This notice covers the current private iOS beta, including the account-deletion update; it does not describe planned future features.

Paddle Paths is operated by Brandie Minnich. Contact **brandie.minnich@gmail.com** with privacy questions or requests.

## What we collect and why

**Your account.** Browsing published Paths and launches does not require an account. Creating an account or signing in sends your email and password to Supabase Authentication. We use account identifiers, authentication records and an account profile to provide sign-in and account-linked features. A session is stored on your device to keep you signed in. The current Profile screen does not request a home address or home area.

**Your location and recordings.** With permission, Explore uses your current location to position the map. When you start recording, Paddle Paths collects precise GPS coordinates and sample times, plus accuracy, altitude and device-reported speed when available. These records support distance/speed calculations, activity history, interruption recovery and diagnostics. Background permission lets an active recording continue while the screen is locked or the app is in the background. This beta does not maintain a general location history outside recording.

Recording samples—including fixes rejected for movement calculations—are saved on your device. If you are signed in, the app automatically attempts private synchronization after completion and when you return to Record. It uploads accepted route geometry, activity/account identifiers, recording mode, an optional intended Path, start/end times and summary measurements. It does not upload the complete raw GPS-fix table through this sync flow. Offline activities remain on the device for retry. Completed recordings made without an account can be assigned to the account that later signs in on that installation.

Private synchronized activities are not part of public browsing. Database access rules restrict ordinary users to their own activities. Authorized service administration and hosting-provider processing remain possible; “private” does not mean inaccessible to the operator or provider.

**Saved Paths and contributions.** Saving a Path stores its identifier, your account identifier and a timestamp. You can remove the saved association without deleting the Path.

Creating a candidate Path is a separate, deliberate action. We store its recorded route geometry, source references, trimming information, metadata, craft suitability, optional launch association, notes and geographically anchored annotations. We also keep submission/moderation states and revision history for review and provenance. Candidates do not automatically become public. If a moderator publishes a Path, its published geometry, notes and annotations are available without signing in and may reveal places you traveled or described. Avoid personal information in content intended for publication.

**Settings and feedback.** Distance-unit and announcement preferences are stored locally. Milestone notifications and spoken distance announcements use device notification and speech facilities. The app does not record microphone audio or register with a Paddle Paths remote-push server. Speech receives milestone text, not your GPS track; operating-system voice processing is controlled by the platform.

If you provide feedback or diagnostic files, we receive the information you send. Diagnostics may contain precise location data: review them before sharing. Apple TestFlight also provides beta feedback, crash and usage reporting under Apple's terms.

## Services used by this beta

- **Supabase** provides account authentication and backend storage, currently in East US (Ohio). Its infrastructure receives ordinary network information such as IP addresses and request timing. See [Supabase privacy information](https://supabase.com/privacy).
- **MapLibre Native** renders maps using **OpenFreeMap** map resources. Map requests reveal the requested map area and ordinary network information to map infrastructure, which may include its CDN. The app does not upload your full recording, account session or password to a map-provider track service. Requested tiles may nevertheless correspond to your location. See [OpenFreeMap's privacy notice](https://openfreemap.org/privacy/).
- **Apple/iOS and TestFlight** supply platform location, speech, notifications, distribution and beta reporting. See [TestFlight information](https://testflight.apple.com/).

The current app does not integrate advertising, behavioral analytics, HealthKit/Fitbit access, contact-list uploads, photo uploads or payment collection. These statements describe Paddle Paths, not every independent practice of its providers.

## Retention, deletion and your controls

Account and activity data do not have an automatic expiration schedule in this beta. You can stop or pause recording, change announcements, revoke location/notification permission in iOS Settings, remove Saved Paths and sign out. Signing out alone does not delete your account or recording history. Local history is device-wide, not isolated by login; consider this when sharing a device.

**Delete Account** is available in the signed-in Profile area and requires confirmation. It removes your authentication account, profile, private synchronized activities and geometry, Saved Paths, reports, and your contributed Paths, launches, notes and annotations—including submitted and published contributions. Associated historical personal content is also erased rather than retained solely for provenance. Removing a Path removes its attached content and associations. Other creators' separate Paths and private activities remain; references to your removed content may disappear.

Deletion also stops this account's active recording and removes its owned recordings, raw GPS samples and milestone records from **the device where you request deletion**. Recordings belonging to another account, recordings not yet assigned to any account, and device-wide announcement/unit preferences remain. Deletion clears the local sign-in session after cleanup. It cannot remotely erase copies on another device.

An internet connection is required to confirm server deletion. If completion cannot be confirmed, the app shows a pending/error state and offers retry; do not assume deletion succeeded from a failed request. A pending deletion blocks account switching and synchronization until resolved. Confirmed deletion can finish interrupted device cleanup after reopening the app. The server retains only an opaque random completion receipt, without your account identifier, GPS or contribution content, to support this recovery.

These controls remove active application records, not every possible external copy. Device backups, provider backups/security logs, previously supplied feedback and copies others made of published material are not all erased by the mobile operation. Their retention has not been independently verified, and we do not promise a fixed backup-erasure deadline. Contact us about additional access, correction or deletion requests. This beta does not provide comprehensive export or individual activity deletion controls.

Backend requests use HTTPS. Device storage is not separately encrypted by the app, and the service does not provide end-to-end encryption. No security measure guarantees protection against every risk.

Approved revisions will be posted at the public policy page with an updated effective date.

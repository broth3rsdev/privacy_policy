---
title: "Privacy Policy - On Air Radio"
lang: en
---

# Privacy Policy for On Air Radio

**Last updated:** 13 August 2026

On Air Radio is a free internet radio player for Romanian radio stations, developed by broth3rsdev. This policy explains what happens to your data when you use it.

## Summary

There is no account and no sign-in. On Air Radio has no analytics, no crash reporting, no advertising, and no tracking SDKs. I never receive your personal data. Everything the app remembers about you - your favorites, alarms, listening history and settings - stays on your device.

The app does rely on one backend that I operate: a hosted database holding the directory of radio stations. It stores station details only, never anything about you. Everything else goes directly to the radio stations you listen to and the other services listed below, exactly as it would if you opened those streams yourself.

## Information stored on your device

The app stores the following locally, in its private app storage:

- The station directory it downloads: the name, country, stream address, logo address and website of each station.
- Your favorites and your recently played stations. These exist only on your device and are never sent anywhere.
- Your alarms: time, repeat days, chosen station, snooze length and fade-in length.
- App preferences, such as theme color and mode, language, list or grid layout, auto-play, and the last station you played.
- A cache of station logo images, kept so artwork still appears offline.

None of this is transmitted to me. Uninstalling the app, or clearing its storage in system settings, removes all of it.

The app allows Android's standard automatic backup, so the items above may be copied into your own Google Drive backup, encrypted and tied to your Google account. I have no access to that backup. You can disable it in your device's backup settings.

## Information sent to third parties

Using the app causes your device to contact these services directly:

- **The station directory**, hosted on Supabase (`khktcoshqvnrhpsdkxti.supabase.co`). The app reads the list of stations and listens for updates to it. Those requests reach the service with your IP address. No favorites, listening history or device identifiers are ever sent. Supabase provides the hosting; see [supabase.com/privacy](https://supabase.com/privacy).
- **Radio stations.** When you play a station, your device connects straight to that broadcaster's streaming server, which receives your IP address and may keep its own logs. Every station is operated independently and applies its own policy. Some stations stream over plain HTTP rather than HTTPS, so those connections are not encrypted.
- **Logo hosts.** Station artwork is fetched from the addresses the stations publish, and those servers receive your IP address.
- **Google Play services**, for Google Cast and Android Auto. When you cast, the station's stream address is sent to the receiving device and Google Play services handles device discovery and the session. Google Play also collects installation and diagnostic data as store operator, independently of this app. See [policies.google.com/privacy](https://policies.google.com/privacy).
- **The Google Play Store**, only if you tap "Rate app", which opens the store listing.
- **Any website you open.** Tapping a station's website opens it in an in-app browser, and that site applies its own policy and may set its own cookies.

## Analytics, crash reporting and advertising

There are none. The app contains no analytics, telemetry, attribution, or advertising SDKs, and no crash reports are transmitted anywhere. Diagnostic logs exist only in memory while the app runs.

The audio visualiser in the player is drawn from the audio the app is already decoding in order to play it. The app holds no microphone permission and records nothing.

If you use the "Send feedback" option, your email app opens with the address and subject filled in. Nothing is sent until you send it yourself, and you can edit or delete anything beforehand.

## Cookies

The app sets no cookies for its own purposes and keeps no login session. Websites you open in the in-app browser may set their own cookies, which belong to those sites.

## Permissions

- **Internet and network state:** to download the station list and play streams.
- **Notifications:** to show the playback controls and the alarm notification.
- **Foreground service, wake lock and Wi-Fi lock:** to keep playback running while the screen is off.
- **Alarms and reminders (exact alarms):** so radio alarms ring at the time you set.
- **Run at startup:** to restore your alarms after the device reboots.

The app requests no location, contacts, microphone, camera, or photo access.

## Legal basis and your rights (EEA/UK)

Where the GDPR applies, the limited processing carried out by the app rests on legitimate interest in making the app work: delivering the station directory and connecting you to the stream you choose. There is no account and I hold no copy of your data, so requests for access, correction, erasure, portability, or objection are satisfied on your device by clearing the app's storage or uninstalling it. Requests concerning data held by a radio station or other third party should be directed to that party. You may lodge a complaint with your local data protection authority.

## Contact

Questions about this policy: [broth3rsdev@gmail.com](mailto:broth3rsdev@gmail.com)

# MuslimEcho Privacy Policy

_Last updated: 6 November 2026_

MuslimEcho is a prayer-times, adhan and Qur'an app for Android TV / Google TV. It is built to collect
nothing about you.

## The short version

- **No account, no sign-in.**
- **No ads, no analytics, no tracking.** MuslimEcho contains no advertising, analytics or
  crash-reporting libraries. The only Google library is Google Play Billing, used solely for the
  optional "buy us a coffee" tips.
- **We don't collect, sell or share personal data.** We (the developer) don't run any server and
  receive nothing from the app.
- **Your settings stay on your TV.** Prayer times are calculated on the device, offline.

## What is stored on your TV

Your settings (city and its coordinates, calculation method, adhan choices, language, display
preferences) and small caches (today's verse, mosque photo, downloaded adhkar and Qur'an text) are
kept in the app's private storage on the TV. Uninstalling MuslimEcho deletes them.

If **Android backup** is turned on for your Google account, Android may include a copy of the MuslimEcho
settings in your device backup (stored by Google, encrypted, under your account) so they come back
after a reinstall. Turn it off in the TV's Settings → System → Backup.

## When MuslimEcho connects to the internet

Prayer times, the adhan and the bundled hadith work without internet. The features below fetch
public content when you use them. These requests contain no identifiers or account data (the
weather request includes your city's approximate location), and like any internet request they
reveal your TV's IP address to the service that answers them.

| Feature | Service | What is requested |
|---|---|---|
| "Detect my location" (setup and Settings → Location) | get.geojs.io, fallback ipapi.co | Your approximate city from the IP address. Only when you press the button. |
| City search | geocoding-api.open-meteo.com, photon.komoot.io | The city name you type |
| Ayah of the Day, Qur'an text and verse timing | api.quran.com | A random verse / the surah you open |
| Qur'an recitation | download.quranicaudio.com, mp3quran.net | The audio of the surah you play |
| Adhkar (morning & evening) | www.hisnmuslim.com | The adhkar text and recitation audio |
| Mosque of the Day | commons.wikimedia.org, upload.wikimedia.org | The day's photo and its credit |
| Screensaver weather (can be turned off in Settings → Screensaver) | api.open-meteo.com | Today's forecast for your city's coordinates, rounded to about 10 km |

Each service has its own privacy policy. MuslimEcho sends them no identifiers, cookies or account data.

## Optional support tips

The Support tab lets you "buy us a coffee" through Google Play. The payment is handled entirely by
Google Play under Google's terms and privacy policy (https://policies.google.com/privacy). MuslimEcho
only learns whether the purchase went through; it never sees your name, email or payment details,
and its own code doesn't store or send any purchase information. The Google Play Billing Library
included in the app exchanges the purchase with Google Play, which is why the Play Store's Data
safety section lists "Purchase history". Tips are optional and unlock nothing.

## Permissions

| Permission | Why |
|---|---|
| Internet | The content listed above |
| Alarms & reminders (exact alarms) | Play the adhan at the exact prayer time |
| Run at startup | Re-arm the adhan schedule after the TV restarts |
| Foreground service (media playback), wake lock | Play the adhan while another app is open or the screen is dimmed |
| Notifications | Show the playing adhan with a Stop button |
| Display over other apps (optional) | Show the small adhan card with a Stop button on top of other apps |
| Google Play billing | The optional support tips |

MuslimEcho doesn't use the microphone, camera, contacts, precise location or storage.

## Children

MuslimEcho is suitable for all ages and collects no data from anyone, including children.

## Changes

If this policy changes, the new version will be published at the same address with a new date.

## Contact

Questions or requests: write to the developer at the email address shown on MuslimEcho's Google Play
listing (under "App support").

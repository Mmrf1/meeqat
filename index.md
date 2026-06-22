# Privacy Policy — Meeqat

**Effective date:** 22 June 2026

**App:** Meeqat (Android)

**Package ID:** `com.artvsp.hudur`

**Developer:** ArtVSP

**Contact:** maruf.artvsp@gmail.com

This policy explains what Meeqat collects, what it does with that information, and what your rights are. It is written in plain language. If you only have time to read one sentence, read this: **Meeqat keeps almost all of your data on your device and does not run any analytics or tracking of its own.**

---

## 1. Information Meeqat collects

### 1.1 Approximate location (with your permission)
When you grant the location permission, Meeqat reads your device's approximate location (latitude and longitude) so it can calculate accurate prayer times for where you are. We use this only to:

- compute local prayer times and qibla direction,
- request a monthly prayer-time table from the AlAdhan API (see section 2 below).

The coordinates are stored on your device only. They are not transmitted to any server we operate, because we don't operate any server. You can revoke the location permission at any time from your Android settings; if you do, Meeqat will continue to work using the last known location until you change it manually.

### 1.2 Settings and preferences you choose
Your settings — chosen calculation method, madhhab, theme, reminders, custom calendar markers, adhkar counts — are saved locally on your device using on-device storage (MMKV + SQLite). They never leave your device.

### 1.3 Purchase entitlements
If you purchase the "Remove Ads" one-time unlock or send a tip, the transaction is processed entirely by **Google Play Billing**. Meeqat receives only a yes/no signal indicating whether you own "Remove Ads" — no payment details, name, address, or billing identifiers reach the app.

### 1.4 What Meeqat does NOT collect
- No analytics events, no crash reporting, no usage telemetry.
- No advertising ID is used by Meeqat itself.
- No account creation, no login, no user identifier.
- No address book, photos, microphone, camera, calendar events, or files.
- No background location tracking.

---

## 2. Third-party services

### 2.1 AlAdhan API (prayer time data)
Meeqat fetches monthly prayer-time tables from the public AlAdhan service at `api.aladhan.com`. Each request includes the latitude and longitude needed for the calculation and the month being requested. No identifying information about you or your device is included in these requests beyond standard HTTP metadata (IP address, user agent — set automatically by the operating system).

AlAdhan is operated independently of Meeqat. Their privacy policy: https://aladhan.com/privacy-policy.

### 2.2 Google AdMob (banner advertising)
Unless you purchase the "Remove Ads" upgrade, Meeqat shows a banner advertisement at the bottom of the screen on most pages. The ad is served by **Google AdMob**.

AdMob may collect device-level information (Advertising ID, IP address, coarse location, ad interactions) to serve and measure ads. By default, Meeqat configures AdMob to request **non-personalized ads** so the information AdMob uses is minimized. You can also reset or limit your Advertising ID in your Android settings under *Privacy → Ads*.

Google's policies covering AdMob: https://policies.google.com/technologies/ads.

### 2.3 Google Play Billing (in-app purchases)
"Remove Ads" and the optional tips are processed by **Google Play Billing**. Google's policies and your purchase history are governed by the Play Store. Meeqat does not receive your payment details.

Google Play's policies: https://policies.google.com/.

---

## 3. Permissions Meeqat requests

| Permission | Why |
|---|---|
| `INTERNET` | Fetch prayer-time tables from AlAdhan; load banner ads (unless you've bought Remove Ads) |
| `ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION` | Calculate prayer times and qibla direction for your location |
| `POST_NOTIFICATIONS` | Show reminder notifications you've enabled |
| `WAKE_LOCK`, `SCHEDULE_EXACT_ALARM`, `USE_EXACT_ALARM`, `USE_FULL_SCREEN_INTENT` | Trigger reminders at the exact prayer time even when the device is idle |
| `RECEIVE_BOOT_COMPLETED` | Re-schedule pending reminders after your device restarts |
| `FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_MEDIA_PLAYBACK` | Play the adhan when a prayer-time alarm fires |
| `VIBRATE` | Vibrate during reminder notifications |
| `com.android.vending.BILLING` | Communicate with Google Play Billing for purchases |

You can revoke any optional permission at any time from your device's Settings → Apps → Meeqat → Permissions.

---

## 4. Data sharing

We do not sell, rent, or share your information with third parties beyond what is described in section 2 — and even there, the only "sharing" is the lat/lng you actively send to the AlAdhan API when fetching prayer times, and the device-level data Google AdMob collects when ads are shown.

---

## 5. Data retention and deletion

All data Meeqat creates lives on your device. To delete it, simply uninstall the app — Android will remove all locally stored settings, cached prayer times, and event markers. There is no separate "delete my data" request to file with us because we hold no copy of your data on any server.

---

## 6. Children

Meeqat is not directed at children under 13. We do not knowingly collect personal information from children. The app contains no behavioral profiling and is configured for general-audience (`MaxAdContentRating.G`) advertising.

---

## 7. International users (GDPR / UK GDPR / CCPA)

If you are in the European Economic Area, the United Kingdom, or California, the same disclosure applies: Meeqat itself stores your data locally and processes no personal information on any backend. The only personal data that leaves your device is what you send to AlAdhan (lat/lng) and what Google AdMob processes for ad serving (subject to Google's terms). Under GDPR/CCPA you have rights of access, correction, deletion, and objection — for data Meeqat holds locally, these rights are exercised directly through the app's settings and by uninstalling. For data Google or AlAdhan hold, contact them via their respective policies linked above.

---

## 8. Security

Data stored on your device is protected by Android's standard application sandboxing — other apps cannot read Meeqat's storage. Network requests to AlAdhan and AdMob use HTTPS.

---

## 9. Changes to this policy

If we change this policy, we'll update the "Effective date" at the top and publish the new version at the URL where you found this document. Material changes will be highlighted in the app's release notes.

---

## 10. Contact

If you have questions, concerns, or requests regarding this policy or your data, contact us at:

maruf.artvsp@gmail.com

---

*This document is the privacy policy referenced from the Meeqat app and from its Google Play Store listing.*

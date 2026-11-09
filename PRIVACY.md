# Privacy Policy

**Effective: 8 November 2026**

Munadi is a simple, offline prayer-times app that began in Qatar.
This policy explains what the app does with data. It covers the GitHub APK build.

## Summary

- No accounts, ads, analytics, or trackers.
- Prayer times and settings stay on your device.
- Approximate location is used for the Qibla compass, place name, and prayer-time area.
- We do not operate a server that receives your data.

## Data the app uses

### Approximate location

Munadi requests **approximate location only**; precise location is not
requested. It is used to calculate the Qibla direction and distance, show a
place name, and suggest the nearest prayer-time area. The last approximate
location and place are cached in the app's private storage so the Qibla screen
can open quickly.

Place names are matched on the device from a built-in list. When location is
already allowed, the app may check it at launch to suggest an area. Your
location is not sent anywhere.

On first launch, Munadi also reads which country your mobile network and SIM
card belong to, without any permission, only to open the right country in the
city list. This stays on your device. Location may suggest the nearest listed
city in any region, and never switches it for you.

### Settings and timetable

Theme, color, language, prayer-time city, Asr choice, Hijri date adjustment,
iqamah adjustments, notification preferences, and sound choices are stored
locally on your device.

In Qatar, prayer times follow the Qatar Calendar House timetable, stored inside
the app, using the Doha table by default. You can choose Abu Samra, Dukhan or
Al Shamal in Settings, and the app may suggest one when location is available.

In other regions (currently Saudi Arabia, the United Arab Emirates, Kuwait, Oman, and Pakistan), prayer times are calculated on your
device from the coordinates of the city you choose in Settings, using an
open-source calculation library. Nothing about the calculation leaves your
device.

You can export your settings to a file you choose and import it later. The file
is saved where you put it; Munadi does not upload it.

### Network access

If update checks are enabled, the app requests the latest release information
from GitHub. GitHub receives standard network information such as your IP
address and the app's user agent, subject to GitHub's privacy policy. Munadi
does not send analytics, identifiers, or usage data.

The Google Play build does not include the in-app updater and has a separate
policy.

### Permissions

Depending on the features you use, the app may request:

- Approximate location, for Qibla and the prayer-time area
- Notifications, for adhan and update alerts
- Exact alarms, to keep prayer reminders on time
- Battery optimisation exemption, so alarms are not delayed
- Internet, for optional update checks
- Install unknown apps, for in-app updates
- Foreground media playback and vibration, for the adhan

You can decline optional permissions and still use the prayer timetable.

## Sharing and retention

We do not sell or share your data. Munadi has no accounts and no analytics
SDK. Local data remains until you clear the app's storage or uninstall it.

## Children

Munadi is a general-audience prayer app and does not knowingly collect
personal information from children.

## Changes

This policy may be updated in this repository. The effective date above will
change when it does.

## Contact

Email munadi.prayer@gmail.com, or open an issue at
https://github.com/hackills/munadi-apks/issues.

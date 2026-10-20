# Roam Control 0.9.9

Build 105, released 20 October 2026.

## Highlights

Roam Control 0.9.9 introduces ten interface languages, improved map and route handling, custom Walking/Cycling/Driving speeds, connection recovery refinements and interface improvements.

- **Languages:** English, Hebrew, Arabic, Simplified Chinese, Traditional Chinese, Japanese, Vietnamese, French, German and Spanish, plus System Default. Language changes apply immediately. Arabic and Hebrew support right-to-left layouts.
- **Maps and routes:** improved map controls, coordinate compatibility and handling of routes and route errors.
- **Custom movement speeds:** adjustable movement settings, refined driving behaviour and route estimates, and a live walking-speed display.
- **Connection recovery:** improved detection and recovery while iOS permits execution. Automatic restart cannot be guaranteed while the app is suspended or terminated.
- **Interface:** improved language picker, recovery presentation and localisation of app messages.

For detailed changes, see [CHANGELOG.md](../CHANGELOG.md).

## Before installing

- Requires **iOS 27 or newer** and an iPhone with **Developer Mode** enabled.
- **LocalDevVPN is still required** for local pairing connectivity.
- Distributed as an **unsigned IPA**, to be signed through SideStore or a compatible installation method. Free Apple accounts remain subject to signing and refresh restrictions.
- For LiveContainer installation, enable **Fix Local Notifications** before the app's first launch, as documented in the [installation guide](Installation.md).
- Intended for development, quality assurance and responsible personal testing on an iPhone you own or control.

> [!IMPORTANT]
> **Upgrading directly from Roam Control 0.9.4 or earlier? Create a backup before installing 0.9.9.**
>
> Versions from 0.9.5 use the newer `com.roamcontrol` app identifier. Your 0.9.4 app data will not automatically transfer to that app container.
>
> In the older app, open **Settings > Backup & Restore** and create a backup to preserve favourites, history and supported settings. Restore it during the migration flow after installing the newer app.
>
> Pairing data is not included in app backups, so this iPhone must be paired again.
>
> See the [Migration & SideStore FAQ](Migration095.md).

## Download

Download `RoamControl-0.9.9-Build105.ipa` from the [0.9.9 GitHub Release](https://github.com/seanhowarthdev/Roam-Control/releases/tag/v0.9.9).

**SHA-256**

`211f1057c70292da468226b39808d8777549c02923c14afc504d9e1d2daba86e`

## Continuing features

Fixed locations, Walking/Driving/Cycling routes, manual routes, Joystick movement, GPX import/export, favourites, history, pairing, connection diagnostics and Stop & Restore remain available.

## Support and safety

Read [Installation](Installation.md), [Privacy](Privacy.md) and [Responsible Use](ResponsibleUse.md). Report bugs through GitHub Issues and security concerns through a private security advisory.

Location simulation can affect other apps. Restore the real location before using navigation, emergency, safety or location-sharing features.

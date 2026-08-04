# VerseDay — releases & issues

Downloads and bug reports for **VerseDay**, a macOS focus and time-tracking app.

This repository intentionally contains **no source code**. It exists to host:

- **Release binaries** — the signed, notarized `.dmg` downloads
- **`latest.json`** — the update manifest the app checks
- **Issues** — where to report a problem

## Reporting a problem

Open an issue and include the version and build details shown in
**VerseDay → Settings → About** (there is a **Copy** button). If the app failed
to start, its error screen has a **Copy details** button — paste that instead; it
identifies the exact build and where the failure occurred.

**If VerseDay won't open, please don't delete or reinstall it.** Reinstalling
will not fix a startup failure and it can permanently delete your data. Your
information is stored locally and is most likely recoverable — open an issue
first.

## Privacy

VerseDay stores everything locally on your Mac. Your tasks, notes, and calendar
data never leave the device.

**As of today, VerseDay makes no network requests at all.**

A future version will add an update check that fetches the static `latest.json`
in this repository. When it ships, that check will send no version, no platform,
no identifier, and no personal data. As with any web request, it will reach
GitHub with your IP address and User-Agent, which GitHub logs. This section will
be updated to say so in the present tense when that version is released.

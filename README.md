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

VerseDay checks this repository for a newer version shortly after it starts,
and whenever you press **Check** in Settings. That check sends no version, no
platform, no identifier and no personal data — it fetches a fixed file
(`latest.json`). As with any web request it reaches GitHub carrying your IP
address and User-Agent, which GitHub logs.

Updates are never installed without asking you, and VerseDay will not restart
while you are timing a focus session or on a break.

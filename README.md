# Rigo Studio for desktop

Release downloads for **Rigo Studio**, the free crop scouting and traceability
application from [Agririgo](https://agririgo.com).

This repository holds **release binaries only**. No source code is published here.

## Download

Get the right build for your machine from
**[agririgo.com/download](https://agririgo.com/download)**, which detects your
system for you, or pick one from the [latest release](../../releases/latest).

| File | For |
| --- | --- |
| `Rigo-Studio-<version>-arm64.dmg` | Mac with Apple silicon (M1 and later) |
| `Rigo-Studio-<version>-x64.dmg` | Mac with an Intel processor |
| `Rigo-Studio-Setup-<version>-x64.exe` | Windows 10 and 11, installs normally |
| `Rigo-Studio-Portable-<version>-x64.exe` | Windows, runs without installing |

`SHA256SUMS.txt` in each release lets you verify a download.

## Free, with no paid tier

Every feature is available to every account. There is nothing to buy and no
upgrade to find. Sign in with the same account as the website, or make one in
the app.

## These builds are not code signed yet

Agririgo is early and certificates for both platforms are still being arranged.
Until then your machine will warn you the first time you open the app. This is
expected, and here is how to get past it.

**macOS:** double-clicking will say the app "cannot be opened because the
developer cannot be verified". Right-click (or Control-click) the app in
Applications and choose **Open**, then **Open** again in the dialog. You only do
this once.

**Windows:** SmartScreen will show a blue "Windows protected your PC" screen.
Click **More info**, then **Run anyway**.

Verify the SHA-256 checksum against `SHA256SUMS.txt` if you want to be certain
the file you have is the file we published.

## What it does

Rigo Studio reads a drone or phone photograph of a field and tells you what is
wrong, where, and what to do about it, then carries that record through to the
buyer as a scannable crop passport. Built for African growing conditions, from
smallholder plots to commercial blocks.

It also connects the farm around the photo. You say, in plain words, how things
are wired: this pump waters Block 3, that solar array powers the pump, this
soil probe measures the field. From then on the data talks to itself: a dry
reading becomes "irrigate Block 3 with Pump P-02", with the forecast, the crop's
stage and the pump's power checked for you, and a what-if (do nothing, water
tomorrow, water in three days) before you commit. Your farm can also be
exported in open formats (FIWARE NGSI-LD and OGC SensorThings) for other
systems. These arrive in Rigo Studio on the web first, then in the next desktop
release.

## Support

[agririgo.com/contact](https://agririgo.com/contact)

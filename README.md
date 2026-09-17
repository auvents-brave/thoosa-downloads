# Thoosa — prototype builds

Thoôsa is a marine navigation app. It is native on Apple platforms; this
repository carries the **companion builds for the platforms the Apple app
cannot reach** — Windows, Android and Linux.

Take them from the [latest release](../../releases/latest). No source lives
here: the application is developed elsewhere, and only its packaged builds are
published here so that the download links on
[pitch-and-roll.com](https://pitch-and-roll.com) stay stable. The Windows builds
are compiled by this repository's own workflow, since they cannot be built on
the Mac that packages the others.

| Platform | File |
| --- | --- |
| Windows (x64) | `Thoosa-windows-x64.zip` |
| Windows (arm64) | `Thoosa-windows-arm64.zip` |
| Android (arm64) | `Thoosa-android.apk` |
| Linux (x64) | `Thoosa-linux-x64.tar.gz` |
| Linux (arm64) | `Thoosa-linux-arm64.tar.gz` |

## What "prototype" means

These builds are working proof, not a finished product. They are unsigned: on
Windows, SmartScreen will warn about an unknown publisher, and on Android you
will have to allow installation from an unknown source. Install them only if
you are content to take that on.

The Apple builds are not here. They ship through the App Store.

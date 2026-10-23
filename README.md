# Warpeer for Android and iPhone

Warpeer is a native SSH terminal for phones, built on the Ghostty renderer. This repository
publishes the Android app; Warpeer for iPhone is on the
[App Store](https://apps.apple.com/app/id6807693295). Source code is not published here.

- Website and guides: [warpeer.com](https://warpeer.com)
- Warpeer for Mac, an open-source terminal-only Warp fork:
  [imatrixme/warpeer.desktop](https://github.com/imatrixme/warpeer.desktop)

## Download for Android

Get the latest APK from [Releases](https://github.com/imatrixme/warpeer.mobile/releases/latest).
`Warpeer-android.apk` always points to the newest build.

- Requires Android 12 or later on a 64-bit ARM device.
- Free, with no account, analytics or advertising SDK.
- Not on Google Play yet. Android asks you to allow installing apps from your browser or file
  manager the first time.

Each release lists the APK's SHA-256 checksum and signing certificate fingerprint. Every Android
release is signed with the same key, so later versions install over earlier ones:

```
SHA-256: BB:9E:7E:7D:5D:91:6A:C6:57:B0:4A:AD:69:31:27:E5:AE:2A:36:26:2C:88:37:03:B6:9E:6B:E9:71:B0:A2:E7
```

Check a download with `apksigner verify --print-certs Warpeer-android.apk`.

## Status

The Android app is a preview. It does not list tmux or Herdr sessions, coding agents, git status
or live host metrics yet, and has no file previews, voice input or image attachments. See the
[Android guide](https://warpeer.com/docs/android/getting-started).

## Support

Report problems to [support@warpeer.com](mailto:support@warpeer.com), or open an issue here. Do
not report security vulnerabilities in public issues; email the same address instead.

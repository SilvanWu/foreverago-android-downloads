# Forever Ago Android Downloads

Android installation packages and versioned story-content downloads.
Source code is maintained separately and is not published in this repository.

## Latest APK

[Download Android r7a - Signature Compatibility](https://github.com/SilvanWu/foreverago-android-downloads/releases/download/android-r7a-20261118/ForeverAgo-Android-AutoDownload-20261118-r7a.apk)

- APK: 1,650,793,365 bytes (approximately 1.54 GiB).
- First-launch story download: approximately 3.93 GiB, in verified128 MiB parts.
- Android8.0 or newer; ARM64 phones and x86_64 emulators.
- Package: com.academic.foreverago.qa; version0.1.15/code15.
- SHA-256: 16c98e4887c05943facf012febd079f727312a9b922a6f742a72831d1b80e29b.
- Non-development build using the existing test signing identity. This is a
  test distribution, not a Play Store production release.

r7a keeps the same game payloads, version and signing identity as r7, but
includes explicit v1/JAR certificate files in addition to v2 and v3 signatures.
This follows a phone reporting missing certificates for r7. Local and cloud
signature checks and emulator upgrade passed; that phone's result is pending.

Install the APK from the latest Android release. Versions marked
**Auto Download** retrieve matching story content on first launch.
The app displays the download size and asks before using mobile data.
After the initial download, the matching content works offline.

Story releases contain content-addressed parts and a SHA-256 catalog.
Do not mix parts from different releases. No GitHub login or USB debugging
is required for downloading public content.

The older r6 APK does not support automatic resource downloads.
Physical-device compatibility and full-story completion are not yet certified.
The DINER3 video-rendering issue remains under investigation.

If the initial download fails, check that the device can reach GitHub and its
release-assets CDN, then retry. Completed parts are retained; an incomplete
part restarts. Resource verification on startup can take some time.

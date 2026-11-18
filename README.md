# Forever Ago Android Downloads

Android installation packages and versioned story-content downloads.
Source code is maintained separately and is not published in this repository.

## Latest APK

[Download Android r7 - Auto Download](https://github.com/SilvanWu/foreverago-android-downloads/releases/download/android-r7-20261118/ForeverAgo-Android-AutoDownload-20261118-r7.apk)

- APK: 1,650,781,918 bytes (approximately 1.54 GiB).
- First-launch story download: approximately 3.93 GiB, in verified128 MiB parts.
- Android8.0 or newer; ARM64 phones and x86_64 emulators.
- Package: com.academic.foreverago.qa; version0.1.15/code15.
- SHA-256: 2754c0e34b49d1150d933afa0dddfd3808e6245ad371acb38bf568f2d64692d4.
- Non-development build using the existing test signing identity. This is a
  test distribution, not a Play Store production release.

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

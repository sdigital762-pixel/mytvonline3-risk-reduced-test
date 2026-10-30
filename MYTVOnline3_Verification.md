# MYTVOnline3 Enhanced Build Verification

- File: `MYTVOnline3.apk`
- Package: `tv.formuler.mol3.real`
- App label: `MYTVOnline3`
- Version: `12.1.33-enhanced-2` (`120134`)
- Minimum Android: Android 7.0 / API 24
- Target Android API: 29
- Native architecture: 32-bit ARM (`armeabi-v7a`)
- SHA-256: `E4595BC86DFE3D78DAE7550D9DCD80B2853DD0C6CC951BACEF9CDBB0A2E74804`
- Signing certificate: `CN=AmsterdamClick MYTVOnline3, O=AmsterdamClick, C=MA`
- Certificate SHA-256: `AB94AFE1CB579BD9A8B5C8CA605680323100F7415B9CAD4AFC49FE3BA72546EC`

## Completed checks

- APK Signature Scheme v2 and v3 verification passed.
- Android ZIP alignment verification passed.
- Microsoft Defender custom scan found no threats.
- The final `classes3.dex` matches the intended patched build.
- The original `classes.dex`, `classes2.dex`, and all nine native libraries remain byte-for-byte unchanged.

## Changes in this build

- Larger TV-focused menu, titles, live rows, and focus indicators.
- Updated navy and cyan interface styling.
- Playback-after-rebuffer threshold changed from 10 ms to 1,000 ms to reduce immediate stop/start loops.
- Default recovery attempts changed from three to five.
- The app no longer installs a global trust-all HTTPS verifier; standard Android certificate validation is used.

## Limits

A local malware scan is not proof that proprietary compiled code is malware-free. Test with non-sensitive credentials first. This APK supports Android 7 or newer on compatible devices that can run 32-bit ARM applications and may depend on Formuler services.

No application can guarantee zero buffering. Stream provider capacity, bitrate, packet loss, Wi-Fi quality, ISP routing, VPN overhead, and device performance remain outside the application.

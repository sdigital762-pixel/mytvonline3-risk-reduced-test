# MYTVOnline3 Risk-Reduced Test Download

This repository contains the locally rebuilt and signed `MYTVOnline3-risk-reduced-1.apk` for isolated compatibility testing.

## Download

- Branded page: <https://download.amsterdambyclick.com/>
- Direct AmsterdamClick test link: <https://download.amsterdambyclick.com/app/>
- Release asset: [`MYTVOnline3-risk-reduced-1.apk`](https://github.com/sdigital762-pixel/mytvonline3-risk-reduced-test/releases/download/v12.1.33-risk-reduced-1/MYTVOnline3-risk-reduced-1.apk)
- Package: `tv.formuler.mol3.real`
- Version: `12.1.33-risk-reduced-1` (`120134`)
- SHA-256: `14B10F48FDA9E1B2D29B5A98E064BAF84E9647B698A9BDDF5E21C096F0772611`
- Minimum Android: Android 7.0 / API 24
- Native architecture: 32-bit ARM (`armeabi-v7a`) only

## Installation warning

Uninstall any existing `tv.formuler.mol3.real` installation first. This test build uses a new signing certificate, so Android cannot install it over a differently signed version.

It is intended for compatible Formuler-style hardware. It may not work on 64-bit-only or generic Android/TV devices because the supplied proprietary native libraries are 32-bit only and the app expects Formuler services.

## Safety and buffering limits

Microsoft Defender detected no known threat in the original, decoded, or final signed APK. The final APK passed Android v2/v3 signature verification, alignment verification, and content-hash comparison. See [`MYTVOnline3_APK_Safety_Report.md`](https://github.com/sdigital762-pixel/mytvonline3-risk-reduced-test/releases/download/v12.1.33-risk-reduced-1/MYTVOnline3_APK_Safety_Report.md) for details.

This does **not** prove the APK is malware-free. Its original proprietary DEX and native-library code remains. Test with non-sensitive credentials on an isolated compatible device.

No application can guarantee zero buffering. Provider/CDN capacity, stream bitrate, packet loss, Wi-Fi quality, ISP routing, VPN overhead, and device performance remain outside the application.


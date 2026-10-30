# MYTVOnline3 Enhanced Test Download

This repository hosts the locally rebuilt and signed `MYTVOnline3.apk` for isolated compatibility testing.

## Download

- Branded page: <https://install.amsterdambyclick.com/>
- Direct APK: <https://install.amsterdambyclick.com/MYTVOnline3.apk>
- Automatic download page: <https://install.amsterdambyclick.com/app/>
- Package: `tv.formuler.mol3.real`
- Version: `12.1.33-enhanced-2` (`120134`)
- SHA-256: `E4595BC86DFE3D78DAE7550D9DCD80B2853DD0C6CC951BACEF9CDBB0A2E74804`
- Minimum Android: Android 7.0 / API 24
- Native architecture: 32-bit ARM (`armeabi-v7a`) only

## Installation warning

Uninstall any existing `tv.formuler.mol3.real` installation first. This test build uses a new signing certificate, so Android cannot install it over a differently signed version.

It is intended for compatible Formuler-style hardware. It may not work on 64-bit-only or generic Android/TV devices because the supplied proprietary native libraries are 32-bit only and the app expects Formuler services.

## Safety and buffering limits

Microsoft Defender detected no known threat in the final signed APK. The final APK passed Android v2/v3 signature verification, alignment verification, and content-hash comparison. See the [verification report](https://install.amsterdambyclick.com/MYTVOnline3_Verification.md) for details.

This does **not** prove the APK is malware-free. Its original proprietary DEX and native-library code remains. Test with non-sensitive credentials on an isolated compatible device.

No application can guarantee zero buffering. Provider/CDN capacity, stream bitrate, packet loss, Wi-Fi quality, ISP routing, VPN overhead, and device performance remain outside the application.


# XiangqiAtlas · 象棋搭子Atlas

Official Android APK downloads published by Caractiv Tech.

- [Google Play](https://play.google.com/store/apps/details?id=com.caractiv.xiangqiatlas)
- [Official website](https://xiangqiatlas.caractiv.com/)
- [Latest release and downloads](https://github.com/caractiv/xiangqiatlas-app-release/releases/latest)
- [Privacy policy](https://xiangqiatlas.caractiv.com/privacy/) · [Terms and EULA](https://xiangqiatlas.caractiv.com/terms/)

## Install / 安装

Open **Releases** and download the APK that matches your device:

| APK | Device |
| --- | --- |
| `arm64-v8a` | Most current Android phones / 大多数现代 Android 手机 |
| `armeabi-v7a` | Older 32-bit ARM devices / 较早的 32 位 ARM 设备 |
| `x86_64` | Compatible Intel/AMD Android devices and emulators / 兼容的 x86_64 设备与模拟器 |

Android 7.0 or later is required. Use Google Play to update a Google Play installation; use these releases to update a standalone APK installation.

Download `SHA256SUMS.txt` from the same release to verify the file. APK download filenames omit the parentheses used in our internal build filenames; the signed APK bytes are identical.

## Open-source engine / 开源引擎

The app contains Fairy-Stockfish as a separate executable, licensed under GNU GPL v3, with our published NNUE memory patch. Every release includes the corresponding upstream source archive, patch, build script and licence in `fairy-stockfish-6d9d0f57-xiangqiatlas-source.zip`. The source package is an explicit release attachment, separate from GitHub's automatically generated repository archives.

The official Fairy-Stockfish xiangqi neural network is CC0 data. Source revision, patch checksum and build instructions are included in the source package.

This repository distributes app releases and engine source materials. The XiangqiAtlas application source is maintained separately; app use is governed by the linked Terms and EULA.

Support / 联系我们: contactus@caractiv.com

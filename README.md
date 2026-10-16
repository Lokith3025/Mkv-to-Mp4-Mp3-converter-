# MKV Converter
A fast, lightweight Android application designed to convert MKV and AVI media files directly to MP4 video or MP3 audio on your device. Powered by native Android Media3 Transformer hardware acceleration for quick, efficient processing without sending any data to external servers.
---
## Features
- **Hardware accelerated transcoding:** Utilizes native device decoders and encoders via Media3 for swift processing.
- **MKV to MP4 conversion:** Converts high-definition video containers into widely compatible MP4 formats.
- **Audio extraction:** Pulls audio tracks directly from videos and saves them as MP3.
- **Batch processing:** Select multiple media files at once and process them in sequence.
- **Completely offline:** No video or audio data ever leaves your device; processing happens locally.
- **Direct save to gallery:** Export converted files straight to your device's media storage.
---
## Download
Get the latest pre-compiled Android package:
- Head to the [Releases](../../releases) tab.
- Download the latest `app-release.apk`.
- Open the downloaded file on your Android device to install.
---
## Technical Specifications

| Feature | Detail |
| :--- | :--- |
| Platform | Android |
| Minimum Android Version | Android 7.0 (API 24) |
| Architecture Support | arm64-v8a |
| Core Transcoder Engine | AndroidX Media3 Transformer 1.5.1 |
| Container Formats | Input: MKV, AVI / Output: MP4, MP3 |

---
## Permissions Used
- `READ_MEDIA_VIDEO` / `READ_MEDIA_AUDIO`: Required to select and process source files from local storage.
- `INTERNET` & `ACCESS_NETWORK_STATE`: Used solely for loading Google AdMob ad units to support free development.
---
## License
This distribution contains pre-built binaries. All rights reserved by the developer.

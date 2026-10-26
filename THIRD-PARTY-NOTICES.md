# Third-party notices

Hypt's own code is MIT licensed (see `LICENSE`). Release downloads also contain:

| Component | Used for | License |
|---|---|---|
| [FFmpeg](https://ffmpeg.org) (Windows build by [BtbN/FFmpeg-Builds](https://github.com/BtbN/FFmpeg-Builds), `gpl-shared` variant) | Screen capture (ddagrab), GPU encoding (NVENC/AMF/QSV), saving, exports | GPL-3.0 build (`ffmpeg/LICENSE.txt`). Hypt runs it as a separate program; source: https://github.com/FFmpeg/FFmpeg |
| [NAudio](https://github.com/naudio/NAudio) | WASAPI speaker loopback + microphone capture | MIT |
| [QRCoder](https://github.com/codebude/QRCoder) | QR codes for phone sharing | MIT |
| [Vosk](https://github.com/alphacep/vosk-api) | Offline voice commands (speech recognition) | Apache-2.0 |
| [vosk-model-small-en-us-0.15](https://alphacephei.com/vosk/models) | English speech model shipped in `voice/model` | Apache-2.0 |
| [System.Speech](https://www.nuget.org/packages/System.Speech) | Fallback voice engine (the Windows speech engine) | MIT |
| [.NET](https://github.com/dotnet/runtime) / WPF | Runtime and UI | MIT |
| Segoe Fluent Icons / Segoe UI Variable | Icons and type (part of Windows, not redistributed) | Microsoft |

FFmpeg is GPL software. If you redistribute Hypt together with FFmpeg you must also make FFmpeg's
corresponding source available — the links above point to it.

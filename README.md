# libmpv-audio-only

Windows builds of `libmpv-2.dll` stripped down for audio playback.

## Details
- Video output, video decoders, and graphics APIs disabled
- TLS support via Windows SChannel (no external OpenSSL dependency)
- Supported formats: MP3, AAC, FLAC, OGG, Opus, WAV, M4A, MKV audio
- Audio filters: volume, equalizer, atempo, dynaudnorm, afftdn

Prebuilt binaries are available in [Releases](https://github.com/M-Rajabi-dev/libmpv-audio-only/releases).

## License
MIT

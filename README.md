# Marker releases

Windows downloads for **Marker**, a pointer-only video review tool: timecoded notes, exported as markdown. Each release has:

- `Marker-Setup-<version>.exe`: the installer. Installs for your account only (no administrator password), adds a Start menu entry, and keeps itself up to date (Marker checks this page when it starts; Settings turns that off).
- `Marker-<version>-win64.zip`: the portable build. Unzip anywhere and run `Marker\Marker.exe`.
- `SHA256SUMS.txt`: hashes of both.

Both files are signed by OK Studio Inc. Windows SmartScreen may still show "Windows protected your PC" while a new release earns its reputation: click "More info", then "Run anyway".

Marker runs `ffmpeg` and `ffprobe` as separate programs; the copies in the `ffmpeg` folder are a GPL build from [BtbN/FFmpeg-Builds](https://github.com/BtbN/FFmpeg-Builds). `THIRD_PARTY.txt` in the installed folder records the exact version and licences. Marker itself is MIT licensed.

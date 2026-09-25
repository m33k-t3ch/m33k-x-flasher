# Firmware staging

Do not place personal development binaries here.

The public flasher will use two release-safe merged images:

- `watch/m33k-x-watch-merged.bin` — LilyGO T-Watch Ultra / ESP32-S3
- `c5/m33k-x-c5-merged.bin` — Seeed XIAO ESP32-C5

Before enabling the installer:

1. Build both devices from sanitized release source.
2. Confirm no personal credentials, Wi-Fi passwords, API keys, tokens, or development-only secrets are embedded.
3. Replace the current shared development Watch <-> C5 authentication mechanism with device-specific enrollment/pairing.
4. Produce merged binaries suitable for ESP Web Tools.
5. Flash both devices from the browser and run the hardware test checklist.
6. Only then rename `manifest.template.json` to the active release manifest and enable the installer button.

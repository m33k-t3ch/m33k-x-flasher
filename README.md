# M33K X Web Flasher

Private staging repository for the browser-based M33K X installer.

## Targets

- **M33K X Watch** — LilyGO T-Watch Ultra (ESP32-S3)
- **M33K X C5** — Seeed XIAO ESP32-C5 companion

The final installer will use ESP Web Tools so the same page can detect the connected chip family and choose the matching firmware.

## Current status

The web page structure is in `docs/`, but installation is intentionally disabled until release-safe Watch and C5 binaries exist.

The current private development firmware must **not** be published as-is because Watch <-> C5 development authentication uses a local secret excluded from Git. The public release should use device-specific first-time enrollment instead.

## GitHub Pages

When ready for browser testing, configure GitHub Pages to deploy from:

- Branch: `main`
- Folder: `/docs`

Keep this repository private while the flasher is under development. Before making it public, run the firmware privacy/security checks and browser-flash test on both devices.

# M33K X Web Flasher

<p align="center">
  <img src="docs/assets/flasher1.png" alt="M33K X cyberpunk artwork" width="900">
</p>

M33K X is an experimental ESP32 wearable security and wireless research project built around the **LilyGO T-Watch Ultra** and a **Seeed XIAO ESP32-C5** companion.

> **Experimental learning project:** M33K X is being built as a hands-on way to explore ESP32 development, wireless technologies, embedded systems, security research, and custom hardware/software integration. Features may change as testing and development continue.

This repository hosts the browser-based Web Flasher for installing M33K X firmware.

## Features

- Browser-based firmware installation with ESP Web Tools
- Separate installers for the M33K X Watch and XIAO ESP32-C5 companion
- ESP32-S3 Watch + ESP32-C5 companion workflow
- Beta firmware testing on real hardware
- Custom M33K X interface and artwork
- Ongoing Wi-Fi, BLE, GPS, wardriving, NFC, LoRa/radio, and device-integration development

## Project status

- **M33K X Watch** — Beta
- **M33K X C5 companion** — Beta
- **Web Flasher** — Working
- **NFC** — In progress
- **LoRa / Radio** — In progress
- **Phone / dashboard integration** — Planned

## Supported devices

- **M33K X Watch** — LilyGO T-Watch Ultra (ESP32-S3)
- **M33K X C5** — Seeed XIAO ESP32-C5 companion

The installer uses ESP Web Tools so firmware can be flashed directly from a supported desktop browser.

## Install

1. Connect the device with a USB data cable.
2. Open the M33K X Web Flasher.
3. Select the matching installer for the Watch or C5.
4. Complete the browser flashing process.
5. After both devices are flashed, power them near each other for first-time pairing.

## Firmware status

Current firmware is a beta release and is being tested on real hardware before a stable release is announced.

## License

The M33K X source code is licensed under the **GNU General Public License v3.0 (GPLv3)**.

M33K T3CH artwork, character designs, logos, graphics, icons, visual assets, and branding are **All Rights Reserved** and are not included in the GPLv3 license for the source code.

See [LICENSE.md](LICENSE.md) for the project licensing terms and [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) for dependency notices.

## GitHub Pages

This repository is designed to be served from:

- Branch: `main`
- Folder: `/docs`

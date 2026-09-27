# M33K X Web Flasher

<p align="center">
  <img src="docs/assets/pose8.png" alt="M33K X cyberpunk artwork" width="900">
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


## Tools and features

The current M33K X Watch firmware includes:

- **Wi-Fi Scanner** — nearby 2.4 GHz networks from the Watch plus C5-assisted 5 GHz results, network details, and a live channel graph.
- **BLE Scanner** — nearby BLE advertisements with signal and device details.
- **Recon Dashboard** — combined Wi-Fi, BLE, channel, and GPS summaries.
  - **Pulse** — visualizes newly observed, lost, and changing signals.
  - **Radar** — radar-style visualization of wireless observations.
  - **Signal Hunter** — target-oriented Wi-Fi/BLE signal-strength tracking.
  - **Watch Mode** — creates a local wireless baseline and watches for changes between sweeps.
- **Wardrive** — repeated Wi-Fi/BLE collection with GPS data and C5-assisted 5 GHz observations; sessions can be stored locally on microSD.
- **GPS / GNSS** — satellites, coordinates, altitude, speed, HDOP, course, and receiver status.
- **SD Logs** — view locally stored wardrive files on the watch.
- **Settings** — timezone, 12/24-hour clock, Wi-Fi connection/persistence, and device configuration.
- **Radio / LoRa** — experimental receive/listen and packet-monitoring controls; still in active development.
- **NFC** — interface is present, but the feature remains in progress and is not considered reliable in the public beta.
- **Phone / Web Dashboard** — planned / in progress and not enabled in the current public beta.


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

For updates, choose **not to erase** when prompted if you want to preserve saved Wi-Fi settings and the Watch↔C5 enrollment key.

## Firmware status

Current firmware is a beta release and is being tested on real hardware before a stable release is announced.

## License

The M33K X firmware source code is licensed under the **GNU General Public License v3.0 (GPLv3)**. The corresponding public source snapshot is available at https://github.com/m33k-t3ch/m33k-x-source.

M33K T3CH artwork, character designs, logos, graphics, icons, visual assets, and branding are **All Rights Reserved** and are not included in the GPLv3 license for the source code.

See [LICENSE.md](LICENSE.md) for the project licensing terms and [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) for dependency notices.

## Links

- Web Flasher: https://m33k-t3ch.github.io/m33k-x-flasher/
- Flasher repository: https://github.com/m33k-t3ch/m33k-x-flasher
- Public GPLv3 source: https://github.com/m33k-t3ch/m33k-x-source

## GitHub Pages

This repository is designed to be served from:

- Branch: `main`
- Folder: `/docs`

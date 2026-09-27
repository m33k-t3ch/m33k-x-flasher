# Third-Party Notices

M33K X uses third-party open-source libraries and vendor components. Those components remain subject to their own licenses and copyright notices.

## Firmware dependencies

| Component | License |
| --- | --- |
| LVGL | MIT |
| RadioLib | MIT |
| XPowersLib | MIT |
| TinyGPSPlus | GNU LGPL v2.1 or later |
| NimBLE-Arduino | Apache License 2.0 |
| LilyGoLib | MIT |
| SensorLib | MIT |
| ST25R3916-fork | STMicroelectronics SLA0052 and applicable third-party terms |
| NFC-RFAL-fork | STMicroelectronics SLA0052 and applicable third-party terms |

The public source release should retain the license and copyright files supplied with vendored libraries and dependencies.

M33K T3CH artwork and branding are not covered by these third-party licenses and remain subject to the artwork terms in [LICENSE.md](LICENSE.md).


## NFC licensing note

The ST25R3916-fork and NFC-RFAL-fork packages include STMicroelectronics SLA0052 terms. Those terms include restrictions concerning software that would be subjected to certain open-source licensing obligations. Before a GPLv3 public firmware release, the NFC dependency path must be reviewed and resolved. A practical release option is to remove or replace those components from the GPL-covered public build unless compatibility is clearly established.

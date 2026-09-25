# M33K X Flasher security notes

This repository is intended to become the public distribution point for M33K X release firmware.

## Never publish

- personal Wi-Fi credentials
- API keys or access tokens
- private keys or signing secrets
- local development configuration
- a universal production Watch <-> C5 authentication secret
- personal filesystem paths or identifying development data

## Watch <-> C5 release requirement

The private development builds currently use a local shared key that is intentionally excluded from source control. Public release binaries must not embed that private development key.

The public release path should use first-time Watch <-> C5 enrollment so each paired device set establishes its own credentials.

## Release gate

The web install button stays disabled until both firmware images are sanitized, merged, hardware-tested, and verified to work through ESP Web Tools.

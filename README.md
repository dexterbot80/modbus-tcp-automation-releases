# Modbus TCP Automation — Firmware Releases

Public distribution repository for ESP32-P4 Modbus TCP Automation firmware.
Firmware downloads will be accessible without a GitHub account or access token.
Application source code is maintained separately in a private repository.

## Status

No OTA firmware release has been published yet. The existing v0.31.18 factory-only
firmware is not an OTA bootstrap release. Do not use this repository as evidence
that OTA is already supported on a controller.

## Planned release assets

- `esp32p4-relay.bin`: relay controller application, for either Master or Slave role.
- `esp32p4-thermostat.bin`: thermostat application, for either Master or Slave role.
- A manifest recording version, hardware/profile compatibility, OTA partition
  compatibility, image size, download location and SHA-256 digest.

Updates must preserve stored controller configuration. Initial migration to an
OTA partition layout requires a separately documented wired installation.

Only firmware intended for public distribution and release documentation belong
here. Do not upload credentials, device configuration backups, NVS dumps or
merged flash images containing configuration. Public binaries must be built
without deployment-specific credentials.

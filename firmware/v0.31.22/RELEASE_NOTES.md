# ESP32-P4 Automation v0.31.22

- Controller date/time replaces the former MQTT overview cell.
- Network and MQTT connection indicators share one overview cell.
- Clear clock with seconds, formatted date and controller timezone, visible on desktop, portrait tablets and phones.
- Explicit unsynchronized-time and stale-connection indicators; no substitution with browser time.
- Existing Modbus, MQTT, thermostat, authentication, OTA and configuration behavior retained.

On compatible v0.31.19/v0.31.20/v0.31.21 installations, update through Firmware Update; reload the web page after reboot. Configuration storage schemas are unchanged.

Relay and Thermostat binaries compiled with ESP32 Arduino core 3.3.12, ESP32P4 Dev Module, chip before v3.00, 4 MB flash, PSRAM disabled, default USB. First installation from an incompatible partition layout requires the USB migration installer.

Validation: both hardware profiles compile; 84 browser layout checks across 12 viewport sizes (320–1920 px), plus clock visibility, midnight/year rollover, unsynchronized time and lost/restored connection checks. No physical controller/tablet testing performed for this release.

Source commit: cd35a0bf18ceea73f3365b72368039c2b95814b5.

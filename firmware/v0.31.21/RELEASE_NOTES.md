# ESP32-P4 Automation v0.31.21

- Adaptive dashboard card grids for desktop, phones and tablets in portrait/landscape.
- Compact tablet header, settings navigation above forms, flexible controls and long labels.
- Scrollable data tables and viewport-constrained menus/dialogs.
- Larger touch targets, safe-area navigation and stable hover behavior.

Configuration storage and OTA profile selection are unchanged. On compatible v0.31.19/v0.31.20 installations, update through Firmware Update; reload the web page after reboot.

Relay and Thermostat binaries compiled with ESP32 Arduino core 3.3.12, ESP32P4 Dev Module, chip before v3.00, 4 MB flash, PSRAM disabled, default USB. First installation from an incompatible partition layout requires the USB migration installer.

Validation: both hardware profiles compile; 72 browser layout checks pass across 12 viewport sizes (320–1920 px). No physical controller/tablet testing performed for this release.

Source commit: ae069d4e6d77c02e06cd1dc310d382470f106205.

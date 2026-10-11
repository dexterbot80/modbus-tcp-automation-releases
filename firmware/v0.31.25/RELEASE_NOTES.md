# Smart control v0.31.25

- One continuous information bar with subtle dividers, shared background and compact spacing.
- Equal font size, weight and line height for values, including clock and uptime.
- Four columns on desktop and portrait tablets; continuous two-column layout on phones.
- Makita/Neco branding, controller behavior, configuration schemas and OTA compatibility retained.

Update compatible v0.31.19-v0.31.24 installations through Firmware Update, then reload the web page.

Relay and Thermostat compiled with Arduino-ESP32 3.3.12, ESP32P4 Dev Module, chip before v3.00, 4 MB flash, PSRAM disabled, default USB. First installation from an incompatible layout requires the USB migration installer.

Validation: both profiles compile; responsive browser checks at 12 viewport sizes. Physical controller testing was not performed for this release.

Source commit: 97bf071ff3ad13d7ed53de13a97220e1e07a501c.

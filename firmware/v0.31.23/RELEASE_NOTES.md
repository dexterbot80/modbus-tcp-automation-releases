# Smart control v0.31.23

- Makita logo with Smart control directly underneath, on dashboard and sign-in screen.
- Remove the Date & time label while retaining the controller clock, date and timezone.
- Footer: Designed by Neco Energies SRL, with https://neco.ro underneath. Visible on mobile too.
- Controller behavior, configuration schemas and OTA compatibility retained.

Update compatible v0.31.19-v0.31.22 installations through Firmware Update, then reload the web page.

Relay and Thermostat compiled with Arduino-ESP32 3.3.12, ESP32P4 Dev Module, chip before v3.00, 4 MB flash, PSRAM disabled, default USB. First installation from an incompatible layout requires the USB migration installer.

Validation: both profiles compile; responsive browser checks at 12 viewport sizes. Physical controller testing was not performed for this release.

Source commit: ab7d6c1fa7931fee3d0742b690b66dcdde1af4be.

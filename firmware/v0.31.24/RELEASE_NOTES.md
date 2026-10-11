# Smart control v0.31.24

- Makita logo with Proffesional Power. Smart Control underneath in both header and footer.
- Right-aligned Neco Energies SRL footer link opens https://neco.ro in a new tab.
- Rebuilt overview with four equal-size cards matching the dashboard styling: one row on desktop, symmetric 2x2 grid on tablet and phone.
- Controller behavior, configuration schemas and OTA compatibility retained.

Update compatible v0.31.19-v0.31.23 installations through Firmware Update, then reload the web page.

Relay and Thermostat compiled with Arduino-ESP32 3.3.12, ESP32P4 Dev Module, chip before v3.00, 4 MB flash, PSRAM disabled, default USB. First installation from an incompatible layout requires the USB migration installer.

Validation: both profiles compile; responsive browser checks at 12 viewport sizes. Physical controller testing was not performed for this release.

Source commit: 5fd22a99e4c2c850edb497ea5711ffe1072a5a56.

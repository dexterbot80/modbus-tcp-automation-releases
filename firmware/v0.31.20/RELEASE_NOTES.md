Firmware OTA v0.31.20 pentru ESP32-P4: Relay si Thermostat.

- Actualizare prin meniul administratorului Firmware Update, fara cont GitHub pe dispozitive.
- Profil selectat automat; configuratia NVS si rolul Master/Slave sunt pastrate.
- Aceleasi scheme de configuratie si partitii OTA ca v0.31.19.
- Verificare HTTPS, dimensiune, SHA-256 si identitate firmware.

Pentru v0.31.18 sau mai vechi: prima instalare USB cu instalatorul NVS-preserving din pachetul complet. Nu folositi standard Arduino Upload sau merged.bin cu aceasta schema NVS.

Build: Arduino-ESP32 3.3.12, ESP32P4 Dev Module, Chip Variant Before v3.00, flash 4 MB, PSRAM disabled, default USB. Folositi aceste binare numai pe hardware compatibil.

Validare: ambele profile compilate si binarele verificate automat in GitHub Actions. Testarea fizica pe controllere nu a fost efectuata de autorul pachetului. Instalarea implica restart; nu este activat rollback automat dupa boot.

Source revision: 165d55347c03137dd0b72a2cb0751ec194c4a7ca.

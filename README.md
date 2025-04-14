# Rotex_HPSU_Compact
based on https://github.com/Trunks1982/Daikin-Rotex-HPSU-CAN-Seriell
and https://github.com/juanferrla/rotex_solaris

### Differences
The rotex-hpsu.yaml contains only the needed code for the CAN-interface between a Rotex/Dakin HPSU compact 516 and ESPHome / Home Assistant
The rotex_hpsu_solaris_r3.yaml contains additionally the UART-interface for the Solaris R3 information. This runs ONLY on an ESP32-S3 device as it contains the CAN-interface too.
Please do not use both files at the same time in the same Home Assistant instance. It will leads to issues with the readings.

### PSA:
All changes made to your ESP devices and your heating unit are not supported by me!
All changes need to be made by an engineer that is trained on all the stuff, this repo covers!
It can harm your heating device!
I´m not responsible for any damages or mistakes you´ll make while attempting to copy my build or the linked repositories!
It is up to you!
It is your legal domain, your responsibility!

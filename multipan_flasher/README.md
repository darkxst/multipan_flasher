# Home Assistant Add-on: Silicon Labs Multipan Flasher Add-on

Silicon Labs Flasher add-on to flash Silicon Labs based radios.

## About

This add-on flashes the community built firmware to use Multipan (Silicon
Labs Multiprotocol Addon). It will enable automatic updates for supported dongles.

### Supported Devices
Currently supported devices for which firmware builds are included:
  * Sonoff ZBDongle-E
  * Sonoff iHost
  * Easyiot ZB-GW04 v1.1
  * Easyiot ZB-GW04 v1.2
  * Elelabs USB ELU013
  * Elelabs Raspberry Pi Shield

**NOTE:** Make sure no other add-on or integration is using the radio. In
particular disable the Zigbee Home Automation integration if not yet using the Silicon Labs
Multiprotocol add-on.

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg


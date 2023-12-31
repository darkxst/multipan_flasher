# Home Assistant Add-on: Silicon Labs MultiPan Flasher Add-on

## Installation

Follow these steps to get the add-on installed on your system:

1. Click the Home Assistant My button below to open the add-on on your Home
   Assistant instance.

   [![Open this add-on in your Home Assistant instance.][addon-badge]][addon]
1. Click the "Install" button to install the add-on.

## Supported Devices
Currently supported devices for which firmware builds are included:
  * Sonoff ZBDongle-E
  * Easyiot ZB-GW04 v1.1
  * Easyiot ZB-GW04 v1.2
  * Elelabs USB ELU013
  * Elelabs Raspberry Pi Shield

## How to use

The add-on needs a Silicon Labs based wireless module accessible through a
serial port (like Sonoff ZBDongle-E, Easyiot ZB-GW04 or other USB based Zigbee adapters).

1. Select the correct `device` in the add-on configuration tab and press `Save`.
1. Optionally select your `device model` (ZBDongle-E will be auto-detected).
1. Make sure no other add-on or integration is using the radio. In particular disable the Zigbee Home Automation integration if your not yet using Silicon Labs Multiprotocol add-on.
1. Start the add-on.
1. This addon will run at startup and check for updates. It will temporarily stop Silicon Labs Multiprotocol add-on while it runs.

## Configuration

Add-on configuration:

| Configuration      | Description                                                      |
| ------------------ | ---------------------------------------------------------------- |
| device (mandatory) | Serial service where the Silicon Labs radio is attached          |
| baudrate           | Serial port bootloader baudrate                                  |
| hardware           | Device model of the Silicon Labs radio                           |


## Support

Got questions?

You have several options to get them answered:

- The [Home Assistant Discord Chat Server][discord].
- The Home Assistant [Community Forum][forum].
- Join the [Reddit subreddit][reddit] in [/r/homeassistant][reddit]

In case you've found a bug, please [open an issue on our GitHub][issue].

[discord]: https://discord.gg/c5DvZ4e
[forum]: https://community.home-assistant.io
[reddit]: https://reddit.com/r/homeassistant
[issue]: https://github.com/darkxst/silabs-firmware-builder/issues
[addon-badge]: https://my.home-assistant.io/badges/supervisor_addon.svg
[addon]: https://my.home-assistant.io/redirect/supervisor_addon/?addon=00e2fc12_multipan_flasher&repository_url=https%3A%2F%2Fgithub.com%2Fdarkxst%2Fmultipan_flasher

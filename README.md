# Creality Box Control

[![GitHub Release][releases-shield]][releases]
[![GitHub Activity][commits-shield]][commits]
[![License][license-shield]](LICENSE)

![Project Maintenance][maintenance-shield]
[![BuyMeCoffee][buymecoffeebadge]][buymecoffee]

[![Discord][discord-shield]][discord]
[![Community Forum][forum-shield]][forum]

_Integration to integrate with [creality_box_control][creality_box_control]._

**This integration will set up the following platforms.**

Platform | Description
-- | --
`binary_sensor` | Show something `True` or `False`.
`sensor` | Show info from the wifi box.
`button` | Stop, pause, and resume prints.

## Installation

1. Using the tool of choice open the directory (folder) for your HA configuration (where you find `configuration.yaml`).
1. If you do not have a `custom_components` directory (folder) there, you need to create it.
1. In the `custom_components` directory (folder) create a new folder called `creality_box_control`.
1. Download _all_ the files from the `custom_components/creality_box_control/` directory (folder) in this repository.
1. Place the files you downloaded in the new directory (folder) you created.
1. Restart Home Assistant
1. In the HA UI go to "Configuration" -> "Integrations" click "+" and search for "Creality Box Control"

## Configuration is done in the UI

<!---->

## Contributions are welcome!

If you want to contribute to this please read the [Contribution guidelines](CONTRIBUTING.md)

***

[creality_box_control]: https://github.com/pcartwright81/creality_box_control
[buymecoffee]: https://www.buymeacoffee.com/pcartwright81
[buymecoffeebadge]: https://img.shields.io/badge/buy%20me%20a%20coffee-donate-yellow.svg?style=for-the-badge
[commits-shield]: https://img.shields.io/github/commit-activity/y/pcartwright81/creality_box_control.svg?style=for-the-badge
[commits]: https://github.com/pcartwright81/creality_box_control/commits/main
[discord]: https://discord.gg/Qa5fW2R
[discord-shield]: https://img.shields.io/discord/330944238910963714.svg?style=for-the-badge
[exampleimg]: example.png
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg?style=for-the-badge
[forum]: https://community.home-assistant.io/
[license-shield]: https://img.shields.io/github/license/pcartwright81/creality_box_control.svg?style=for-the-badge
[maintenance-shield]: https://img.shields.io/badge/maintainer-Patrick%20Cartwright%20%40pcartwright81-blue.svg?style=for-the-badge
[releases-shield]: https://img.shields.io/github/release/pcartwright81/creality_box_control.svg?style=for-the-badge
[releases]: https://github.com/pcartwright81/creality_box_control/releases

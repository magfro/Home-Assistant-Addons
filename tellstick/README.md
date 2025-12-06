# Home Assistant Add-on: TellStick

> [!CAUTION]
> **Deprecation notice**
> The library this add-on depends on is abandoned. Its last activity was 5
> years ago and it cannot be built on Alpine versions above 3.15. Users can continue
> using the add-on, but no issues or pull requests will be accepted.
>
> **IMPORTANT**
> This is a copy of the official tellstick Home Assistant add-on repo as it was
> in December 2025, before it was removed. It is only retained here in order for
> me to be able to use it in my Home Assistant installation without getting
> Repair issue notice from the Supervisor.
> 
> If you want to install it, do it at your own risk. Use this URL when you add
> the repo to Home Assistant add-on store:
> https://github.com/magfro/Home-Assistant-Addons

TellStick and TellStick Duo service.

![Supports aarch64 Architecture][aarch64-shield] ![Supports amd64 Architecture][amd64-shield] ![Supports armhf Architecture][armhf-shield] ![Supports armv7 Architecture][armv7-shield] ![Supports i386 Architecture][i386-shield]

## About

This add-on wraps around the `telldus-core` package to expose a service
for your TellStick and TellStick Duo.

This integration allows users to add switches, lights, and sensors which are
communicating with 433 MHz. There are a number of vendors (Capidi Elro,
Intertechno, Nexa, Proove, Sartano, and Viking) who are selling products that
work with TellStick.

For more details, please check the TellStick [protocol list][protocol-list].


[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg

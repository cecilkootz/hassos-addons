# Changelog

## [0.5.0] - 2023-01-01

- Update Node Exporter to 1.5.0

## [0.4.0] - 2022-10-20

- Upgrade base image from `ghcr.io/hassio-addons/base/<arch>:12.2.0` to `12.2.4`

## [0.3.0] - 2022-09-26

- Update Node Exporter to 1.4.0

## [0.2.1] - 2022-08-05

- More logging around TLS

## [0.2.0] - 2022-08-05

- Add TLS support
- Map Node Exporter config files from `/etc` to `/config`, to allow editing via the [File editor add-on](https://github.com/home-assistant/addons/tree/master/configurator)

## [0.1.1] - 2022-08-05

- Add configuration option descriptions

## [0.1.0] - 2022-07-11

- Upgrade base image from `ghcr.io/hassio-addons/base/<arch>:11.1.2` to `12.2.0` (Alpine Linux 3.16), but also disable the s6 init system because of [this issue](https://github.com/home-assistant/supervisor/issues/3642)
- Add CI from [here](https://github.com/hassio-addons/addon-glances/blob/main/.github/workflows/ci.yaml)

## [0.0.7] - 2022-06-07

- Upgrade base image from `ghcr.io/hassio-addons/base/<arch>:11.1.0` to `11.1.2` (this is the latest and last without s6 v3)

## [0.0.6] - 2022-05-17

- Fix S6-overlay v3 problems
- Add build.json file to better control base image versions
- Small formatting fixes and readability changes

## [0.0.5] - 2022-02-13

- Added HTTP Basic Auth

## [0.0.4] - 2021-12-29

- Update Node Exporter to 1.3.1

## [0.0.3] - 2021-12-12

- Built for `armv7` (Raspberry Pi 3B) thanks to [@jaredacox](https://github.com/jaredacox)

## [0.0.2] - 2021-11-16

- Built for `aarch64` (Raspberry Pi 4B)

## [0.0.1] - 2021-11-03

- Initial release

## Note

I'm not making numbered GitHub releases/tags, since this is still a beta project. These release numbers are purely made up.

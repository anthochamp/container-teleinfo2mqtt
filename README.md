# teleinfo2mqtt Container

![GitHub License](https://img.shields.io/github/license/anthochamp/container-teleinfo2mqtt?style=for-the-badge)
![GitHub Release](https://img.shields.io/github/v/release/anthochamp/container-teleinfo2mqtt?style=for-the-badge&color=457EC4)
![GitHub Release Date](https://img.shields.io/github/release-date/anthochamp/container-teleinfo2mqtt?style=for-the-badge&display_date=published_at&color=457EC4)

Container images based on [teleinfo2mqtt](https://github.com/fmartinou/teleinfo2mqtt), a service that reads Linky smart meter data (Télé-Information Client) and publishes it to an MQTT broker.

## How to use this image

```shell
docker run \
  --device /dev/ttyUSB0 \
  -e MQTT_HOST=mqtt-broker \
  anthochamp/teleinfo2mqtt
```

## Configuration

This container adds Docker secrets support: append `__FILE` to any environment variable name to read its value from a file (e.g., `MQTT_PASSWORD__FILE=/run/secrets/mqtt_password`).

All environment variables supported by teleinfo2mqtt are available. Refer to the [teleinfo2mqtt documentation](https://fmartinou.github.io/teleinfo2mqtt/) for the full list.

**References:**

- [teleinfo2mqtt documentation](https://fmartinou.github.io/teleinfo2mqtt/)
- [teleinfo2mqtt on GitHub](https://github.com/fmartinou/teleinfo2mqtt)

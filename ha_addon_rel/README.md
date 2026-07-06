# Home Assistant App: TSUN-Proxy

Integrates TSUN inverters (e.g. TSOL MS800, MS2000, MS3000) and batteries (TSOL DC1000) into Home Assistant.

It is based on the [TSUN Proxy][tsunproxy] and enables a reliable connection between TSUN devices and an MQTT broker.

With the App, you can easily retrieve real-time values such as power, current and daily energy and integrate the inverter into Home Assistant.
This works even without an internet connection.

The optional connection to the TSUN Cloud can be disabled!

## Features

- Supports TSUN MX Series:
  - Microinverter 1-in-1: TSOL-MX500, MX450 and MX400
  - Microinverter 2-in-1: TSOL-MX1000, MX900 and MX800
  - Microinverter 4-in-1: TSOL-MX2250
  - Microinverter 6-in-1: TSOL-MX3300, MX3000, MX2700, MX2500 and MX2400
- Supports TSUN MS Series:
  - Microinverter 1-in-1: TSOL-MS400, MS350 and MS300
  - Microinverter 2-in-1: TSOL-MS800, MS700 and MS600
  - Microinverter 4-in-1: TSOL-MS2000, MS1800 and MS1600
- Supports TSUN Batteries:
  - DCU: TSOL-DC1000
- `Home-Assistant` auto-discovery support
- `MODBUS` support via MQTT topics
- `AT-Command` support via MQTT topics (GEN3PLUS only)
- Faster DataUp interval sends measurement data to the MQTT broker every minute
- Self-sufficient island operation without internet
- Security-Features:
  - control access via `AT-commands`

## About

This App and the TSUN Proxy is not related to the company TSUN. It is a private initiative that aims to connect TSUN inverters and storage systems with an MQTT broker. There is no support and no warranty from TSUN.

[tsunproxy]: https://github.com/s-allius/tsun-gen3-proxy

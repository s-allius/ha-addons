# Home Assistant Add-on: TSUN-Proxy (Debug)

This is a bleeding-edge version of the `TSUN Proxy`  Add-On with debuging enabled by default.

The versions may be based on different feature branches and therefore the range of functions may change.

It is intended to be used to simulate special situations/problems and should only be used in consultation with the maintainer.

For production please use the stable version `TSUN Proxy`. If you are interested in a bleeding edge version, we offer the `TSUN Proxy (dev)` version.

## Features

- Supports TSUN GEN3 PLUS inverters: TSOL-MS2000, MS1800 and MS1600
- Supports TSUN GEN3 PLUS batteries: TSOL-DC1000 (from version 0.13)
- Supports TSUN GEN3 inverters: TSOL-MS3000, MS800, MS700, MS600, MS400, MS350 and MS300
- `Home-Assistant` auto-discovery support
- `MODBUS` support via MQTT topics
- `AT-Command` support via MQTT topics (GEN3PLUS only)
- Faster DataUp interval sends measurement data to the MQTT broker every minute
- Self-sufficient island operation without internet
- Security-Features:
  - control access via `AT-commands`

## About

This Add-on and the TSUN Proxy is not related to the company TSUN. It is a private initiative that aims to connect TSUN inverters and storage systems with an MQTT broker. There is no support and no warranty from TSUN.

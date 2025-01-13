[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2Fjnrcorp%2Fha-blueprints%2Fmain%2Fha-blueprint-sync-custom-brightness.yaml)

**Sync Brightness to Z-Wave Attribute v1.0** 🔛

This blueprint allows you to easily create/maintain an automation that links the state of multiple entities:
  - set the brightness of any Z-Wave dimmer switch entity, it will set the custom brightness z-wave attribute to that brightness.
    - For Zooz, this is Custom Brightness.
    - For Leviton, this is Initial Brightness.

**NOTE**: You can select any device and this script will not verify what you provide is accurate, but it will fail if the device is not compatible.

**CHANGELOG:**
  - 1.0: (2025-01-13)
    - First official release

**Source:**
[![jnrcorp - ha-blueprints](https://img.shields.io/static/v1?label=jnrcorp&message=ha-blueprints&color=blue&logo=github)](https://github.com/jnrcorp/ha-blueprints/blob/main/ha-blueprint-sync-custom-brightness.yaml "Go to GitHub repo") [![stars - ha-blueprints](https://img.shields.io/github/stars/jnrcorp/ha-blueprints?style=social)](https://github.com/jnrcorp/ha-blueprints) [![forks - ha-blueprints](https://img.shields.io/github/forks/jnrcorp/ha-blueprints?style=social)](https://github.com/jnrcorp/ha-blueprints)

**Support:**
[![HA Community - Topic](https://img.shields.io/static/v1?label=HA+Community&message=Topic&color=2ea44f&logo=home-assistant)](https://community.home-assistant.io/t/linked-entities-keep-mutlple-entities-binary-state-in-sync-lights-switches-etc/662836?u=jnrcorp)

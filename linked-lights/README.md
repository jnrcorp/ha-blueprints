[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2Fjnrcorp%2Fha-blueprints%2Fmain%2Flinked-lights%2Fha-blueprint-linked-lights.yaml)

**Linked Lights v1.4**

This blueprint allows you to easily create/maintain an automation that links the state of multiple lights:
  - turn ANY linked light ON, it will turn ON ALL linked lights.
  - turn ANY linked light OFF, it will turn OFF ALL linked lights.
  - set the brightness of any light entity, it will set the same brightness of ALL linked light entities.
  - set the color temp of any light entity, it will set the same color temperature of ALL linked light entities.

**NOTE**: You can select any light entity with an ON/OFF state (bulbs, lights, etc.), lights with brightness or color temperature attributes.

My main use-case was for multiple light switches in the house controlling the same light.

**CHANGELOG:**
  - **1.0**: (2025-05-10)
    - First official release - ported from https://github.com/alexdelprete/ha-blueprints

**Source:**
[![jnrcorp - ha-blueprints](https://img.shields.io/static/v1?label=jnrcorp&message=ha-blueprints&color=blue&logo=github)](https://github.com/jnrcorp/ha-blueprints/blob/main/linked-lights/ha-blueprint-linked-lights.yaml "Go to GitHub repo") [![stars - ha-blueprints](https://img.shields.io/github/stars/jnrcorp/ha-blueprints?style=social)](https://github.com/jnrcorp/ha-blueprints) [![forks - ha-blueprints](https://img.shields.io/github/forks/jnrcorp/ha-blueprints?style=social)](https://github.com/jnrcorp/ha-blueprints)

**Support:**
[![HA Community - Topic](https://img.shields.io/static/v1?label=HA+Community&message=Topic&color=2ea44f&logo=home-assistant)](https://community.home-assistant.io/t/linked-lights-keep-lights-in-sync/887934?u=jnrcorp)

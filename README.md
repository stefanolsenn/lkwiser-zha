# LK Wiser 550D0001 - Schneider Wiser 4-Button Zigbee Device Automation Blueprint

This blueprint allows you to create automations for the **Schneider Wiser 4-button Zigbee device** (model 550D0001) using ZHA events in Home Assistant. It supports four button actions (top left, top right, bottom left, and bottom right), where each button has an associated action for single presses (on/off) for both endpoints.

## Prerequisites
- **Home Assistant** instance with ZHA integration set up.
- A **Schneider Wiser 550D0001** Zigbee device paired with Home Assistant using the ZHA integration.

## Blueprint Inputs
This blueprint accepts the following inputs:

1. **zigbee_device**: Select your Schneider Wiser Zigbee device (integrated via ZHA).
2. **top_left_action**: Action to trigger on the top left button (endpoint 21, "on").
3. **top_right_action**: Action to trigger on the top right button (endpoint 21, "off").
4. **bottom_left_action**: Action to trigger on the bottom left button (endpoint 22, "on").
5. **bottom_right_action**: Action to trigger on the bottom right button (endpoint 22, "off").

## Add blueprint
   
  [![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2Fstefanolsenn%2Flkwiser-zha%2Frefs%2Fheads%2Fmain%2Flk-wiser.yaml)

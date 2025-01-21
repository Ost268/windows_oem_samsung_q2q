# Windows on Snapdragon 888 Board Support Package

Welcome to the Snapdragon 888 Windows BSP Platform repository.

This repository contains drivers, components and files needed to run Windows on official Snapdragon 888 platforms such as:

- Modem Testing Platform (MTP)
- Qualcomm Reference Design (QRD)

We currently support the following chipsets:

- Snapdragon 888
- Snapdragon 888+
- Snapdragon 888 4G

In the following variants:

- MSM
- APQ

And with the following configurations:

- SDX65
- HSP
- HSP PRO

## Currently non functional chipset features

- List to be done, consider "everything" for now.

## Reference design support status


| Feature                | Description                                                                                                    | Working state |
|------------------------|----------------------------------------------------------------------------------------------------------------|---------------|
| ⌨️ Side buttons         |                                                                                                                | ✅             |
| ♋ Cellular Calls       |                                                                                                                | ❌             |
| ♋ Cellular Data        |                                                                                                                | ❌             |
| ♋ Cellular Texts       |                                                                                                                | ❌             |
| ♋ WiFi                 |                                                                                                                | ❌             |
| 🌡️ Thermal sensors      |                                                                                                                | ✅             |
| 🎆 GPU                  |                                                                                                                | ❌             |
| 👆 Touchscreen          |                                                                                                                | ✅             |
| 💤 Modern Standby       |                                                                                                                | ❌             |
| 📌 GPS                  |                                                                                                                | ✅             |
| 📦 UFS                  |                                                                                                                | ✅             |
| 📲 Display              |                                                                                                                | ✅             |
| 📳 Vibration motor      |                                                                                                                | ❌             |
| 📸 [Camera Flash]       |                                                                                                                | ❌             |
| 🔋 Battery              |                                                                                                                | ❌             |
| 🔌 Charger              |  slow charging                                                                                                 | ❌             |
| 🔵 Bluetooth            |                                                                                                                | ❌             |
| 📺 HDMI / DP out        |                                                                                                                | ❌             |
| 🧭 Sensors              |                                                                                                                | ✅             |
| 🧮 SoC Cores            |                                                                                                                | ✅             |
| 🪵 USB C                |                                                                                                                | ✅             |
| 📸 Camera Sensors       | Requires Cam Sensor drivers configuration, otherwise camera subsystem is functional                            | ❌             |
| 🔊 Audio                | Requires WP ADSP for Audio subsystem to work. Workaround hasn't been found yet                                 | ❌             |
| 🧑‍💼 Hyper-V              | Requires correctly configured WP firmware, only possible with unfused devices                                  | ⚠️             |
| 🧬 Fingerprint scanner  | Driver works, but sensor does not                                                                              | ✅             |


## Relevant Documentation

You can find a few notes under the docs folder inside this repository.

## Misc

These driver files are not perfect, typos may exist, feel free to file an issue on GitHub in case you found any.

## Resources

## Copyright, License, Disclaimers and end user license agreement

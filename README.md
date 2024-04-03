# esphome-config
Repo for my [ESPHome](https://esphome.io/) configurations. Contributions welcome.

## Deye SUN-12K-SG04LP3 - Modbus
The most complete 😉 Modbus connector for the Deye SG04LP3 three-phase hybrid low voltage inverter. Should be compatible with all versions: SUN-5K-SG04LP3, SUN-6K-SG04LP3, SUN-8K-SG04LP3, SUN-12K-SG04LP3

[deye-sun-12k-sg04lp3.yaml](./devices/deye-sun-12k-sg04lp3.yaml)

Based on the work of [Sunsynk-Home-Assistant-Dash](https://github.com/slipx06/Sunsynk-Home-Assistant-Dash), [deye-inverter-mqtt](https://github.com/kbialek/deye-inverter-mqtt), [esphome-for-deye](https://github.com/klatremis/esphome-for-deye), [home_assistant_solarman](https://github.com/StephanJoubert/home_assistant_solarman), and more.


## Victron SmartSolar 75 | 15 - BLE
This ESPHome connector reads the SmartSolar sensors using the Bluetooth advertising protocol. It also provides a few extras such as battery charge and discharge, load voltage and power, and daily load consumption. I expect it to work with all SmartSolar devices, although I have only tested it with the SmartSolar 75 | 15.

[victron-smartsolar-75-15.yaml](./devices/victron-smartsolar-75-15.yaml)

#### Sensors
- PV power and daily production 
- Battery current, power, voltage, daily charge and discharge
- Load current, power, voltage, and daily consumption
- MPPT state, error

For device configuration details, visit [esphome-victron_ble](https://github.com/Fabian-Schmidt/esphome-victron_ble?tab=readme-ov-file#victron_ble-component-recommended).

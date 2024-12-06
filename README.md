# esphome-victron-ble-ir
 Victron BLE (instant readout) EspHome component

Using an ESP32 to listen to BLE advertisements from Victron devices supporting this protocol.  
The protocol is somehow [officially documented](https://communityarchive.victronenergy.com/storage/attachments/extra-manufacturer-data-2022-12-14.pdf) and has some ESPHome implementations too (I've based mine off this [repository](https://github.com/Fabian-Schmidt/esphome-victron_ble)). Current implementation works and is being tested on a Victron Multi RS inverter. Support for all other BLE compliant products even if implemented has not been tested so far

## How to use
Beside the usual EspHome platforms configuration (an ESP32 with BLE is needed) follow the sample [config](https://github.com/krahabb/esphome-victron-ble-ir/blob/main/components/m3_victron_ble_ir/m3_victron_ble_ir_example.yaml)

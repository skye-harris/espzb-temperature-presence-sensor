# ESP32 Zigbee Temperature/Presence Sensor

Based on the Espressif Temperature Sensor example project at https://github.com/espressif/arduino-esp32/tree/master/libraries/Zigbee/examples/Zigbee_Temperature_Sensor

* Reports humidity in addition to temperature, from a DHT22 sensor module
* Reports motion/presence from a connected sensor (I use LD2410 however a PIR sensor should also work just fine)
* Implements the zigbee identify functionality with an RGB LED
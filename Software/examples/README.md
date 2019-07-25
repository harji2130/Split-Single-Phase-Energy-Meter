## Examples ##
This example software was created by us and the community to use the CircuitSetup Split Single Phase Energy Meter in different applications.

### Sketches ###
- **ATM90E32_Basic_SPI** is a Basic Arduino sketch - this is a basic example that shows how to use the ATM90E32 library in Arduino. It simply outputs values to the serial window. The basis for this was created by [Tisham Dhar for his ATM90E26 Featherwing meter.](https://github.com/whatnick/ATM90E26_Arduino/tree/master/examples)
- **ATM90E32_MQTT** - an Arduino sketch using MQTT to send energy meter data via a Wemos D1. [Created by digiblur](https://github.com/digiblur/digiNRG_SplitPhase)
- **Home_Assistant_MQTT** - an Arduino sketch to send data to Home Assistant using MQTT. Includes the Home Assistant sensor file. Thanks to Richard Talley for supplying this.

### ATM90E32 Libraries ###
- **[CircuitPython](https://github.com/BitKnitting/CircuitSetup_CircuitPython)** - The ATM90E32 library converted to work with Adafruit's CircuitPython. Created by BitKnitting
- **[MicroPython](https://github.com/BitKnitting/CircuitSetup_micropython)** - The ATM90E32 library converted to work with MicroPython. Created by BitKnitting
- **[ESPHome](https://github.com/esphome/esphome/tree/dev/esphome/components/atm90e32)** - direct integration for ESPHome, which allows you to more easily import energy data directly into home automation systems like Home Assistant. Created by thompsa.
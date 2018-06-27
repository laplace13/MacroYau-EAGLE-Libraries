# Macro Yau's EAGLE Libraries

This repository includes PCB component libraries for selected electronic and electromechanical components.

## Components

- Energy Harvesting Power Management IC (energy-harvesting-pmic.lbr)
  - [Texas Instruments BQ25570](www.ti.com/product/bq25570)
- [Espressif Systems ESP32 SoC](http://www.espressif.com/en/products/hardware/esp32/overview) (esp32.lbr)
  - Ai-Thinker ESP3212 _(Obsolete)_
  - Ai-Thinker ESP-32S
  - Espressif Systems ESP-WROOM-32
- [Espressif Systems ESP8266 SoC](https://www.espressif.com/en/products/hardware/esp8266ex/overview) (esp8266.lbr)
  - Ai-Thinker ESP-12E
  - Espressif Systems ESP-WROOM-02

## Installation

Download the latest [ZIP file](https://github.com/MacroYau/MacroYau-Eagle-Libraries/archive/master.zip) (or via Git) and extract the `MacroYau-Eagle-Libraries` folder to the `lbr` folder inside your EAGLE installation directory. By default, the installation location should be:

- `/Applications/EAGLE-7.6.0/lbr` (macOS)
- `C:\Program Files\EAGLE-7.6.0\lbr` (Windows)

If you prefer to keep custom libraries in a separate directory to avoid migration during every EAGLE version update, you can refer to [this tutorial](https://github.com/adafruit/Adafruit-Eagle-Library).

## Compatibility

The libraries are created with [EAGLE 7.6.0](https://cadsoft.io) and should be compatible with newer versions.

## License

[Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/)

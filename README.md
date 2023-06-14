# I2C/SPI OLED module

MLAB module for connecting OLED displays [EA OLEDM128-6GGA](https://www.lcd-module.com/fileadmin/eng/pdf/grafik/oledm128-6e.pdf). The module contains standard MLAB headers and internal 12V power supply for the OLED display. The module can be manufactured in SPI or I2C variant (never booth simaltaniously). Display is based on [SSD1306](https://cdn-shop.adafruit.com/datasheets/SSD1306.pdf) controller. 

The module features an integrated I2C level converter, which allows you to operate the display with power supply in range 3-5V, while the I2C bus levels can reach the same values. The SPI variant does not have this feature and the SPI must operate at levels of 2-3.3V.

The module includes a pair of LEDs and a buzzer. Booth is drivered by integrated transistor.

## Design
![OLED01](/doc/gen/img/OLED01-top.svg) ![OLED01](/doc/gen/img/OLED01-bottom.svg)

## Schematics
[![Schematics](/doc/gen/OLED01-schematic.svg)](/doc/gen/OLED01-schematic.pdf)

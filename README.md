# OLED01 - OLED Display Module with I2C interface

The OLED01 is an MLAB module, designed for using OLED displays, specifically the [EA OLEDM128-6GGA](https://www.lcd-module.com/fileadmin/eng/pdf/grafik/oledm128-6e.pdf). This  module provides a solution for integrating high-contrast OLED displays into various systems.

Built around the [SSD1306](https://cdn-shop.adafruit.com/datasheets/SSD1306.pdf) controller, this module communicates using the I2C protocol. The module's design uses standard MLAB headers and an internal 12V power supply, for powering the OLED display.

An important feature of the OLED01 module is the integrated I2C level converter, which ensures the display can operate within a 3-5V power supply range, with I2C bus levels attaining the same values.

Beyond the OLED display connection, the OLED01 module incorporates a pair of LEDs and a buzzer, driven by an integrated transistor.  The OLED01 module is equipped with a reset circuit to ensure proper clear display initialization after power-up.

## Design
![OLED01](/doc/gen/img/OLED01-top.svg) ![OLED01](/doc/gen/img/OLED01-bottom.svg)

The OLED01 module is designed to promote user-friendly integration and durability. Its compact form factor allows for easy placement within diverse hardware configurations, and the robust construction assures longevity. The contained OLED display delivers a resolution of 128x64 pixels with high-contrast visual output.

## Specifications

- **Interface**: I2C
- **Power Supply**: 3-5V operational range for I2C, Internal 12V supply for OLED
- **Display**: 128x64 pixels resolution
- **Additional Features**: Pair of LEDs and buzzer driven by integrated transistor by external GPIO
- **Reset Circuit**: Included for proper initialization of the OLED display

## Possible Applications

The OLED01 module's versatility allows for use in a wide range of applications:

2. **Industrial Control Systems:** The robustness and clarity of the OLED display, coupled with the additional buzzer and LED indicators, make this module a top choice for control panels in industrial machinery and robotics.
3. **Automotive Systems:** The OLED01 can serve as an interface for vehicle systems, providing clear and sharp visual output under various lighting conditions.
5. **Experimental Projects and Prototyping:** The module's easy integration through MLAB headers and broad compatibility with the I2C interface make it suitable for experimental electronics projects, prototyping, and educational applications.

## Schematics
[![Schematics](/doc/gen/OLED01-schematic.svg)](/doc/gen/OLED01-schematic.pdf)

## Usage examples

  * [Li-ion-Charger](https://github.com/MLAB-project/Li-ion-Charger)

# OLED01 - OLED Display Touchscreen with I2C interface

The OLED01 is an MLAB module, designed for using OLED displays, specifically the [EA OLEDM128-6GGA](https://www.lcd-module.com/fileadmin/eng/pdf/grafik/oledm128-6e.pdf) built around the [SSD1306](https://cdn-shop.adafruit.com/datasheets/SSD1306.pdf) controller, this module communicates using the I2C protocol. The module's design uses standard MLAB headers and an internal 12V power supply, for powering the OLED display. This  module provides a solution for integrating high-contrast OLED displays into various systems.

An important feature of the OLED01 module is the integrated I2C level converter, which can operate within a 3-5V power supply and signal range. The OLED01 also incorporates a pair of LEDs and a buzzer, driven by an integrated transistor and it is equipped with a reset circuit to ensure proper clear display initialization after power-up.

## Design
![OLED01](/doc/gen/img/OLED01-top.svg) ![OLED01](/doc/gen/img/OLED01-bottom.svg)

The OLED01 module is designed to promote user-friendly integration and durability. Its compact form factor allows for easy placement within diverse hardware configurations, and the robust construction assures longevity. The contained OLED display delivers a resolution of 128x64 pixels with high-contrast visual output.

### Touchscreen Support

The OLED01 module supports 4-wire resistive touchscreens through integration with the [TSC2007 touch controller](https://www.ti.com/lit/ds/symlink/tsc2007.pdf). This I2C-based controller enables position and pressure detection with 12-bit resolution, low power consumption, and internal preprocessing for noise reduction. The PENIRQ output allows interrupt-based touch event detection.

This expands the module's usability for interactive user interfaces in embedded systems.


## Specifications

- **Interface**: I2C
- **Touchscreen Support**: 4-wire resistive touchscreen interface via TSC2007 (I2C, 12-bit ADC)
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

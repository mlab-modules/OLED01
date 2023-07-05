# I2C OLED Module: OLED01

The OLED01 is an MLAB module, designed for interfacing OLED displays, specifically the [EA OLEDM128-6GGA](https://www.lcd-module.com/fileadmin/eng/pdf/grafik/oledm128-6e.pdf). This versatile module provides an efficient and practical solution for integrating high-contrast, power-efficient OLED displays into various systems.

Built around the reliable and robust [SSD1306](https://cdn-shop.adafruit.com/datasheets/SSD1306.pdf) controller, this module communicates using the I2C protocol. The module's design incorporates standard MLAB headers and an internal 12V power supply, specifically for powering the OLED display.

An important feature of the OLED01 module is the integrated I2C level converter, which ensures the display can operate within a 3-5V power supply range, with I2C bus levels attaining the same values.

Beyond the OLED display connection, the OLED01 module incorporates a pair of LEDs and a buzzer, driven by an integrated transistor. This extends the module's functionality, providing additional user feedback and making it a more versatile component for an array of applications.

Understanding the operational requirements of OLED displays, the OLED01 module is equipped with a reset circuit to ensure proper initialization of the display post power-up.

## Design
![OLED01](/doc/gen/img/OLED01-top.svg) ![OLED01](/doc/gen/img/OLED01-bottom.svg)

The OLED01 module is designed to promote user-friendly integration and durability. Its compact form factor allows for easy placement within diverse hardware configurations, and the robust construction assures longevity. The contained OLED display delivers a resolution of 128x64 pixels with high-contrast visual output.

## Specifications

- **Interface**: I2C
- **Power Supply**: 3-5V operational range for I2C, Internal 12V supply for OLED
- **Display**: 128x64 pixels resolution
- **Additional Features**: Pair of LEDs and buzzer driven by integrated transistor
- **Reset Circuit**: Included for proper initialization of the OLED display

## Possible Applications

The OLED01 module's versatility allows for use in a wide range of applications:

1. **Consumer Electronics:** The OLED01 is ideal for wearable devices, handheld gadgets, and home automation controllers, thanks to the high-contrast, bright output and power efficiency of the OLED display.
2. **Industrial Control Systems:** The robustness and clarity of the OLED display, coupled with the additional buzzer and LED indicators, make this module a top choice for control panels in industrial machinery and robotics.
3. **Automotive Systems:** The OLED01 can serve as an interface for vehicle systems, providing clear and sharp visual output under various lighting conditions.
4. **Medical Devices:** With its high contrast and sharpness, the module is suitable for devices requiring high-quality visual feedback, like medical monitoring devices.
5. **Experimental Projects and Prototyping:** The module's easy integration through MLAB headers and broad compatibility with I2C interface makes it an excellent choice for experimental electronics projects, prototyping, and educational applications.

## Schematics
[![Schematics](/doc/gen/OLED01-schematic.svg)](/doc/gen/OLED01-schematic.pdf)

The provided schematics offer a thorough insight into the OLED01 module's electrical design, proving helpful for troubleshooting, modifications, or gaining a better understanding of the operation and interconnectivity of the various components within the module.

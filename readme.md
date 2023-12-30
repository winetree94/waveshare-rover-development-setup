# Waveshare Rover Development Setup

This repository includes a guide and modules for developing the Waveshare rover using the Arduino IDE.
It was created as a personal backup due to Waveshare's unhelpful documentation and the scattered nature of their resources.

# What's in the box?

- `examples` - Demo Arduino projects for the built-in ESP32 module in the rover.
- `libraries` - Requirement libraries for building `examples`
  - `Adafruit_BusIO` - 1.14.5 (*)
  - `Adafruit_GFX_Library` - 1.11.9 (*)
  - `Adafruit_SSD1306` - 2.5.9 (*)
  - `ArduinoJson` - 6.21.4 (*)
  - `ESP32_Servo` - unknown
  - `INA219_WE` - 1.3.7 (*)
  - `SCServo` - unknown
- `packages` - Requirement packages for building `examples`
  - `esp32` - 1.0.6 

> (*) indicates that it can be installed directly from within the Arduino IDE.

> The ESP installation process can be substituted with [Link](https://docs.espressif.com/projects/arduino-esp32/en/latest/installing.html). Do not update package beyond version 1.0.6. Version 2.x does not work with the ESP32 module in the rover.

# How to use this repository

1. Unzip the files in the 'libraries' folder and copy them to the Arduino Library folder. (On Windows, this is C:\Users\USERNAME\AppData\Local\Arduino15\libraries.)
2. Unzip the files in the 'packages' folder and copy them to the Arduino Package folder. (On Windows, this is C:\Users\USERNAME\AppData\Local\Arduino15\packages.)
3. Unzip the WAVE_ROVER file in the 'examples' folder, and then open the WAVE_ROVER.ino file using the Arduino IDE.
4. Select the correct board and port in the Arduino IDE, and then click the upload button to upload the program to the board. (Refer to the "Upload Demo" section at [Link](https://www.waveshare.com/wiki/How_To_Install_Arduino_IDE))

# Useful Links

- https://www.waveshare.com/wiki/WAVE_ROVER
- https://www.waveshare.com/wiki/General_Driver_for_Robots
- https://www.waveshare.com/wiki/How_To_Install_Arduino_IDE
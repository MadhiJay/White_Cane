# White_Cane
This source code used for intergrate withh smart white cane  to detects water spits and scan money according color.

## Tools & Technologies used
- Arduino Nano
- TCS34725 Color Sensor
- Water Sensor

### Code to Note
Water sensor has three terminals - S, Vout(+), and GND (-). Connect the sensor as follows −

- Connect the +Vs to +5v on your Arduino board.
- Connect S to digital pin number 8 on Arduino board.
- Connect GND with GND on Arduino.
- Connect LED to digital pin number 9 in Arduino board.
When the sensor detects water, pin 8 on Arduino becomes LOW and then the LED on Arduino is turned ON.

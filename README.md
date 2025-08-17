DHT Sensor with Arduino (DHT11)

This project demonstrates how to interface a DHT temperature and humidity sensor with an Arduino board. The DHT sensor can measure humidity (%RH) and temperature (°C/°F), and also compute the heat index.

The example code uses the DHT11 sensor, but you can also use DHT22 or DHT21 by changing the code definitions.

Components Required

Arduino Uno (or compatible board)

DHT11 / DHT22 / DHT21 Sensor

Jumper wires

Breadboard

Wiring Diagram

Pin 1 (VCC) → +5V (or 3.3V for some boards)

Pin 2 (Data) → Digital pin 2 (with 10kΩ pull-up resistor to VCC)

Pin 4 (GND) → GND

Arduino Code

The sketch reads:

Humidity (%)

Temperature (°C and °F)

Heat Index (Feels-like temperature)

It prints the values to the Serial Monitor every 2 seconds.

Circuit diagram

![DHT sensor circuit diagram](DHT.png)

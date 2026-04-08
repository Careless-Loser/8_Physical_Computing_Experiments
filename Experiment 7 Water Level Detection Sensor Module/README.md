# Experiment 7: DHT11 Temperature and Humidity Sensor 

In this experiment, we will learn how to read environmental data using a DHT11 Temperature and Humidity Sensor.

## Description

The DHT11 is a basic, low-cost digital sensor that measures both ambient temperature and air humidity. It uses a capacitive humidity sensor and a thermistor to measure the surrounding air, and it outputs a digital signal on a single data pin (meaning no analog input pins are required). While it is not the fastest sensor on the market, it is highly reliable and accurate enough for most projects that need to keep track of basic environmental readings.

To interface with this sensor, we will be using a dedicated software library designed specifically for DHT sensors. Interacting with the DHT11 from scratch requires precise microsecond timing to read the data pulses. By utilizing the library, all of this complex timing is handled in the background, making our Arduino code much shorter, cleaner, and easier to write.

## Components Required

* 1x Elegoo Uno R3 (or standard Arduino Uno R3)
* 1x DHT11 Temperature and Humidity module
* 3x F-M wires (Female to Male DuPont jumper wires)

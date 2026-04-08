# Experiment 7: Water Level Detection Sensor 

In this experiment, you will learn how to measure the depth of water using a water level detection sensor module.

## Description

This sensor module is designed to perceive water depth using a very simple but effective method. Its core component is an amplifying circuit composed of a transistor and a series of exposed, pectinate (comb-like) PCB traces. 

When you partially submerge the sensor into water, these exposed traces act as a variable resistor. The resistance across the traces changes depending on how much of the sensor is underwater. This physical change is then converted into a variable analog electrical signal. By connecting this sensor to the Arduino, you can read these voltage changes using the Uno R3's built-in Analog-to-Digital Converter (ADC) function, allowing your code to accurately track the rise and fall of the water level.

## Components Required

* 1x Elegoo Uno R3 (or standard Arduino Uno R3)
* 1x Water level detection sensor module
* 3x F-M wires (Female to Male DuPont jumper wires)

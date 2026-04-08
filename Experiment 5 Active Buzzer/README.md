# Experiment 5: Active Buzzer Overview

In this experiment, you will learn how to generate sound and audible alerts using an active buzzer.

## Description

Electronic buzzers are DC-powered audio signaling devices equipped with an integrated circuit. They are widely used to provide audio feedback and alerts in computers, alarms, timers, automotive electronics, and various other consumer products. 

Buzzers are generally categorized into two distinct types: **active** and **passive**. 

* **Active Buzzers:** An active buzzer is equipped with a built-in oscillating source. Because of this internal circuitry, it will automatically generate a continuous sound as soon as it is electrified with a direct current (DC) voltage. You can usually identify an active buzzer by looking at its bottom; it is typically sealed or enclosed with a piece of black tape or epoxy. Because of the built-in circuitry, active buzzers are slightly more expensive but much easier to use for simple alarms.
* **Passive Buzzers:** A passive buzzer does not have an internal oscillator. If you simply apply DC power to it, it will not make a sound. Instead, to drive a passive buzzer, the microcontroller must send it a specific square wave signal (usually between 2KHz and 5KHz). Passive buzzers can generally be identified by their exposed green circuit board on the bottom.

## Components Required

* 1x Elegoo Uno R3 (or standard Arduino Uno R3)
* 1x Active buzzer
* 2x F-M wires (Female to Male DuPont jumper wires)

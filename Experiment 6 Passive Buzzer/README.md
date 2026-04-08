# Experiment 6: Passive Buzzer Overview

In this experiment, you will learn how to use a passive buzzer to play specific musical notes by controlling audio frequencies.

## Description and Purpose

The purpose of this experiment is to generate a musical scale consisting of eight different sounds, with each sound lasting for 0.5 seconds. You will program the microcontroller to output specific frequencies to play the following sequence: 

* Alto Do (523Hz)
* Re (587Hz)
* Mi (659Hz)
* Fa (698Hz)
* So (784Hz)
* La (880Hz)
* Si (988Hz)
* Treble Do (1047Hz)

### Component Introduction: Passive Buzzer

A passive buzzer works by using Pulse Width Modulation (PWM) signals to vibrate the surrounding air. By appropriately changing the vibration frequency of the electrical signal, the buzzer can generate different musical pitches. For example, sending a 523Hz pulse generates an "Alto Do", a 587Hz pulse generates a "Re", and a 659Hz pulse produces a "Mi". By sequencing these specific frequencies, you can use the passive buzzer to play a complete song.

**⚠️ Important Technical Note:** You must be careful **not** to use the standard Arduino `analogWrite()` function to generate the pulse for the buzzer. The frequency output of `analogWrite()` is fixed (typically around 490Hz or 500Hz depending on the pin). Because that frequency cannot be dynamically changed, it cannot produce different musical notes. Instead, you must use a function that allows you to specify the exact frequency (such as the standard `tone()` function in Arduino).

## Components Required

* 1x Elegoo Uno R3 (or standard Arduino Uno R3)
* 1x Passive buzzer
* 2x F-M wires (Female to Male DuPont jumper wires)

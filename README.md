# Simple tachometer with ATtiny2313A

## Description

A simple tachometer that shows the frequency (in RPM) of a input signal on an alphanumeric LCD display. Also has a PWM output which can be toggled and adjusted using the buttons interface. Range from about 50 RPM to 20 kRPM seems to be working well.

## Build

Just running `make` with the avr toolchain installed should generate the `.hex` file required to program the microcontroller. Also can use `make prog` for automatically programming the µC, just specify the programmer to be used on the `Makefile`.

## Schematic

<p align="center">
<img src="sch/sch.png" width="600"><br>
<sub><sup>Current schematic and pinout used</sub></sup>
</p>

## TODOs

1. Closed loop PWM/RPM control (will probably require a µC with larger memory, like a tiny4313A or some ATmega)
2. Documentation obviously

## Licence

This project is available under a MIT licence.
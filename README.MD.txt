# STM32 GPIO Blink – Nucleo-F401RE

This project demonstrates basic GPIO output on an STM32 Nucleo-F401RE board using STM32CubeIDE and the HAL library.

## Hardware
- STM32 Nucleo-F401RE
- External LED + 220Ω resistor
- Breadboard and jumper wires

## GPIO Mapping
- PA5 (Arduino D13) → LED (via resistor)
- GND → LED cathode

## Functionality
- Configures GPIO pins using CubeMX
- Toggles an LED every 500 ms using HAL

## Tools
- STM32CubeIDE
- STM32CubeF4 HAL
- Git & GitHub

## What I learned
- STM32 GPIO configuration
- Board pin vs MCU pin mapping
- HAL initialization flow
- Flashing and debugging with ST-LINK
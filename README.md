# Project Name
Embedded linux

# Overview
These functions access the Linux file system and configure and control analog GPIOs and pins according to the application being developed.

## Platform
Beaglebone

## Architecture
Debian 32 bits (Embedded Linux)

## Usage
- init_gpio 
Configure the output gpio as output or input;

- set_gpio_high
Set the output gpio value;

- set_gpio_low
Clear the output gpio value;

- get_value
Return the input gpio value;

- init_analog_pins
Configure the analogs pins to read;

- get_value_ain
Read the analog pin.

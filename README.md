# FirstTrace

## Description

This project demonstrates a custom PCB containing the STM32F103C8T6 microcontroller. This board can be used for embedded development using GPIO and SWD Headers.

## Components

1. Microcontroller: STM32F103C8T6
   - 20 KB SRAM and 64 KB Flash
   - 72 MHz clock speed 
   
2. USB Connectivity:
   - USB Micro-B for data and power 
   - USBLC6-2SC6 for ESD protection

3. Power Supply: AMS1117-3.3 
   - Voltage regulator for stable 3.3V output
  
4. Headers:
   - SWD headers for debugging and programming
   - GPIO headers for external connections

## Schematic and PCB Design

The board was designed using KiCad. Files from the PCB design can be found in the hardware folder. This folder includes:

- PCB Schematic 
- PCB Layout
- Gerber files
- Assembly files

## How to Use

1. Power the board
   - Use a USB Micro cable to power the board.
   
2. Microcontroller Programming:
   - Use STM32CubeIDE to program the microcontroller.
   - Use an SWD debugger, such as ST-Link, to the SWD headers.

3. GPIO Access
   - Use the GPIO headers to connect peripherals.
  

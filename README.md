# Pico MZ-80K beta

## A Sharp MZ-80K Emulator for the Raspberry Pico Microcontroller

A Raspberry Pico implementation of the Sharp MZ-80K sold in the UK from 1979, utilising the Pimoroni VGA demo base.

![A picture of a Pimoroni VGA demo base with a Raspberry Pico (with headers) installed.](https://z80.timholyoake.uk/wp-content/uploads/2024/09/20240905_101721-1024x633.jpg)

## Documentation

Full user and systems documentation is provided in the [documentation subdirectory](https://github.com/psychotimmy/picomz-80k-beta/tree/main/documentation).

## Brief user notes

Ensure a microSD card containing one or more Sharp MZ-80K software (.mzf) files is installed in the slot on the Pimoroni VGA demo base. 

If you have successfully flashed either **picomz-80k.uf2** or **picomz-80k-diag.uf2** to the pico, when a USB keyboard (use picomz-80k.uf2) or terminal emulator (use picomz-80k-diag.uf2) plus VGA display is connected, you will see:

** MONITOR SP-1002 **

\*

on the screen.  

If the Pico's green led is flashing quickly (200ms between flashes), this means that a USB keyboard has not been connected or recognised via a terminal emulator. 

If the Pico's green led is flashing slowly (1s between flashes), then your microSD card cannot be read.

If either of these error conditions occur, the emulator will not display the monitor prompt until the problem is resolved. 

To find a file to load from the microSD card, use the F1 key to browse its contents. 

### This README was last updated on 27th October 2024.

# Pico MZ-80K beta

## A Sharp MZ-80K Emulator for the Raspberry Pico Microcontroller

A Raspberry Pico implementation of the Sharp MZ-80K sold in the UK from 1979, utilising the Pimoroni VGA demo base.

![A picture of a Pimoroni VGA demo base with a Raspberry Pico (with headers) installed.](https://z80.timholyoake.uk/wp-content/uploads/2024/09/20240905_101721-1024x633.jpg)

## Documentation

Full user and systems documentation is provided in the [documentation subdirectory](https://github.com/psychotimmy/picomz-80k-beta/tree/main/documentation).

## Brief user notes

If you have successfully installed either the **picomz-80k.uf2** or **picomz-80k-diag.uf2** file, then when a USB keyboard (use picomz-80k.uf2) or terminal emulator (use picomz-80k-diag.uf2) and VGA display is connected along with a microSD card containing Sharp MZ-80K software, you should see:

** MONITOR SP-1002 **

\*

on the screen. 

If the Pico's green led is flashing quickly (200ms between flashes), this means that a USB keyboard has not been connected or recognised via a terminal emulator. 

If the Pico's green led is flashing slowly (1s between flashes), then your microSD card cannot be read.

If either of these error conditions occur, the emulator will not display the monitor prompt on the VGA screen until the problem is resolved. 

### This README was last updated on 27th October 2024.

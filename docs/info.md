<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

A small programmable engine that drives and samples the I/O pins under firmware control. It has instructions for reading pins, writing pins, counting cycles and waiting for precise delays, so serial protocols such as UART, SPI and I2C run as firmware loaded after fabrication instead of as fixed logic.

Work in progress: the instruction set is still being designed, and the current build is the template's example adder.

## How to test

Load a protocol program, connect the target device to the protocol pins, then send or receive data through the engine. Exact pin assignments and loading steps will be documented once the instruction set is settled.

## External hardware

None yet.

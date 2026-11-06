# Alfred Vipin

I build embedded and RF hardware: boards, firmware, and the FPGA logic that sits between them. Most of what's here started as something I wanted to exist and couldn't buy.

Instagram: [@alf.rde](https://www.instagram.com/alf.rde/)

## Working on now

**[PeriR](https://github.com/nihcoc/PeriR)**
A software-defined radio that plugs into a Raspberry Pi CM4. An AD9364 handles the RF, an Artix-7 50T does the DSP and glue logic, and the whole thing talks to the Pi over PCIe 2.0. Written in Verilog, with Vivado for the build.

**STMflow**
A reflow oven controller on an STM32. I'm working on proper temperature profiling and the power stage. No repo yet.

## Finished

**[EchoSign](https://github.com/nihcoc/EchoSign)**
A glove that reads hand gestures and turns them into text and speech. KiCad board, Arduino, Bluetooth, and a small ML model for classification.

**[WCIS](https://github.com/nihcoc/WCIS)**
An ESP32 irrigation controller I built for my mom's garden. It covers the electronics, the enclosure, and the plumbing, and it's still running.

**[PCBCLOCK](https://github.com/nihcoc/PCBCLOCK)**
An analog-style clock made of an LED matrix on a custom PCB, driven by an STM32 and a 32.768 kHz TCXO for the RTC.

# Infrared Irradiance Probe

Copyright (c) 2022-2023 [Antmicro](https://www.antmicro.com)

![IR Irradiance Probe](/img/ir-irradiance-probe-vis.png)

## Overview

This project contains open hardware design files for a simple detector of infrared (IR) radiation.
It features two photodiodes with peak sensitivity of 900nm and 940nm, and signal-forming circuitry with adjustable gain.
The board can be used for measuring relative intensity of IR radiation and for probing dynamic illumination parameters of infrared LEDs and laser modules.

The design files were prepared in KiCad 6.x.

## Project structure 

The main directory contains KiCad PCB design files, a LICENSE and a README.
The remaining files are stored in the following directories: 

* `lib` - contains the component libraries, 
* `img` - contains graphics for this README,
* `assets` - contains visual assets used for showcasing this board on [Open Hardware Portal](https://openhardware.antmicro.com)

## Key features

* Two photodiodes for measuring IR irradiance (peak sensitivity @ 900nm for diode on top and 940nm for the bottom one)
* BNC connector for oscilloscope measurements
* Regulated sensitivity
* I2C single-channel interface for digital signal probing
* Selectable power source (USB-C / JST / external power supply)

## License

This project is licensed under the [Apache-2.0](LICENSE) license.

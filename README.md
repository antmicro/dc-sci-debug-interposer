# DC-SCI Debug Interposer

Copyright (c) 2026 [Antmicro](https://www.antmicro.com)

![](./img/dc-sci-debug-interposer.png)

## Overview

The open hardware Data Center Secure Control Interface (DC-SCI) Debug Interposer exposes IO interfaces provided by the DC-SCI rev.2.x.
It aids DC-SCM software development and server platform bringup. All single-ended signals are exposed on 2.54 mm headers to simplify the debugging setup. The on-board SOP-16 sockets provide an easy way for BIOS injection.
The DC-SCI Debug Interposer board also exposes two USB headers connected to PCIE_HPMROOT_5 (compatible with HPM Common Circuit Type 1 Design Specification).

## Key features

* Compatible with DC-SCM 2.x
* All single ended DC-SCI signals exposed on 2.54 mm headers
* 2x BIOS SPI Flash sockets
* 2-port USB controller connected to DC-SCI PCIE_HPMROOT_5 (assembly option)
* 68 x 90 mm (2.67 x 3.54 inch) PCB outline

## Project structure

The main directory contains KiCad PCB project files, the LICENSE, and this README, and the img directory contains graphics for this README.

## License

This project is licensed under the [Apache-2.0](LICENSE) license.

# DC-SCM Debug Interposer

Copyright (c) 2026 [Antmicro](https://www.antmicro.com)

![](./img/dc-sci-debug-interposer.png)

## Overview

This project contains open hardware design files for a Data Center Secure Control Modules (DC-SCM) interposer board exposing IO interfaces offered by Data Center Secure Control Interface (DC-SCI) rev.2.x.
This board aids DC-SCM software development and server platfroms bringup. All single ended signals are exposed on 2.54mm headers to simplify the debugging setup. Onboard SOP-16 sockets provide easy way for BIOS injection.
Board also exposses two USB headers connected to PCIE_HPMROOT_5 (compatible with HPM Common Circuit Type 1 Design Specification).
The design files were prepared in KiCad 10.

## Key features

* Comaptible with DC-SCM 2.x
* All single ended DC-SCI signals exposed on 2.54mm headers
* 2x BIOS SPI Flash sockets
* 2-port USB controller connected to DC-SCI PCIE_HPMROOT_5 (assembly option)
* 68 x 90 mm (2.67 x 3.54 inch) PCB outline

## Project structure

The main directory contains KiCad PCB project files, the LICENSE, and this README, and the img directory contains graphics for this README.

## License

This project is licensed under the [Apache-2.0](LICENSE) license.

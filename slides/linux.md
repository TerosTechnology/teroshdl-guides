---

header:  -[Index](./index.html#1)-
footer: Native Linux tools installation -- [pdf slides](./linux.pdf)  -- [TerosHDLdoc](https://terostechnology.github.io)
marp: true
title: Linux tools installation guide
description: How to install the tools natively in Linux
theme: uncover
paginate: true
_paginate: false

---

# Python dependencies
- Python: `sudo apt install python3.9`
- pip: `sudo apt install python3-pip`
- vunit, yosys, edalize: `pip3 install teroshdl`
- cocotb: `pip3 install cocotb`

---

# Simulators, linters, etc
- Download release of [OSS CAD Suite (YosysHQ)](https://github.com/YosysHQ/oss-cad-suite-build/releases) 
- Install and add environment to .bashrc:
```bash
tar -xvf <download_path/release_file>
rm <download_path/release_file>
echo "source <oss-cad-suite_path>/environment" >> ~/.bashrc
```
---
# Configure Yosys path 
- [Configure yosys tool](https://terostechnology.github.io/terosHDLdoc/configuration/tools.html#tools)
- Select yosys + GHDL as module in schematic viewer settings




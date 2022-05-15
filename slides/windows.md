---

header:  -[Index](./index.html#1)-
footer:  Native Windows tools installation --  [pdf slides](./windows.pdf)  -- [TerosHDLdoc](https://terostechnology.github.io)
marp: true
title: Windows tools installation guide
description: How to install the tools natively in windows
theme: uncover
paginate: true
_paginate: false

---

# Msys2
- Install: [Msys2.org](https://www.msys2.org/)
- Update: `pacman -Syu`

---

# Mingw_w64_EDA
- Msys2: `pacman -S mingw-w64-x86_64-eda`
  + Yosys (include GHDL plugin)
  + GHDL
  + Iverilog
  + GTKWave
  + Verilator
- Msys2: `make` , `git`

---

# Add paths to environment variables

- `<install_pah>/mingw32/bin`
- `<install_path>/usr/bin`

---

# Python3

- Download and install [python3](https://www.python.org/downloads/windows/)
- Install python teros dependencies `pip install teroshdl`
- Install cocotb `pip install cocotb`

---

# TerosHDL configuration

- [Configuration instructions](https://terostechnology.github.io/terosHDLdoc/configuration/tools.html)
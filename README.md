# RISC-V Reference SoC — VSD Tapeout Journey

**Author:** Aniket Singh  
**Contact:** aniketku123@gmail.com

---

## 0) What this repo is
This is my public notebook while I learn, build, and tapeout a small **RISC-V SoC** using an end-to-end open-source flow. You’ll find weekly notes, commands that actually worked on my machine, and links to the exact artefacts I generate.

> Goal: go from **RTL → GDSII** using community tooling and document every meaningful step.

---

## 1) Fast facts

- Program: **VSD – RISC-V Reference SoC Tapeout Program**
- Focus: Open-source EDA (simulation, synthesis, analysis, sign-off friendly checks)
- Toolchain theme: *portable, reproducible, and script-first*

---

## 2) Environment (Week-0 outcome)

I set up a clean toolchain and validated each tool is callable from PATH.

**Installed**
- **Icarus Verilog** (sim)
- **Yosys** (synth)
- **GTKWave** (waveform viewer)

**Quick checks**
```bash
iverilog -V
yosys -V
gtkwave --version

# Hi, I'm Chinmay 👋
**Hardware & Silicon Engineer** — VLSI/Mixed-Signal Design · Digital & PCB Hardware · ML-Hardware Systems
M.S. ECE @ Northeastern University (Hardware & Software for Machine Intelligence track, GPA 3.92/4.0) · Published 6G antenna researcher · Building across the stack from transistors to Verilog to ML accelerators.

📍 Seattle, WA &nbsp;|&nbsp; 🎯 Seeking Hardware/Silicon Engineering Internships & New-Grad Roles
&nbsp;|&nbsp; ✉️ [mahananda.c@northeastern.edu](mailto:mahananda.c@northeastern.edu)
&nbsp;|&nbsp; 🔗 [LinkedIn](https://linkedin.com/in/chinmaymahananda)

---

### ⚙️ What I work on
I design and verify hardware end-to-end — RTL, CMOS/digital circuits, PCBs — and build the classical & deep learning systems that run on top of them.

- **VLSI / Circuit Design:** CMOS & digital logic, schematic capture & simulation (Cadence Virtuoso, Spectre), MOSFET I–V characterization, DC/transient analysis, logical-effort sizing
- **Digital Design / HDL:** Verilog, RTL-to-GDSII ASIC flows (Yosys, OpenROAD, Sky130), parameterizable datapath design, self-checking testbenches
- **PCB / Embedded:** Schematic capture, layout & fabrication (KiCad, Altium), board bring-up & fault isolation, Embedded C
- **ML / Computer Vision:** PyTorch, CNN-based detection & embedding models (YOLO11, EfficientNet, transfer learning), classical ML for imbalanced classification (XGBoost, scikit-learn)

### 🔧 Tools & Languages
`Verilog` `Python` `Embedded C` `MATLAB` `SPICE` `Cadence Virtuoso` `Spectre` `LTspice` `CST Studio Suite` `KiCad` `Altium` `PyTorch` `scikit-learn` `XGBoost` `Git` `Icarus Verilog` `Logisim`

### 🚀 Featured Projects

| Project | Description |
|---|---|
| [**riscv-pipelined-core**](https://github.com/chinmaymahananda/riscv-pipelined-core) | 4-stage pipelined RV32I core (IF→EX→MEM→WB) with hazard forwarding, load-use stalling, and branch handling, verified bit-exact against a from-scratch golden model — carried through a full open-source ASIC flow (Yosys, OpenROAD, Sky130 PDK) to signed-off GDSII at 333MHz, zero DRC/LVS violations. A 500MHz stretch attempt was honestly documented as a failed timing closure rather than discarded. |
| [**systolic-mac-array**](https://github.com/chinmaymahananda/systolic-mac-array) | Parameterizable output-stationary systolic MAC array built bottom-up from a single MAC PE, extended into a full INT8 CNN inference accelerator (Conv1→Conv2→FC) with interlayer requantization. Traced a silent numerical drift on non-square input tiles to an edge case in the accumulator's saturation logic via waveform-level debugging, patched it, and re-verified bit-exact against a Python golden model across all 20 calibration samples. |
| **8-Bit ALU & 4:1 MUX** | 8-bit ALU built from a 1-bit cell in Logisim (AND/OR/XOR/NOR, two's-complement add/subtract, SLT); 4:1 MUX built and transient-verified in Cadence Virtuoso/Spectre across all four select states. |
| **PCB Fabrication & Bring-Up** | End-to-end board ownership — schematic capture, layout, fabrication, assembly, and functional test, bringing up power and signal nets on first power-on. Isolated a failed signal net to an improperly routed ground return via systematic continuity/probe testing rather than reflow guesswork. |
| **Pokémon TCG Card Recognition** | Team project (with Jeffrey Ma, Rayne Liu) — YOLO11-Nano OBB detector + EfficientNet-B0 triplet-loss embedding pipeline for sub-2-second recognition across 558 card embeddings, trained on a single RTX 3050 with augmentation to close the sim-to-real gap. |
| **Credit Card Fraud Detection** | Benchmarked 5 ML models on 284,807 transactions at 0.17% fraud prevalence — ~0.99 AUC-ROC via leak-free SMOTE and recall-prioritized threshold tuning under asymmetric misclassification cost. |

### 📄 Publication
**"Design of 6G Antenna"** — IJNRD 2024, Vol. 9 Issue 6 (ISSN 2456-4184), **first author** — millimeter- and micrometer-scale microstrip patch antennas for 6G THz-band communication, designed and simulated in CST Studio Suite. [Read it →](https://www.ijnrd.org/papers/IJNRD2406113.pdf)

### 🎓 Education
**M.S. Electrical & Computer Engineering** — Northeastern University (Seattle), GPA 3.92/4.0 — Sep 2025–Present

**B.E. Electronics & Communication Engineering** — Dr. Ambedkar Institute of Technology, Bengaluru — 2020–2024

Recipient of the **Seattle Campus Scholarship** and **International Impact Award** — competitive merit scholarships covering 30% of program tuition combined.

### 📜 Certification
**Emertxe Certified Embedded Professional (ECEP)** — Emertxe Information Technologies, 2025 — Linux Systems, Advanced C, Data Structures, Linux Internals & Networking, Micro Controllers, C++ Programming. [Verify →](https://certificate.emertxe.com/?id=24032F_023)

---
✉️ Reach me at [mahananda.c@northeastern.edu](mailto:mahananda.c@northeastern.edu) or on [LinkedIn](https://linkedin.com/in/chinmaymahananda)

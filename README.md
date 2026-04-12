<a id="readme-top"></a>
# About This Project

A compact USB‑C powered boost regulator board based on the MT3608 DC‑DC step‑up converter.

This board is designed for small embedded systems, robotics projects, and portable power applications requiring adjustable output voltage from a USB‑C input source.

---

# 📁 File Structure

<!-- TREEVIEW START -->
```bash
├── USB-C-Regulator.kicad_pcb   # PCB Layout
├── USB-C-Regulator.kicad_pro   # KiCad Project File
├── USB-C-Regulator.kicad_sch   # Schematic
└── README.md
```

## File Descriptions
* `kicad_pcb` - PCB Layout
* `kicad_sch` - Schematic
* `kicad_pro` - KiCad Project Configuration File
<!-- TREEVIEW END -->

---


# 🚀 Getting Started

Requirements
* KiCad 8 (recommended)

Open the `.kicad_pro` file using KiCad 8 to access the full project including schematic and PCB layout.

---

# 🔧 Board Feature

STM32 Board have below features
- [x] Hand-solder friendly footprint design
- [x] MT3608
- [x] USB-C Power Connector
- [x] Adjustable Output Voltage
- [x] Compact PCB Deisgn

---

# ⚙️ Technical Overview

* Input: 5V from USB‑C
* Converter IC: MT3608
* Topology: Boost (Step‑Up) DC‑DC
* Application: Portable power systems, embedded projects, battery-powered devices


# 🧠 Usage

* Step up 5V USB input to higher voltages (e.g., 9V / 12V)
* Power sensors, microcontrollers, or motor drivers
* Serve as a regulated power module in robotics projects
* Integrate into custom embedded designs

## Typical Workflow
1. Manufacture PCB
2. Solder components
3. Adjust output voltage via feedback resistors
4. Verify output with a multimeter before connecting load

⚠️ Always verify output voltage before powering 
sensitive electronics.

---

Got it ✅ — here is your BOM formatted exactly in that clean Markdown table style:

---

# 📦 Bill of Materials (BOM)

| Reference | Value | Package / Footprint | Qty |
|-----------|-------|--------------------|-----|
| C1, C3 | 22 µF Capacitor | 1206 SMD | 2 |
| L1 | 22 µH Inductor | 7.3×7.3 mm SMD | 1 |
| D1 | SS34 Schottky Diode | SMA (SMD) | 1 |
| J2 | 2‑Pin Output Header (2.54 mm) | Through‑hole | 1 |
| J3 | USB‑C Receptacle (Power Only, 6‑Pin) | SMD Type‑C | 1 |
| R2 | 2.2 kΩ Resistor | 1206 SMD | 1 |
| R3, R4 | 5.1 kΩ Resistor | 1206 SMD | 2 |
| RV1 | 100 kΩ Trimmer Potentiometer | Bourns 3296W (THT) | 1 |
| U1 | MT3608 Boost Converter IC | SOT‑23‑6 | 1 |

---

# License

MIT License

Feel free to use, modify, and distribute.

---

## 📫 Let's Connect

I'm always interested in collaborating on embedded systems projects, robotics competitions, or autonomous vehicle development!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077b5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/hang020713)

[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github)](https://github.com/hang020713)

[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:hang020713@gmail.com)

---

<p align="right">(<a href="#readme-top">Back to Top</a>)</p>
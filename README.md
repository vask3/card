# PCB Business Card

Hi! I am **Vasil Terziev**, a student and hardware enthusiast.

This repository contains the design and layout files for my custom printed circuit board (PCB) business card. Instead of handing out a standard paper card, I designed a physical, electronics-inspired card to share my contact details, demonstrate clean PCB design practices, and reflect my interest in embedded hardware and circuit design.

---

## Overview

The goal of this project is to combine practical contact information with thoughtful hardware aesthetics. Every trace, pad, and silkscreen label is arranged so the board looks intentional and clean while remaining easy to fabricate and assemble. Whether used as a conversation starter at events, hackathons, and university projects or kept as a small hardware piece, it serves as a compact representation of my work in electronics.

---

## Technical Details

- **Microcontroller / IC:** TQFP-32 package footprint, suitable for compact 32-pin microcontrollers or logic/controller ICs
- **Passive Components:** Surface-mount (SMD) resistors and capacitors for decoupling, pull-ups/pull-downs, or signal conditioning
- **Solder Mask & Silkscreen:** Blue solder mask paired with crisp, high-contrast white silkscreen text and markings
- **PCB Layout:** Carefully routed traces with clean geometry, consistent spacing, and a balanced front/back visual flow
- **Assembly Style:** Hand-solderable or reflow-friendly SMD footprint layout designed for clean solder joints and reliable component placement

### Board Views

<img width="772" height="473" alt="Screenshot 2026-11-05 202638" src="https://github.com/user-attachments/assets/bbe2281f-9029-4735-8550-f9172008ade5" />
<img width="1316" height="516" alt="image" src="https://github.com/user-attachments/assets/cd8643a8-d475-4d03-a294-d36967d150f6" />

---

## Repository Contents

- **CAD / Design Files:** Schematic and PCB layout source files
- **Fabrication Outputs:** Gerber and drill files ready for PCB manufacturing (where applicable)
- **Documentation:** Project overview, layout previews, and assembly notes

---

## Contact Information

- **GitHub:** [vask3](https://github.com/vask3)
- **Instagram:** [@terziev511](https://instagram.com/terziev511)
- **Website:** [vasko.blog](https://vasko.blog)
- **Email:** hello@vasko.blog

---

## How to Manufacture and Assemble

1. **Prepare Fabrication Files:** Download the Gerber files (or open the source project files and export Gerbers/drill files) from this repository.
2. **Order the Bare PCB:** Upload the Gerber archive to your preferred PCB manufacturer (such as JLCPCB, PCBWay, or another fab house) and select a blue solder mask with white silkscreen.
3. **Source Components:** Gather the required TQFP-32 IC and SMD resistors/capacitors according to your bill of materials (BOM).
4. **Populate & Solder:** Align the TQFP-32 package and passive components carefully, then solder them using a fine-tip soldering iron with flux, hot air rework station, or solder paste with reflow.
5. **Inspect & Clean:** Check all pins on the TQFP-32 footprint for solder bridges, verify pad wetting on passives, and clean excess flux residue before handling or sharing.

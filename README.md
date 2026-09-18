# ESD Monitor Protective Enclosure

A custom-designed 3D-printed enclosure developed to protect the FEITA-209-2 ESD Monitor from mechanical damage while improving maintainability through the use of replaceable banana connectors.

<img width="924" height="602" alt="image" src="https://github.com/user-attachments/assets/0acf538f-465b-44fc-8362-5c50d7efb8e0" />

---

## Project Overview

In a manufacturing environment, the FEITA-209-2 ESD Monitor was frequently damaged due to repeated insertion and removal of workstation and wrist strap banana plugs. Since the original banana ports are integrated into the monitor, mechanical wear often required replacement of the entire unit, increasing maintenance costs and equipment downtime.

To address this issue, a custom protective enclosure was designed and manufactured. The enclosure relocates the electrical connection to external replaceable banana connectors, allowing inexpensive consumable components to absorb mechanical wear while preserving the integrity of the original monitor.

---

## Objectives

- Protect the ESD monitor from mechanical damage.
- Extend the service life of the equipment.
- Reduce maintenance and replacement costs.
- Improve serviceability through replaceable connectors.
- Maintain full functionality and visibility of the monitor indicators.
- Create a solution suitable for additive manufacturing.

---

## Features

- Custom 3D-printed enclosure.
- Replaceable 4 mm banana connectors.
- Transparent front cover for continuous visibility of workstation and wrist strap status LEDs.
- Heat-set threaded inserts for durable assembly.
- Modular design for easy maintenance.
- Two-color printed top cover with integrated ESD warning label.

---

## Design Process

The enclosure was designed in **SolidWorks** following Design for Manufacturing (DFM) and Design for Additive Manufacturing (DfAM) principles.

The assembly consists of:

- Main Case
- Main Case Top
- Transparent Front Cover
- FEITA-209-2 ESD Monitor
- Replaceable Banana Connectors
- Heat-Set Inserts
- Socket Head Screws

Every component was modeled to ensure proper fit, ease of assembly, and reliable long-term operation in a manufacturing environment.

---

## Manufacturing

The enclosure was manufactured using FDM 3D printing.

### Materials

| Component | Material |
|----------|----------|
| Main Case | Black ESD-Safe PETG |
| Main Case Top | Black ESD-Safe PETG + Yellow PETG |
| Transparent Front Cover | Transparent PP |

Detailed printing parameters can be found in the **3D Printing Guide**.

---

## Repository Structure

```
CAD/
│── SolidWorks parts and assemblies

STL/
│── Printable models

Drawings/
│── Engineering drawings

Documentation/
│── Assembly instructions
│── 3D printing guide

Images/
│── Project renders and photographs
```

---

## Assembly

The enclosure is assembled using standard socket head screws and threaded heat-set inserts to provide a durable and serviceable structure. The replaceable banana connectors are internally wired to the ESD monitor using 22 AWG stranded copper wire, allowing worn connectors to be replaced without affecting the monitor itself. Detailed assembly drawings, the Bill of Materials, and manufacturing documentation are included in the Documentation folder.

---

## Results

The final design successfully protects the original ESD monitor from mechanical damage while transferring connector wear to inexpensive, replaceable banana connectors. This approach reduces maintenance costs, extends the service life of the equipment, and preserves full visibility of the workstation and wrist strap status LEDs. The enclosure also provides a cleaner, more robust appearance suitable for continuous use in a manufacturing environment.

<img width="1662" height="1247" alt="image" src="https://github.com/user-attachments/assets/23d5a0e5-2fc8-4b21-84c2-6725c5416e5e" />

---

## Software Used

The enclosure and all engineering drawings were designed using SolidWorks, while the STL files were prepared for manufacturing with PrusaSlicer. Version control and project documentation are managed through GitHub, ensuring an organized workflow and complete project traceability.

---

## Skills Demonstrated

- Mechanical Design
- CAD Modeling
- Product Improvement
- Design for Manufacturing (DFM)
- Design for Additive Manufacturing (DfAM)
- Rapid Prototyping
- FDM 3D Printing
- Engineering Documentation
- Technical Drawings
- Root Cause Analysis
- Problem Solving

---

## License

This project is provided for portfolio and educational purposes.

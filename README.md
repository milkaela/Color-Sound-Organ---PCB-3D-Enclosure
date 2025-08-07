# Color Sound Organ: PCB-3D-Enclosure
This project contains a complete design for a **sound-reactive light organ** with 3 channels (bass, mid, treble), using a PCB designed in KiCad and a custom 3D-printed case modeled in FreeCAD.
It is intended as a simple analog project for beginners or hobbyists who want to create visual effects based on audio input.


## 📦 Files Included

| File | Description |
|------|-------------|
| `3leduri.kicad_pcb` | PCB layout for the sound organ |
| `3leduri.kicad_sch` | Schematic diagram (circuit design) |
| `3leduri.kicad_pro` | KiCad project file |
| `3leduri.kicad_prl` | Layout view settings |
| `3leduri.xml`       | Netlist and BOM data export |
| `3leduri_bom_.csv`  | Bill of materials (CSV format) |
| `3leduri_bom_.xlsx` | Bill of materials (Excel format) |
| `fp-info-cache`     | Footprint cache used by KiCad |
| `cutie2.1.FCStd`    | 3D model of the custom case (FreeCAD format) |
---

## 🧠 Functional Description

The circuit detects three different frequency bands from an audio signal (low, mid, and high), and lights up a dedicated LED for each band accordingly.

- **Low frequencies (bass)** → LED 1
- **Mid frequencies** → LED 2
- **High frequencies (treble)** → LED 3

The PCB is designed to fit perfectly into the custom enclosure, with holes for LEDs and power input.

---

## 🛠 Tools and Technologies

- **KiCad** – for PCB design
- **FreeCAD** – for designing the case
- **3D Printer** – to fabricate the enclosure
- (Optional) **Audio signal source** – via jack, aux, or microphone

---

## 🖨️ 3D Printing Information

- Format: `.FCStd` (native FreeCAD file)
- Recommended slicer: Cura, PrusaSlicer, etc.
- Material: PLA or PETG
- Print time: ~2 hours
- No supports required

---

## ⚡ Usage & Testing

1. Assemble the circuit and solder components on the PCB
2. Insert the board into the 3D-printed case
3. Connect audio input (e.g. from your phone or laptop)
4. Play music — the 3 LEDs will respond to the audio spectrum

---

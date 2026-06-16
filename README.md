<div align="center">

⭐ **If you like this project, give the repository a star!** ⭐ <br>
------- 🇮🇹 **[Readme in Italiano][readme-it-url]** 🇮🇹 --------

<hr />
</div>

<div align="center">
<h2>FreeClock 3D Print</h2>

[![3D Printable](https://img.shields.io/badge/3D_Printable-FDM-orange?logo=3dprint&logoColor=white)](#)
[![No Supports](https://img.shields.io/badge/Supports-Not_needed-brightgreen)](#)
[![No AMS](https://img.shields.io/badge/AMS-Not_required-blue)](#)
[![Mirror](https://img.shields.io/badge/Print-Mirrorable-purple)](#)

<hr/>

<p><em>This model is part of the <a href="https://github.com/Matese-Makers/FreeClock"><strong>FreeClock</strong></a> project — an open source smart clock, easy to assemble, with a 3D-printable shell and a mobile app for management. Build yours and join the project!</em></p>

</div>

## 💡 Overview

FreeClock 3D Print contains all the **STL** files of the 3D-printable FreeClock shell, along with the source **CAD** file and the ready-to-slice **3MF** project.\
The case is designed to house the **FreeClock ESP32** electronics and was engineered to be simple to print and quick to assemble, even if you are new to 3D printing.

## ✨ Features

- 🚫 **Support-free** — every part is oriented to print without supports, reducing waste and post-processing
- 🧩 **Easy to print and assemble** — simple geometries and clean fits, it comes together in minutes
- 🎨 **Multi-color without AMS** — parts are split by color, so you can achieve a multi-color result even without a multi-material system
- 🪞 **Mirror printing** — components can be printed mirrored to customize the case orientation
- 📦 **Modular design** — the shell is split into multiple parts that print flat and fit together
- 🖨️ **FDM friendly** — designed for standard FDM printers with a 0.4 mm nozzle and common materials (PLA / PETG)

## 🗂️ Repository Structure

```
FREECLOCK-model/
├── 3MF/
│   └── freeclock.3mf          # Ready-to-slice project file
├── CAD/
│   └── FREECLOCK.f3z          # Fusion 360 source file
├── STL/
│   ├── a v3.stl               # Part A (variant v3)
│   ├── b v3.stl               # Part B (variant v3)
│   ├── buttom.stl             # Bottom base
│   ├── display cover.stl      # Display cover
│   ├── frame.stl              # Front frame
│   ├── main body.stl          # Main body / shell
│   └── retro.stl              # Rear panel
├── LICENSE
├── README.md
└── README.it.md
```

## 🧱 Components

All STL files are located in the [`STL/`](STL/) folder.

| File | Description |
|------|-------------|
| [`main body.stl`](STL/main%20body.stl) | Main body (shell) that houses the electronics |
| [`buttom.stl`](STL/buttom.stl) | Bottom base of the case |
| [`retro.stl`](STL/retro.stl) | Rear panel |
| [`frame.stl`](STL/frame.stl) | Front display frame |
| [`display cover.stl`](STL/display%20cover.stl) | Display cover / mask |
| [`a v3.stl`](STL/a%20v3.stl) | Decorative / structural part A (v3) |
| [`b v3.stl`](STL/b%20v3.stl) | Decorative / structural part B (v3) |

### 📐 CAD Source

The Fusion 360 source file is available in [`CAD/FREECLOCK.f3z`](CAD/FREECLOCK.f3z) for anyone who wants to modify or remix the design.

### 📦 3MF Project

A ready-to-slice 3MF project file is available in [`3MF/freeclock.3mf`](3MF/freeclock.3mf), pre-configured with part orientation and settings.

## 🚀 Getting Started

### What you need

- 🖨️ An **FDM 3D printer** (0.4 mm nozzle)
- 🧵 **PLA** or **PETG** filament (one or more colors of your choice)
- 🪛 A **slicer** (PrusaSlicer, OrcaSlicer, Cura or equivalent)

### Recommended print settings

> **Note:** these are tested starting values; adapt them to your printer and filament.

- **Layer height:** 0.2 mm
- **Perimeters (walls):** 3
- **Infill:** 15–20%
- **Supports:** ❌ none
- **Bed adhesion:** brim recommended for smaller parts

### How to print

1. **Download** or clone the repository:

   ```bash
   git clone https://github.com/Danzaywer/FREECLOCK-model.git
   cd FREECLOCK-model
   ```

2. **Option A — Use the 3MF:** Open [`3MF/freeclock.3mf`](3MF/freeclock.3mf) directly in your slicer for a pre-configured setup.

3. **Option B — Use the STLs:** Import the individual files from the [`STL/`](STL/) folder into your slicer, orient them flat (no supports needed), and slice.

4. **Print** each component and proceed with assembly.

### 🎨 Multi-color printing (without AMS)

Since the case is split into multiple parts, you can assign a different filament color to each component and achieve a multi-color result **without** needing an AMS / multi-material system: just print the parts separately with the desired filament.

### 🪞 Mirror printing

Components can be printed **mirrored** directly from the slicer, useful to flip the case orientation according to your needs.

## 📟 Compatible Electronics

- **FreeClock ESP32** — the board and display sit inside the shell
- For firmware and the management app, refer to the [main FreeClock project](https://github.com/Matese-Makers/FreeClock)

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a branch for your change (`git checkout -b feature/my-change`)
3. **Commit** your changes (`git commit -m 'Add my change'`)
4. **Push** the branch (`git push origin feature/my-change`)
5. **Open** a Pull Request

If you printed the case, share a photo or suggest improvements to the model! To report issues or propose new variants, [open an issue](https://github.com/Danzaywer/FREECLOCK-model/issues).

## 📄 License

This project is released under the **GNU Affero General Public License v3.0 (AGPL-3.0)**.

This means you are free to use, modify, and distribute these files, provided that:
- Any modified version made available over a network must be released under the same license
- The source code / original files must be made available to users who interact with the project over a network

For the full license text, see the [LICENSE](LICENSE) file.

<!--URL for Links-->
[readme-en-url]: README.md
[readme-it-url]: README.it.md

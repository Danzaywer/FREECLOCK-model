<div align= "center">

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

<a href="https://github.com/Matese-Makers/FreeClock">
<img alt="FreeClock Project" src="./gh-assets/FreeClock_project.png" width="200">
</a>

<p><em>This model is part of the <a href="https://github.com/Matese-Makers/FreeClock"><strong>FreeClock</strong></a> project — an open source smart clock, easy to assemble, with a 3D-printable shell and a mobile app for management. Build yours and join the project!</em></p>

</div>

## 💡 Overview

FreeClock 3D Print contains all the **STL** files of the 3D-printable FreeClock shell.\
The case is designed to house the **FreeClock ESP32** electronics and was engineered to be simple to print and quick to assemble, even if you are new to 3D printing.

## ✨ Features

- 🚫 **Support-free** — every part is oriented to print without supports, reducing waste and post-processing
- 🧩 **Easy to print and assemble** — simple geometries and clean fits, it comes together in minutes
- 🎨 **Multi-color without AMS** — parts are split by color, so you can achieve a multi-color result even without a multi-material system
- 🪞 **Mirror printing** — components can be printed mirrored to customize the case orientation
- 📦 **Modular design** — the shell is split into multiple parts that print flat and fit together
- 🖨️ **FDM friendly** — designed for standard FDM printers with a 0.4 mm nozzle and common materials (PLA / PETG)

## 🧱 Components

All STL files are located in the [`stl/`](stl/) folder. The numbers indicate the recommended print and assembly order.

| # | File | Description |
|---|------|-------------|
| 1 | [`1_box.stl`](stl/1_box.stl) | Main body (shell) that houses the electronics |
| 2 | [`2_bottom.stl`](stl/2_bottom.stl) | Bottom base of the case |
| 3 | [`3_top.stl`](stl/3_top.stl) | Top cover |
| 4 | [`4_back.stl`](stl/4_back.stl) | Rear panel |
| 5 | [`5_display_mask.stl`](stl/5_display_mask.stl) | Display mask |
| 6 | [`6_display_frame.stl`](stl/6_display_frame.stl) | Front display frame |

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
   git clone https://github.com/luigirossidev/freeclock-3dprint.git
   cd freeclock-3dprint
   ```

2. **Import** the STL files from the [`stl/`](stl/) folder into your slicer.
3. **Orient** the parts as previewed (they are already designed to print without supports) and run the slicing.
4. **Print** each component and proceed with assembly following the numeric order.

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

If you printed the case, share a photo or suggest improvements to the model! To report issues or propose new variants, [open an issue](https://github.com/luigirossidev/freeclock-3dprint/issues).

## 📄 License

This project is released under the **GNU Affero General Public License v3.0 (AGPL-3.0)**.

This means you are free to use, modify, and distribute these files, provided that:
- Any modified version made available over a network must be released under the same license
- The source code / original files must be made available to users who interact with the project over a network

For the full license text, see the [LICENSE](LICENSE) file.

<!--URL for Links-->
[readme-en-url]: README.md
[readme-it-url]: README.it.md

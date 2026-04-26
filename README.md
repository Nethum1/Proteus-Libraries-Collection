# 🔌 Proteus-Libraries-Collection

<div align="center">

![Proteus](https://img.shields.io/badge/Proteus-Design%20Suite-blue?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAyTDIgN2wxMCA1IDEwLTV6TTIgMTdsOSA1IDktNXYtNWwtOSA1LTktNXoiLz48L3N2Zz4=)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

**A curated collection of custom Proteus libraries for electronics simulation and PCB design.**

*Built for engineers, students, and hobbyists who want ready-to-use, accurate component models.*

</div>
---

## 📖 Table of Contents

- [About This Repository](#-about-this-repository)
- [What's Inside](#-whats-inside)
- [Getting Started](#-getting-started)
- [How to Install Libraries](#-how-to-install-libraries)
- [Library Structure](#-library-structure)
- [Component Categories](#-component-categories)
- [Usage Guide](#-usage-guide)
- [Contributing](#-contributing)
- [Notes & Tips](#-notes--tips)
- [License](#-license)
- [Author](#-author)

---
## 🧠 About This Repository

This repository is a growing collection of **custom Proteus ISIS/ARES libraries** — including schematic symbols, PCB footprints, and SPICE simulation models — assembled and maintained for use in electronics design and embedded systems projects.

Whether you're prototyping a microcontroller circuit, designing a power supply, or building a sensor interface, these libraries are designed to **save time** and **improve simulation accuracy** inside Proteus Design Suite.

> **Why this repo?**  
> Official Proteus libraries don't always include the latest ICs, sensors, and modules. This collection fills that gap with community-tested, project-ready parts.

---
## 📦 What's Inside

| File Type | Extension | Description |
|-----------|-----------|-------------|
| Schematic Symbol Library | `.LIB` | Component symbols for ISIS schematic editor |
| PCB Footprint Library | `.LIB` | Land patterns for ARES PCB layout |
| SPICE Models | `.MDF` / `.SDF` | Simulation data for accurate circuit behavior |
| Shape Library | `.SF` | Custom 3D or 2D component shapes |

---

## 🚀 Getting Started

### Prerequisites

Before using these libraries, make sure you have:

- ✅ **Proteus Design Suite** (v7.x, v8.x, or newer) installed
- ✅ Basic understanding of Proteus Library Manager
- ✅ Git installed (to clone this repo) — *or* download as ZIP

### Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/proteus-libraries.git
```

Or click the green **`Code`** button → **Download ZIP** and extract it.

---

## 🛠️ How to Install Libraries

Follow these steps carefully to add libraries to Proteus:

### Method 1 — Manual Copy (Recommended)

1. **Copy** the `.LIB`, `.MDF`, or `.SDF` files from this repo.
2. **Paste** them into your Proteus library folder:
   ```
   C:\ProgramData\Labcenter Electronics\Proteus X Professional\LIBRARY\
   ```
   > ⚠️ The path may vary depending on your Proteus version and Windows installation.

3. **Restart Proteus** — the new components will now appear in the device library picker.

### Method 2 — Library Manager (ISIS)

1. Open **Proteus ISIS**.
2. Go to **Library → Pick Devices/Symbol**.
3. Click **Library Manager**.
4. Select **Add/Remove Library Files**.
5. Browse to the `.LIB` files from this repository and add them.

### Method 3 — Append to Existing Library

If you want to merge components into an existing `.LIB` file:

1. Open **Library Manager** in ISIS.
2. Select the target library.
3. Use **Import** to pull in components from the new `.LIB` file.

---

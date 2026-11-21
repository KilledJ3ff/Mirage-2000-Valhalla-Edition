# Mirage 2000 — Valhalla Edition

##### Dassault Mirage 2000 for FlightGear — Valhalla Edition fork of FGMEMBERS/Mirage-2000 (Helijah).

[![FlightGear](https://img.shields.io/badge/FlightGear-2020.3%2B-blue.svg)]()
[![FDM](https://img.shields.io/badge/FDM-JSBSim-green.svg)]()
[![License](https://img.shields.io/badge/License-GPL--2.0-red.svg)]()

> **Valhalla Edition** — fork of FGMEMBERS/Mirage-2000 maintained under **Projeto Valhalla** (ala NEXUS).

---

## Aircraft Description

The **Dassault Mirage 2000** is a French fourth-generation multirole fighter developed from the Mirage III delta-wing family. It introduced fly-by-wire controls, a glass cockpit and the Snecma M53 engine, and remains in service with several air forces (France, UAE, India, Greece, etc.).

## Variants in this package

| Variant | Set file | Notes |
|---------|----------|-------|
| Mirage 2000-5 | `m2000-5-set.xml` | Single-seat multirole |
| Mirage 2000-5B | `m2000-5B-set.xml` | Two-seat trainer |
| Mirage 2000-5B backseat | `m2000-5B-backseat-set.xml` | Backseat view |
| Mirage 2000D | `m2000D-set.xml` | Strike variant |

## Simulator Capabilities

| System | Status | Details |
|--------|--------|---------|
| JSBSim FDM | ✅ | Richard Harrison aero model |
| FBW / AFCS / Autopilot | ✅ | Josh Davidson FCS/FBW/AP |
| Canvas HUD | ✅ | `Nasal/HUD/`, `Nasal/CANVAS/` |
| MFD pages | ✅ | `Nasal/MFD/` — PA docs in `Docs/` |
| Weapons | ✅ | AM39 Exocet, AS-30L, ASMP, APACHE, GBU-12, CC422 cannon pod, BAP-100, AS-37 |
| Multiplayer | ✅ | `Nasal/MP.nas` |
| Systems (hydraulics, electrics, ECS, fuel) | ✅ | Improved since 2020-09 |

## Installation

1. Clone into your FlightGear aircraft directory:
   ```bash
   git clone https://github.com/KilledJ3ff/Mirage-2000-Valhalla-Edition.git Mirage-2000
   ```
2. Add the parent folder to **Additional Aircraft Directories** in the launcher.
3. Select **Mirage 2000** and pick a variant.

---

## Repository Structure

```text
Mirage-2000/
├── m2000-*-set.xml          # Variant sets (2000-5, 5B, 5B-backseat, D)
├── Models/                  # Airframe, cockpit, missiles models
├── Nasal/                   # HUD, MFD (Canvas), FCS, weapons, MP
├── Missiles/                # AM39, AS30L, ASMP, APACHE, GBU-12, ...
├── Dialogs/  DualControl/   # GUI & dual-control
├── Docs/                    # MFD-PA manual, Nasal doc, dev help
└── README.md / ROADMAP.md / CHANGELOG.md
```

---

## Development

- **Roadmap:** [ROADMAP.md](ROADMAP.md)
- **Changelog:** [CHANGELOG.md](CHANGELOG.md) (upstream history in `CHANGELOG.txt`)
- **Upstream:** https://github.com/FGMEMBERS/Mirage-2000

## Credits

- **Valhalla Edition fork** — **Killed J3ff** (Projeto Valhalla — NEXUS)
- **Original Mirage 2000** — Helijah (3D), 5H1N0B1 (weapons/systems), Richard Harrison (FDM), Leto, Josh Davidson (FCS/FBW/AP), hardball, Domokos Juttner, F-Sig, J Maverick 16, legoboyvdlp, onox, ravenclaw_007, Niall "Salmon" Roe, Marsdolphin, R. "Wolf" Roquefort, Rick Gruber-Riemer

## License

GPL-2.0 — see `COPYING`.

---

*Original readmes kept: `README.txt`, `Read-Me.txt`, `English/`, `Francais/`*
# ROADMAP — Mirage 2000 Valhalla Edition

> Fork of FGMEMBERS/Mirage-2000 (Helijah), maintained under **Projeto Valhalla (NEXUS)**.
> **Status Convention:** ✅ = Implemented | 🟡 = Partial | ⬜ = Planned

---

## Phase Overview

| Phase | Focus | Status | Notes |
|-------|-------|--------|-------|
| **P0 — Fork Baseline** | Fork + rename to Valhalla Edition | ✅ Done | This repo |
| **P1 — Sync local build** | 466 modified files synced | ✅ Done | Missiles, Nasal, CHANGELOG |
| **P2 — Variants** | 2000-5, 5B, 5B-backseat, D | ✅ Done | 4 set files |
| **P3 — Avionics** | Canvas HUD + MFD | ✅ Done | Since 2020-09 |
| **P4 — FCS/FBW/AP** | Fly-by-wire, autopilot | ✅ Done | Josh Davidson model |
| **P5 — Weapons depth** | Missile seekers, SMS pages | 🟡 | 466 files synced; seeker tuning ongoing |
| **P6 — Systems** | Hydraulics/electrics/ECS/fuel | ✅ basic, depth ⬜ | |
| **P7 — Valhalla integration** | VLH liveries, DiEV scenarios | ⬜ | With TACTICAL/DiEV |

---

## Detailed Tracking

### Weapons (`Missiles/`)
AM39 Exocet · APACHE · AS-37 Armat/Martel · AS-30L · ASMP/ASMP-300 · BAP-100 · CC422 cannon pod · GBU-12 — models present; guidance depth varies per missile.

### Avionics
| Item | Status |
|------|--------|
| Canvas HUD | ✅ |
| MFD (PA) | ✅ — docs in `Docs/m2000-MFD-PA.pdf` |
| FBW / AFCS | ✅ |
| MP datalink | ✅ |

---

## Links
- Changelog: [CHANGELOG.md](CHANGELOG.md) + upstream `CHANGELOG.txt`
- Upstream: https://github.com/FGMEMBERS/Mirage-2000
- FlightGear Wiki: https://wiki.flightgear.org/

---

*Last updated: 2026-11-21*
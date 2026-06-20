<div align="center">

<img src="https://raw.githubusercontent.com/Galusz/sensmos-protocol/main/logo.png" alt="Sensmos" height="96">

# Sensmos

**A decentralized sensor network that measures the real world, puts it on a live map, and rewards real physical contribution with the GALU token.**

[![Website](https://img.shields.io/badge/website-sensmos.com-1FCFB4?style=flat-square)](https://sensmos.com)
[![Live map](https://img.shields.io/badge/live-map-1FCFB4?style=flat-square)](https://sensmos.com/map/)
[![Epoch explorer](https://img.shields.io/badge/epoch-explorer-1FCFB4?style=flat-square)](https://sensmos.com/epochs/)
[![GALU on Polygon](https://img.shields.io/badge/GALU-live%20on%20Polygon-8247E5?style=flat-square)](https://polygonscan.com/token/0x9d797D0E642D9EADdbDbD34ACFCFd07bf0043c6C)

</div>

---

Cheap **ESP32** nodes measure power quality, signal and climate on *your* street, sign every reading on-chip, publish to a shared live map, and earn **GALU** — an on-chain, physically-backed reward token. No cloud lock-in: the firmware and the Home Assistant integration run fully local.

### Explore

- 🌐 **Site** — https://sensmos.com
- 🗺️ **Live map** — https://sensmos.com/map/
- 📈 **Epoch explorer** — every reward epoch, on-chain and verifiable — https://sensmos.com/epochs/
- 📄 **Whitepaper** — [English](https://github.com/Galusz/sensmos-protocol/blob/main/WHITEPAPER.md) · [Polski](https://github.com/Galusz/sensmos-protocol/blob/main/WHITEPAPER.pl.md)
- 💬 **Discord** — https://discord.gg/ukea386Kqx

### Open-source repositories

| Repo | What it is | Stack |
|------|------------|-------|
| [sensmos-firmware](https://github.com/Galusz/sensmos-firmware) | ESP32 node firmware — sensors, edge script engine, signed batches | C++ / Arduino |
| [sensmos-app](https://github.com/Galusz/sensmos-app) | Mobile app — self-custody wallet, BLE onboarding, live map | Flutter |
| [sensmos-homeassistant](https://github.com/Galusz/sensmos-homeassistant) | Home Assistant integration (HACS) — both ways, fully local | Python |
| [sensmos-protocol](https://github.com/Galusz/sensmos-protocol) | GALU token, on-chain reward pool, emission model + whitepaper | Solidity |

GALU runs on **Polygon** · contract [`0x9d79…3c6C`](https://polygonscan.com/token/0x9d797D0E642D9EADdbDbD34ACFCFd07bf0043c6C)

<sub>Built by Wojciech Gałuszewski — full-stack (Node.js / TypeScript · C++ · Flutter).</sub>

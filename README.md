# TESAIoT Game Console — Firmware Releases

Official firmware releases for the **TESAIoT AI-Game console**
(PSoC™ Edge E84 · KIT_PSE84_AI SoM + QWA309 base board).

## Install

Flash the latest `app_combined.hex` from the [Releases](../../releases) page
using the TESAIoT Programmer.

Each release ships:

| Asset | Purpose |
|---|---|
| `app_combined.hex` | Combined tri-core firmware image (CM33_S + CM33_NS + CM55) |
| `manifest.json` | Firmware identity manifest — SKU, version, UUID, CRC-32, SHA-256 |

The firmware embeds a verifiable identity record (SKU `TESAIOT-CLAW-AI-GAME`)
readable by the TESAIoT Programmer.

---

© TESAIoT · Advance Innovation Centre (AIC)

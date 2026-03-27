# ⚡ Lightning Candy Machine
→ Candy machine triggered with a Bitcoin Lightning payment, built with an ESP32, BTCPay Server + Blink.

![License: MIT](https://img.shields.io/badge/License-MIT-orange.svg)
![Hardware: ESP32](https://img.shields.io/badge/Hardware-ESP32-green.svg)
![Network: Lightning](https://img.shields.io/badge/Network-Lightning-yellow.svg)
![Platform: BTCPay](https://img.shields.io/badge/Platform-BTCPay%20Server-green.svg)

- **Level:** Intermediate
- **Estimated time:** 2-3 hours
- **Use cases:** Bitcoin events, bitcoin stores, kids activities, Lightning demos, conference booths

## How it works

1. A Lightning invoice is displayed on screen or printed
2. The payment is detected by BTCPay Server + Blink
3. The ESP32 receives the payment event via WebSocket
4. The ESP32 activates a relay connected to the candy machine

## Hardware

**Electronic components**
- ESP32-WROOM-32 microcontroller
- 5V relay module with optocoupler
- Candy machine with electronic dispenser
- Dupont cables: Male/Male and Male/Female
- 5V USB power supply or Li-Po battery
- Micro-USB cable

**Tools**
- Soldering iron + tin (or Dupont connectors)
- Screwdriver
- Multimeter (recommended)
- Adhesive tape / glue

## License

MIT © 2026 Ezmo

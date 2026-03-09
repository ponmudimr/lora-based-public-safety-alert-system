# lora-based-public-safety-alert-system
A LoRa-based solar-powered RF public safety alert system using ESP32 for disaster alerts and emergency communication between authorities and remote villages.
# Solar-Powered Zoned RF Public Safety Alert System

## Overview

This project develops a decentralized RF-based public safety communication system using ESP32 and LoRa modules. The system enables authorities to send emergency alerts to remote villages and allows villagers to send panic signals back.

The system is designed to operate in remote areas without internet connectivity and can be powered using solar energy.

---

## Objective

- Provide reliable emergency alerts to remote communities
- Enable two-way communication between villages and authorities
- Work without cellular networks
- Use long-range LoRa RF communication
- Operate using renewable solar power

---

## Hardware Used

- ESP32 Development Board
- LoRa SX1278 RF Module
- Antenna
- Jumper Wires
- Breadboard

---

## System Architecture

Authority Node (ESP32 + LoRa)
↓
RF Transmission
↓
Village Node (ESP32 + LoRa)

Village nodes activate warning systems and can send panic alerts back to authorities.

---

## Day 1 Progress

Today we completed the basic hardware setup and initial testing.

### Work Done

- Connected ESP32 with LoRa SX1278 module
- Configured SPI communication between ESP32 and LoRa module
- Uploaded LoRa test program
- Verified ESP32 boot and serial communication
- Debugged wiring connections

### Result

ESP32 successfully detected the LoRa module and initialized RF communication.

### Issues Faced

- Initial LoRa initialization failure
- Incorrect wiring connections

### Fix

Corrected SPI wiring and verified 3.3V power supply.

---

## Development Roadmap

| Day | Task | Status |
|----|------|-------|
| Day 1 | ESP32 + LoRa hardware connection | ✅ Completed |
| Day 2 | LoRa transmitter code | ⏳ |
| Day 3 | LoRa receiver node | ⏳ |
| Day 4 | Panic button communication | ⏳ |
| Day 5 | LED + siren alert system | ⏳ |
| Day 6 | Solar power integration | ⏳ |

---

## Team

Team Name: **404_ERROR**  
Team ID: **100234**

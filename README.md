🌍 LoRa-Based Solar Powered Public Safety Alert System

A LoRa-based solar-powered RF public safety alert system using ESP32 to provide disaster alerts and emergency communication between authorities and remote villages without relying on cellular or internet connectivity.

---

📌 Overview

Many remote villages lack reliable communication infrastructure during disasters such as floods, forest fires, or landslides. This project proposes a long-range RF communication system using LoRa technology to send emergency alerts from authorities to villages and allow villagers to send panic alerts back.

The system is designed to operate in low-power environments using solar energy, making it suitable for remote and disaster-prone regions.

---

🎯 Objectives

- Provide reliable emergency alerts to remote communities
- Enable two-way communication between authorities and villages
- Work without cellular networks or internet
- Use long-range LoRa RF communication
- Operate using solar power for sustainability

---

🛠 Hardware Components

- ESP32 Development Board
- LoRa SX1278 RF Module (433 MHz)
- Antenna
- Breadboard
- Jumper Wires
- Panic Button
- LED / Siren Alert System
- Solar Panel (for field deployment)

---

🏗 System Architecture

Authority Control Unit
(ESP32 + LoRa + Dashboard)

⬇ LoRa RF Communication

Village Alert Node
(ESP32 + LoRa + Siren + Panic Button)

Working Principle

1. Authorities send emergency alerts through the Officer Control Dashboard.
2. The ESP32 transmitter sends RF packets using the LoRa SX1278 module.
3. Village nodes receive the signal and activate:
   - Warning LED
   - Siren Alert
4. Villagers can press the panic button to send emergency signals back to the authority node.

---

📅 Development Progress

Day 1 – Hardware Setup

Work Done

- Connected ESP32 with LoRa SX1278 module
- Configured SPI communication
- Uploaded LoRa test firmware
- Verified ESP32 boot and serial communication

Result

ESP32 successfully detected the LoRa module and initialized RF communication.

Issues Faced

- LoRa initialization failure
- Incorrect SPI wiring

Fix

Corrected SPI connections and ensured 3.3V power supply.

---

Day 2 – Officer Dashboard Development

Work Done

- Designed Officer Control Dashboard
- Implemented alert transmission system
- Added zone-based village alert control
- Integrated LoRa transmission commands

Dashboard Features

- Send emergency alerts
- Select alert zones
- Monitor LoRa connection status
- Trigger alerts such as:
  - Flood warning
  - Forest fire alert
  - Emergency evacuation
  - Medical emergency

Result

Officer dashboard successfully sends alert packets via LoRa to village nodes.

---

📊 Development Roadmap

Day| Task| Status
Day 1| ESP32 + LoRa hardware setup| ✅ Completed
Day 2| Officer dashboard and transmitter| ✅ Completed
Day 3| Village receiver node| ⏳ In Progress
Day 4| Panic button communication| ⏳
Day 5| LED + Siren alert system| ⏳
Day 6| Solar power integration| ⏳

---

🚀 Applications

- Disaster warning systems
- Forest monitoring alerts
- Flood warning systems
- Rural emergency communication
- Military field communication

---

🔮 Future Improvements

- GPS-based village location tracking
- Mesh LoRa network for larger coverage
- Mobile app for authority dashboard
- Integration with disaster monitoring sensors
- AI-based disaster prediction alerts

---

👥 Team

Team Name: 404_ERROR
Team ID: 100234

---

📡 Technology Stack

- ESP32
- LoRa SX1278
- Embedded C / Arduino Framework
- RF Communication
- Solar Power Systems

---

📜 License

This project is developed for research and innovation purposes.
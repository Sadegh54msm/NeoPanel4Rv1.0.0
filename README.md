 NeoPanel4R - Smart IoT Relay Controller

![NeoPanel4R Dashboard](images/dashboard-screenshot.png)

## 🎯 Features

- ✅ 4 Relay Outputs with individual control
- ✅ 2 DHT22 Temperature & Humidity sensors
- ✅ Local web dashboard (works offline)
- ✅ Cloud synchronization
- ✅ Scheduling with second-precision
- ✅ Thermostat mode
- ✅ Momentary/pulse mode
- ✅ OTA firmware updates
- ✅ Dual WiFi (AP + STA)
- ✅ Responsive web interface

## 📦 What's Included

- Complete ESP8266 firmware source code
- Pre-compiled binary (.bin)
- PHP server-side scripts
- MySQL database schema
- Full documentation
- Wiring diagrams

## 🚀 Quick Start

See [INSTALLATION.md](docs/INSTALLATION.md)

## 📖 Documentation

- [Installation Guide](docs/INSTALLATION.md)
- [User Manual (English)](docs/USER-MANUAL-EN.md)
- [User Manual (فارسی)](docs/USER-MANUAL-FA.md)
- [API Reference](docs/API-REFERENCE.md)
- [Troubleshooting](docs/TROUBLESHOOTING.md)

## 🔧 Requirements

### Hardware
- ESP8266 (NodeMCU or Wemos D1 Mini)
- 4-Channel Relay Module (Active LOW)
- 2x DHT22 Sensors
- 5V Power Supply

### Software
- Arduino IDE 1.8+ or PlatformIO
- PHP 7.4+ with PDO
- MySQL 5.7+ or MariaDB

## 📞 Support

- Email: support@iot-smart.ir
- Email: m.msm30@gmail.com
- Website: https://iot-smart.ir

## 📜 License

This is proprietary software. See [LICENSE.md](LICENSE.md)

---
© 2025 Mohammad Sadegh Moridi. All rights reserved.


---

## 🚀 Quick Start

### 1. Hardware Setup
Connect components according to [wiring diagram](hardware/wiring-diagram.png)

### 2. Upload Firmware
Open firmware/NeoPanel4R_v1.0.0.ino in Arduino IDE
Select Board: NodeMCU 1.0
Click Upload

### 3. Connect
Connect to WiFi: NeoPanel4R_AP
Password: 12345678
Open: http://192.168.4.1
Login: admin / 12345678


**📖 Full guide: [docs/INSTALLATION.md](docs/INSTALLATION.md)**

---

## 🔧 Hardware Requirements

| Component | Quantity | Notes |
|-----------|----------|-------|
| ESP8266 NodeMCU | 1 | Or Wemos D1 Mini |
| 4-Channel Relay | 1 | Active LOW |
| DHT22 Sensor | 2 | Temperature & Humidity |
| 5V Power Supply | 1 | 2A recommended |
| Jumper Wires | ~15 | |

**💰 Estimated cost: $15-25**

---

## 📌 Pin Configuration

| ESP8266 Pin | Function |
|-------------|----------|
| D1 (GPIO5) | Relay 1 - Scheduling |
| D2 (GPIO4) | Relay 2 - Momentary |
| D5 (GPIO14) | Relay 3 - Thermostat |
| D6 (GPIO12) | Relay 4 - Auxiliary |
| D7 (GPIO13) | DHT22 Sensor 1 |
| D8 (GPIO15) | DHT22 Sensor 2 |

---

## 📖 Documentation

| Document | Description |
|----------|-------------|
| [INSTALLATION.md](docs/INSTALLATION.md) | Step-by-step setup guide |
| [USER-MANUAL-EN.md](docs/USER-MANUAL-EN.md) | English user manual |
| [USER-MANUAL-FA.md](docs/USER-MANUAL-FA.md) | Persian user manual |
| [API-REFERENCE.md](docs/API-REFERENCE.md) | Cloud API documentation |
| [TROUBLESHOOTING.md](docs/TROUBLESHOOTING.md) | Common issues & fixes |

---

## 🛠️ Technical Specifications

| Parameter | Value |
|-----------|-------|
| Processor | ESP8266 @ 80MHz |
| Flash | 4MB |
| WiFi | 802.11 b/g/n |
| Relay Capacity | 10A @ 250VAC |
| Temp Range | -40°C to 80°C |
| Temp Accuracy | ±0.5°C |
| Cloud Sync | Every 10 seconds |
| Local Response | < 100ms |

---

## 📞 Support

- 📧 Email: support@iot-smart.ir
- 🌐 Website: https://iot-smart.ir

---

## 📜 License

This is **commercial software**. See [LICENSE.md](LICENSE.md) for terms.

---

## 👨‍💻 Author

**Mohammad Sadegh Moridi**

- Website: [iot-smart.ir](https://iot-smart.ir)
- Email: info@iot-smart.ir
- Email: m.msm30@gmail.com
---

© 2025 Mohammad Sadegh Moridi. All rights reserved.

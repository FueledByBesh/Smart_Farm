
# 🌱 Smart Farm - IoT Project
   
## Overview

**Smart Farm** is an IoT-based environment designed to monitor and control various aspects of farming using sensors and actuators. Constructed using wooden boards as a structural skeleton, the system uses an ESP32 MAX as its central controller. The system gathers environmental data through sensors and responds with actuators — all manageable via a mobile application.

Our goal was to simulate a self-regulating farm environment capable of reacting intelligently to changing conditions like soil dryness, light levels, motion detection, and temperature.

---

## 🧠 System Architecture

### 🏗️ Physical Setup

- **Frame:** Wooden boards, screws, and nuts to form the farm’s skeleton.
- **Controller (Brain):** ESP32 MAX microcontroller.
- **Power Supply:**
  - Solar Panel
  - AA Batteries (in dreams)

---

## 🔍 Sensors Used

| Sensor               | Purpose                               |
| -------------------- | ------------------------------------- |
| PIR Motion Sensor    | Detects motion within the environment |
| DHT11                | Measures temperature and humidity     |
| Photoresistor (LDR)  | Detects light levels                  |
| Water Sensor         | Detects presence of water             |
| Touch Sensor         | Detects physical contact/touch        |
| Soil Moisture Sensor | Monitors soil moisture levels         |

---

## ⚙️ Actuators Used

| Actuator               | Function                                |
|------------------------|------------------------------------------|
| Blue LED Module        | Status indicator                         |
| RGB LED                | Multi-color lighting for various alerts  |
| Motor                  | General mechanical control               |
| Water Pump             | Waters the soil when dry                 |
| Servo SG90 (9G)        | Controls small mechanical actions        |
| 5V Relay Module        | Controls high-power components safely    |
| Piezo Buzzer (P-Buzzer)| Sound alerts                             |
| OLED Display Module    | Displays real-time sensor data/status    |

---

## 📱 Mobile App Integration

- Real-time monitoring of sensor data (e.g., temperature, humidity, motion).
- Manual and automatic control of actuators.
- User interface for toggling modes, viewing logs, and managing alerts.
- Works using Wifi

---

## 📸 Visuals

![[photo_2025-05-15 13.40.52.jpeg]]

![[photo_2025-05-15 13.40.51.jpeg]]



---

## 🐄🐮 Authors

- [Olzhas Akimbay]
- [Olzhas Yergali]

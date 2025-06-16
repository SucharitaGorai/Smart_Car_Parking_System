# Smart_Car_Parking_System
# 🚗 Car Parking Slot Monitoring System using Raspberry Pi

This project is a smart **Car Parking System** developed using **Raspberry Pi**, which monitors the occupancy status of parking slots and displays it on an **LCD screen**, as well as publishes the real-time data to an **MQTT broker**.

---

## 📌 Features

- Detects car presence using IR sensors connected to GPIO pins.
- Displays slot status (`Free` or `Parked`) on a 16x2 LCD.
- Sends MQTT messages to a broker (`slot1` and `slot2` topics).
- MQTT-compatible for integration with cloud dashboards or mobile apps.
- Displays welcome screen on startup.

---

## 🛠️ Hardware Requirements

- Raspberry Pi (any model with GPIO support)
- 16x2 LCD Display (HD44780 compatible)
- IR Sensors (2 units)
- Jumper wires and Breadboard
- Internet connection on Raspberry Pi

---

## 🔧 Software/Library Requirements

- Python 3
- `RPi.GPIO` for GPIO control
- `paho-mqtt` for MQTT communication

To install required libraries:

```bash
pip install paho-mqtt

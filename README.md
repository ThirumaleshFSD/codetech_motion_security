# codetech_motion_security
# 🛡️ IoT Motion Detection Security System

This IoT project uses a PIR sensor to detect motion and triggers alerts via LED, buzzer, and serial messages. It serves as a basic prototype for home or office security.

## 🚀 Getting Started

### ✅ Hardware Required

- Arduino Uno / NodeMCU / ESP32
- PIR Motion Sensor
- LED
- Buzzer
- Breadboard & Jumper Wires
- USB Cable

---

## 🔌 Circuit Connections

| Component   | Arduino Pin |
|-------------|-------------|
| PIR Sensor  | D2          |
| LED         | D3          |
| Buzzer      | D4          |

*Make sure to connect PIR VCC to 5V and GND properly.*

---

## 📜 Code Features

- Detects motion using PIR sensor
- Activates LED and buzzer as an alarm
- Sends alerts via Serial Monitor

---

## 🛠️ Setup Instructions

1. Open `motion_security.ino` in Arduino IDE
2. Select correct board & port (e.g., Arduino Uno)
3. Upload the sketch
4. Open Serial Monitor at **9600 baud**
5. Observe alerts when motion is detected

---

## 🖼️ Diagram

![Motion Sensor Circuit](circuit/motion_diagram.png)

*(You can add a Fritzing diagram here)*

---

## 📂 Project Structure


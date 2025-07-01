# 🛡️ Guardian Gear – Smart Helmet Safety System

**Guardian Gear** is an IoT-powered smart helmet system designed for two-wheeler riders. It enforces safety by detecting helmet usage and monitoring for falls or accidents. If an impact is detected, the system sends alerts via a Bluetooth-connected mobile app. It also warns the rider with an audible buzzer if the helmet isn't worn when the ride begins. The mobile app allows emergency contact management, alert control, and cloud-based data storage. This system aims to improve road safety through low-cost, wearable, and connected technology.

---

## 🚀 Features

- **Helmet-Wearing Detection:** Uses IR sensor or reed switch to detect helmet usage.
- **Fall/Impact Detection:** Detects accidents using a vibration sensor (e.g., MPU6050 or SW-420).
- **Buzzer Warning:** Sounds an alarm if the rider starts riding without wearing the helmet.
- **Emergency Alert System:** Detects severe impacts and starts a countdown timer.
- **Alert Cancellation Option:** Riders can cancel false alerts within 20 seconds.
- **BLE Communication:** ESP32 transmits data via Bluetooth Low Energy to the mobile app.
- **React Native Mobile App:** Displays alerts, manages contacts, and stores data.
- **Cloud Storage via Firebase:** Real-time alert logs and contact sync.

---

## 📱 Mobile App Screens

- **Sign Up / Login:** Auth with phone number or email (via Firebase).
- **Profile Screen:** Enter and manage emergency contact numbers.
- **Home Screen:** “Have a safe ride” UI with status & edit profile.
- **Alert Screen:** Countdown with cancel option for false positives.

---

## 🧰 Tech Stack

| Layer            | Technology                                |
|------------------|--------------------------------------------|
| Microcontroller  | ESP32 DevKit v1 (ESP-WROOM-32)             |
| Programming IDE  | Arduino IDE (v2.2+)                        |
| Mobile App       | React Native (v0.73+)                      |
| Bluetooth Comm   | `react-native-ble-plx` (BLE communication) |
| Backend Database | Firebase Firestore                         |
| Authentication   | Firebase Auth (Phone/Email)                |
| Cloud Messaging  | Firebase Cloud Messaging (optional)        |
| Local Storage    | AsyncStorage (React Native)                |
| PCB Design       | EasyEDA (v6.5+)                            |

---

## 🔌 Hardware Components

- ESP32 DevKit v1 (BLE support)
- IR Sensor or Reed Switch (Helmet detection)
- MPU6050 or SW-420 (Fall detection)
- Buzzer (Audible alarm if helmet not worn)
- TP4056 charging module (Battery management)
- Li-ion Battery (Rechargeable)
- Custom PCB (EasyEDA designed)
- Helmet (mountable hardware)

---

## 👨‍💻 Project Team

- **Sahan Perera** – Mobile App Developer (React Native), UI/UX Design  
- **Sulochana Dananjani** – Embedded Systems & Sensor Integration (ESP32, PCB)  
- **Induwara Abhisheka** – Firebase Integration, Bluetooth Communication, and Testing



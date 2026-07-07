# 🚨 Human Safety Alert System

### Real-Time IoT Emergency Response System using ESP32, GPS & Telegram Bot

**Embedded Systems • Internet of Things (IoT) • GPS Tracking • Secure HTTPS • REST API • Real-Time Communication**

---

## 📖 Overview

The **Human Safety Alert System** is an IoT-enabled embedded solution designed to provide immediate assistance during emergency situations through a single-button activation mechanism.

Powered by the **ESP32 microcontroller**, the system integrates a **NEO-6M GPS module** to acquire real-time location data and utilizes the **Telegram Bot API** to instantly deliver emergency notifications over a secure Wi-Fi connection. Upon pressing the panic button, the device retrieves the user's current GPS coordinates, generates a Google Maps location link, and transmits it to predefined emergency contacts.

Unlike traditional GSM-based alert systems, this implementation leverages internet-based communication, reducing hardware complexity while enabling faster, more reliable, and scalable notifications.

This project demonstrates the practical application of **embedded systems, IoT communication, GPS interfacing, secure network programming, and hardware-software integration** to solve a real-world safety challenge.

---

## ✨ Key Features

- 🚨 One-touch emergency alert activation
- 📍 Real-time GPS location acquisition
- 🌍 Automatic Google Maps location link generation
- 💬 Instant Telegram notification via Bot API
- 🔒 Secure HTTPS communication
- 📶 Wi-Fi enabled IoT architecture
- ⚡ Low-latency emergency response
- 📦 Lightweight and portable embedded design
- 🔄 Scalable system architecture for future enhancements

---

## 🏗️ System Architecture

```text
                 Panic Button
                      │
                      ▼
                 ESP32 Controller
                      │
          ┌───────────┴───────────┐
          │                       │
          ▼                       ▼
   GPS (NEO-6M)             Wi-Fi Network
          │                       │
          ▼                       ▼
  Latitude & Longitude      Telegram Bot API
                  │
                  ▼
       Google Maps Location Link
                  │
                  ▼
      Emergency Notification
```

---

## 🛠 Hardware Components

| Component | Description |
|-----------|-------------|
| ESP32 DevKit V1 | Main processing unit with built-in Wi-Fi |
| NEO-6M GPS Module | Real-time GPS location tracking |
| Panic Push Button | Emergency trigger |
| 5V Power Supply | System power source |
| Breadboard & Jumper Wires | Circuit connections |

---

## 💻 Software Stack

- Arduino IDE
- Embedded C++
- ESP32 Board Package
- TinyGPS++ Library
- WiFi Library
- WiFiClientSecure Library
- Telegram Bot API
- Google Maps

---

## ⚙️ Working Principle

1. The ESP32 connects to the configured Wi-Fi network.
2. The GPS module continuously receives satellite data.
3. The system remains in an idle monitoring state.
4. When the panic button is pressed:
   - The current GPS coordinates are acquired.
   - A Google Maps location URL is generated.
   - A secure HTTPS request is sent to the Telegram Bot API.
5. The emergency contact instantly receives a Telegram notification containing the user's live location.

---

## 🔌 Circuit Connections

### GPS Module

| GPS Module | ESP32 |
|------------|-------|
| VCC | 3.3V |
| GND | GND |
| TX | GPIO16 (RX2) |
| RX | GPIO17 (TX2) |

### Panic Button

| Panic Button | ESP32 |
|--------------|-------|
| Signal | GPIO13 |
| Ground | GND |

---

## 📂 Repository Structure

```text
Human-Safety-Alert-System/
│
├── Code/
│   └── HumanSafetyAlert.ino
│
├── Circuit_Diagram/
│   └── ESP32_GPS_Telegram.png
│
├── Images/
│   ├── Hardware_Setup.jpg
│   ├── Telegram_Output.jpg
│   └── System_Working.jpg
│
├── Documentation/
│   └── Project_Report.pdf
│
└── README.md
```

---

## 🚀 Technologies Demonstrated

- Embedded Systems Design
- Internet of Things (IoT)
- ESP32 Programming
- UART Communication
- GPS Data Processing
- Secure HTTPS Communication
- REST API Integration
- Event-Driven Programming
- Hardware–Software Co-design
- Real-Time Embedded Applications

---

## 📱 Sample Telegram Alert

```text
🚨 EMERGENCY ALERT

Immediate assistance required.

Current Location

Latitude  : xx.xxxxxx

Longitude : yy.yyyyyy

https://maps.google.com/?q=xx.xxxxxx,yy.yyyyyy
```

---

## 🎯 Applications

- Women's Safety
- Child Safety
- Elderly Care
- Solo Travelers
- Outdoor Adventure Safety
- Emergency Response Systems
- Industrial Worker Safety
- Personal Security Devices

---

## 🔮 Future Enhancements

- AI-based emergency detection
- Automatic fall detection
- Voice-activated SOS
- Heart-rate monitoring
- Wearable device integration
- Mobile application dashboard
- Cloud-based event logging
- Live location tracking
- Multiple emergency contacts
- Rechargeable battery management

---

## 📚 Learning Outcomes

This project strengthened practical expertise in:

- Embedded Software Development
- ESP32 Firmware Development
- GPS Module Interfacing
- UART Communication Protocol
- Secure IoT Communication
- Telegram Bot Integration
- Network Programming
- Sensor Interfacing
- Real-Time Event Handling
- System-Level Hardware Design

---

## 📊 Project Highlights

- ✅ Real-Time Embedded System
- ✅ IoT-Based Emergency Alert Platform
- ✅ GPS-Based Live Location Tracking
- ✅ Telegram Bot API Integration
- ✅ Secure HTTPS Communication
- ✅ Event-Driven Architecture
- ✅ Low-Cost Embedded Solution
- ✅ Industry-Oriented IoT Project

---

## 🤝 Contributing

Contributions, feature requests, and suggestions are welcome.

If you would like to improve this project, feel free to fork the repository, create a feature branch, and submit a pull request.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👩‍💻 Author

**Thanusha Reddy Padherla**

B.Tech – Electronics and Communication Engineering

Amrita Vishwa Vidyapeetham

📧 *Open to collaborations in Embedded Systems, IoT, AI, and Intelligent Hardware Design.*

---

### ⭐ If you found this project useful, consider giving it a star!

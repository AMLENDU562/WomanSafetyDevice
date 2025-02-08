# StreeRaksha - Smart IoT-Enabled Personal Safety Device for Women

## 📌 Overview
StreeRaksha is an innovative IoT-based wearable device designed to enhance women's safety by providing real-time location tracking and emergency alerts. The device integrates multiple sensors and cloud connectivity to ensure a swift response during emergencies.

## 🎯 Problem Statement
With rising crimes against women, there is a need for an efficient safety device that offers immediate help. Many existing safety solutions are either inaccessible during emergencies or have significant delays. StreeRaksha addresses these issues through real-time GPS tracking, automatic motion detection, and cloud-based emergency alerts.

## 🛠 Features
✅ **Manual & Automatic Alerts**: Users can trigger an alert using a push button, or the device detects rapid hand movements to send alerts automatically.
✅ **Real-Time GPS Tracking**: Sends the user's location to predefined emergency contacts and law enforcement.
✅ **Cloud Connectivity**: Uses Thingspeak IoT cloud for alert notifications.
✅ **Low-Power Consumption**: Designed for prolonged usage with optimized power management.
✅ **Compact & Wearable**: Can be worn as a bracelet or pendant for convenience.

## 🔧 System Architecture
The system consists of:
- **NEO-6M GPS Module**: For real-time location tracking.
- **MPU6050 Accelerometer**: Detects rapid movement for automatic emergency activation.
- **ESP32 NodeMCU**: Controls the device and manages communication with the cloud.
- **Push Button**: Provides a manual alert mechanism.
- **Thingspeak Cloud**: Stores and processes alert data, sending notifications via email.

## 📑 System Design
- **System Architecture Diagram**
- **Data Flow Diagram**
- **Use Case Diagram**
- **Sequence Diagram**

## 🔌 Hardware Requirements
| Component           | Function |
|--------------------|-----------------------------------|
| NEO-6M GPS Module | Tracks and sends real-time location data. |
| MPU6050 Accelerometer | Detects motion to trigger alerts automatically. |
| ESP32 NodeMCU | Microcontroller for processing and communication. |
| Push Button | Manual activation of alerts. |
| Power Supply (3-5V) | Ensures stable operation. |

## 🖥 Software Requirements
- **Arduino IDE**: For programming ESP32.
- **Thingspeak Cloud**: For storing and processing emergency alerts.
- **SMTP Email API**: To send alerts to emergency contacts.

## 📜 Implementation
The device is programmed using **Arduino IDE** and uses **ESP32** to process inputs from the GPS and accelerometer. Alerts are transmitted via **Wi-Fi** to the cloud, which then notifies emergency contacts.

### 🚀 Key Algorithms
1. **Emergency Alert Algorithm**: Sends GPS coordinates and alert messages upon manual or automatic trigger.
2. **Motion Detection Algorithm**: Detects rapid hand movements and triggers an alert if necessary.
3. **Location Transmission Algorithm**: Ensures accurate and timely GPS data updates.
4. **Notification Algorithm**: Sends alert emails to predefined emergency contacts.

## 🛠 Testing
**Unit Test Cases:**
- GPS accuracy within ±5 meters.
- Motion detection triggering alert after 3 consecutive jerks.
- Successful email notifications within 10 seconds.

**Integration Testing:**
- GPS, accelerometer, push button, ESP32, and cloud services tested together.
- Successful data transmission and real-time alerts.

## 📊 Results
✅ Real-time location tracking was accurate within ±5 meters.
✅ Motion detection had a 95% success rate in testing.
✅ Emergency alerts were delivered within 10 seconds.
✅ The device operated continuously for 8+ hours on a full charge.

## 🔮 Future Scope
🔹 **SMS & Voice Alerts**: Implementing additional alert mechanisms.
🔹 **AI-Powered Threat Detection**: Using AI to analyze movement patterns and predict threats.
🔹 **Compact Design**: Miniaturizing components for better wearability.
🔹 **Mobile App Integration**: Allowing users to control and monitor the device via a mobile app.

## 📖 References
- Research papers and sources on women's safety and IoT-based security solutions.

---
**🔗 Developed by:** Akshay N, Aman A Shetty, Amlendu Kumar, Rohit Gajre  
**📅 Year:** 2024-25  
**🎓 Institution:** Dayananda Sagar College of Engineering, Bengaluru  

> *"Empowering Women, Enhancing Safety!"*

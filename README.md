# 🏠 Home Automation System (IoT-Based)

A final-year major project developed under Pokhara University, this Home Automation System enables users to remotely monitor and control home appliances using an IoT-based architecture integrating ESP32, AWS Cloud Services, and a mobile app built with React Native.

## 📱 Overview

This project simplifies home management by allowing homeowners to:

- Remotely control lights, fans, and other appliances.
- Monitor gas leaks via the MQ-2 sensor.
- Receive real-time updates and data from a user-friendly mobile app.
- Ensure safety and security through automation and sensors.

## 👨‍💻 Team Members

- Minraj Basnet `181526`
- Puspa Raj Paneru `181530`
- Mukesh Kushwaha `181527`
- Prakash Chand Kushwaha `181529`

**Supervisor:** Assoc Prof. Mr. Satish Kumar Karn  
**Institution:** Nepal College of Information Technology (NCIT), Balkumari, Lalitpur, Nepal  
**Date:** 13/07/2024

---

## 🔧 Tech Stack

### Hardware Components

- ESP32 microcontroller
- MQ-2 Gas Sensor
- Ultrasonic Sensor
- Flame Sensor
- 4-Channel Relay Module
- Buzzer
- Jumper Cables

### Software Components

- **Mobile App:** React Native
- **Cloud Backend:** AWS
  - AWS IoT Core (MQTT protocol)
  - AWS Lambda (serverless computing)
  - Amazon DynamoDB (data storage)
  - AWS AppSync with GraphQL API
  - AWS Cognito (authentication)

---

## 🧠 Architecture

### 🏗 3-Layer IoT Architecture

1. **Perception Layer:** ESP32, sensors, and actuators.
2. **Network Layer:** AWS IoT Core using MQTT.
3. **Application Layer:** Mobile app with GraphQL API.

### 🔁 Communication Model

- **Publisher-Subscriber Model** (via MQTT)
- ESP32 acts as a gateway to AWS IoT Core, relaying sensor data and receiving commands.

---

## 📱 App Features

- Toggle lights and fans remotely.
- Control fan speed with sliders.
- Monitor gas levels with a visual gauge.
- Authentication via AWS Cognito.

---

## 🎯 Objectives

- Remotely control and monitor home appliances.
- Provide improved safety through gas leakage alerts.
- Improve energy efficiency and convenience.

---

## 🧩 Future Enhancements

- Modularization of hardware into Power, Microcontroller, and Switch modules.
- Integration of AI for personalized automation.
- Voice and gesture-based controls.
- Advanced biometric authentication and intrusion detection.

---

## 💰 Budget Overview

| Component           | Quantity | Price (Rs.)   |
| ------------------- | -------- | ------------- |
| ESP32               | 1        | 945           |
| MQ-2 Gas Sensor     | 1        | 300           |
| Flame Sensor        | 1        | 345           |
| Ultrasonic Sensor   | 1        | 200           |
| 4-Channel Relay     | 2        | 980           |
| Buzzer              | 1        | 100           |
| Jumper Cables (M-M) | 20       | 100           |
| Jumper Cables (M-F) | 20       | 100           |
| **Total**           | -        | **Rs. 3,070** |

---

## 📚 References

1. Abdulraheem et al., "Home Automation System based on IoT", Technology Reports of Kansai University, 2020.
2. Chaurasia et al., "Enhanced Smart Home Automation System", 2019.
3. S. Dey et al., "IEEE Explore Document", 2016.
4. Singh et al., "IEEE Explore Document", 2019.
5. Jackson & Angela, "Security and Privacy in Amazon Echo", IJITCA, 2018.
6. Hilbolling et al., "Philips Hue Ecosystem", Journal of Product Management, 2020.
7. Ye et al., "IEEE Explore Document", 2017.

---

## 📷 Diagrams (in report)

- ESP32 Schematic
- Relay Module Overview
- Use Case & Sequence Diagram
- Publisher-Subscriber Architecture
- Circuit Diagram
- IoT Workflow Diagram

---

## 📜 License

This project is academic and open for reference. For commercial use, proper permission is required.

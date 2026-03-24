# 🚦 AI Pedestrian & Vehicle Crossing Detection System

## 📌 Overview

This project is an AI-based real-time pedestrian and vehicle detection system using YOLOv8 running on Raspberry Pi. It detects vehicles from live camera feed and triggers a buzzer alert system along with LCD display updates via Arduino.

---

## 🚀 Features

* Real-time object detection using YOLOv8
* Vehicle detection (car, bike, bus, truck)
* Buzzer alert when vehicle is detected
* LCD display feedback via serial communication
* Automatic camera detection and recovery
* Edge AI processing (runs on Raspberry Pi)

---

## ⚙️ Hardware Used

* Raspberry Pi
* USB Camera
* Buzzer (GPIO controlled)
* Arduino (for LCD display)
* I2C LCD (connected to Arduino)

---

## 💻 Software & Technologies

* Python
* OpenCV
* YOLOv8 (Ultralytics)
* RPi.GPIO
* Serial Communication (UART)

---

## 🔌 Working Principle

1. System scans and detects available camera
2. YOLOv8 model processes video frames in real time
3. Detects vehicle classes:

   * Car
   * Motorcycle
   * Bus
   * Truck
4. If vehicle detected:

   * Buzzer turns ON
   * LCD displays "VEHICLE"
5. If no vehicle:

   * Buzzer OFF
   * LCD displays "NO"

---

## 📦 Installation

```bash
pip install opencv-python ultralytics RPi.GPIO pyserial
```

---

## ▶️ Run the Project

```bash
python src/main.py
```

---

## 📷 Output

* Bounding boxes displayed on screen
* Real-time alerts via buzzer and LCD

---

## 🌐 Applications

* Smart pedestrian crossing systems
* Traffic monitoring
* Autonomous vehicle safety
* Smart city systems

---

## 🔮 Future Improvements

* Pedestrian detection + signal control
* Traffic light automation
* Cloud monitoring dashboard
* AI-based accident prediction

---

## 👨‍💻 Author

Sowgandh S
Embedded Systems & AI–IoT Developer
GitHub: https://github.com/kingstonsow45

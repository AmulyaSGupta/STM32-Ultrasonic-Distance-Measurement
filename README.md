# 📡 STM32 Ultrasonic Distance Measurement System

## 📌 Overview
This project implements a **real-time distance measurement system** using an ultrasonic sensor (HC-SR04) interfaced with an **STM32 microcontroller**.  

The system calculates distance using **timer-based pulse width measurement** and displays the result via **UART communication**.

An initial prototype was developed using **Arduino (Tinkercad)** and later implemented on **STM32 (CubeMX + CubeIDE)** for better performance and low-level control.

---

## 🚀 Features
- 📏 Accurate distance measurement using ultrasonic sensor
- ⏱ Timer-based pulse width calculation
- 🔁 Continuous real-time monitoring
- 🖥 UART output for serial display
- 🔧 STM32CubeMX configuration for peripherals
- 🧪 Tinkercad simulation for initial validation

---

## 🛠️ Technologies Used
- STM32F103C8T6 (Blue Pill)
- STM32CubeMX
- STM32CubeIDE
- Embedded C (HAL Drivers)
- Arduino IDE (Tinkercad simulation)
- Ultrasonic Sensor (HC-SR04)

---

## 📂 Project Structure

---

## ⚙️ Working Principle
1. Trigger pulse is sent to the ultrasonic sensor.
2. Sensor emits ultrasonic waves.
3. Echo pulse duration is measured using STM32 timers.
4. Distance is calculated using:

\[
Distance = \frac{Time \times Speed\ of\ Sound}{2}
\]

5. Result is transmitted via UART.

---

## 🔌 Hardware Connections
- **Trigger Pin** → GPIO Output  
- **Echo Pin** → GPIO Input  
- **VCC / GND** → Power supply  
- UART configured for serial output  

---

## 🧪 Tinkercad Simulation
An Arduino-based version was developed in Tinkercad to:
- Validate sensor behavior
- Test logic before STM32 implementation  

---

## 📊 Output
- Distance values displayed in serial terminal
- Real-time updates based on object position

---

## 🎯 Applications
- Obstacle detection systems
- Robotics
- Smart parking systems
- Distance sensing applications

---

## 📈 Future Improvements
- Add LCD/OLED display
- Integrate buzzer for alerts
- Wireless monitoring using ESP32/WiFi
- Interrupt-based measurement for higher accuracy

---

## 👩‍💻 Author
**Amulya S Gupta**  
Electronics & Communication Engineering  

---

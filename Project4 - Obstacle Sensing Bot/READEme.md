# 🤖 Obstacle Sensing Bot

This project implements an **Obstacle Sensing System** using an **Arduino Uno**, an **Ultrasonic Sensor (HC-SR04)**, LEDs, and a Buzzer. The system detects the speed of a moving obstacle and provides visual and audio alerts accordingly.

## 📌 Features
- **Detects the speed of a moving obstacle** 🏎️
- **Visual indication** using Red, Yellow, and Green LEDs 🚦
- **Buzzer alarm for high-speed obstacles** 🔊
- **Ideal for automation and security applications** 🔧

## 🔧 Components Required
| Quantity | Component |
|----------|-----------|
| 1 | Arduino Uno R3 |
| 1 | HC-SR04 Ultrasonic Sensor |
| 1 | Buzzer |
| 1 | Red LED |
| 1 | Yellow LED |
| 1 | Green LED |
| 3 | Resistors (330Ω) |
| 1 | Breadboard |
| Wires | Jumper Wires |

## ⚙️ Working Principle
The system detects the speed of a moving obstacle and provides feedback:
- **If speed is between 0 cm/s - 20 cm/s**, the **Red LED blinks**. 🔴
- **If speed is between 20 cm/s - 50 cm/s**, the **Yellow LED blinks**. 🟡
- **If speed is greater than 50 cm/s**, the **Green LED blinks, and the Buzzer sounds**. 🟢🔊

## 🚀 Setup Instructions
1. **Connect components** as per the circuit diagram.
2. **Upload the code** to the Arduino using the **Arduino IDE**.
3. **Place a moving obstacle** in front of the ultrasonic sensor.
4. **Observe the LED and Buzzer response** based on the obstacle’s speed.

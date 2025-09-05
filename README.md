# **Open-Source DM Robotic Arm**  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  
![Platform](https://img.shields.io/badge/platform-MATLAB%20%7C%20Python-blue)  
![Motors](https://img.shields.io/badge/motors-DM4310%20%26%20DM4340-green)  

A self-built, open-source robotic arm powered by **DM4310** & **DM4340** BLDC motors with integrated **FOC modules**.  
It offers **53 cm max reach**, **500 g min payload**, and full control via MATLAB with per-joint tuning of **Kp**, **Kd**, **V_des**, **P_des**, and **T** for precise and flexible motion control.  

Link to all the documents: https://github.com/XU32444/RoboticArm



---

## 📷 **Preview**

<img width="1068" height="668" alt="image" src="https://github.com/user-attachments/assets/8ab26a7c-4af1-406a-b4f8-460515da93ce" />

<img width="1920" height="1080" alt="Model_2025-Aug-15_05-48-42AM-000_CustomizedView31302310918_png" src="https://github.com/user-attachments/assets/b849083c-4f9a-4113-be0e-c19485265ca9" />



https://github.com/user-attachments/assets/e968c895-902c-4a40-a29c-e2be5edf713a



---
## Model Access Link:

https://a360.co/3HxrzQ5

---
---

## ✨ **Features**
- 🦾 **Powerful Hardware** – DM4310 & DM4340 BLDC motors with integrated FOC  
- 📏 **Max Reach** – 53 cm  
- 📦 **Payload** – 500 g minimum  
- 🎛 **Flexible Control** – Adjust **Kp**, **Kd**, **V_des**, **P_des**, **T** per joint  
- 🔄 **Multiple Modes** – MIT, Position-Velocity, Velocity, Torque-Position  
- 🛠 **Upgradeable** – Modular hardware & open-source software for easy upgrades  

---

## 🛠 **Hardware Requirements**
| Component | Model | Notes |
|-----------|-------|-------|
| Motors | DM4310, DM4340 | Integrated FOC modules |
| Motor Driver | Built-in Damiao FOC | — |
| USB-to-CAN Adapter | DM_USB2CAN | Tested with included DLL |
| Power Supply | 24–48V (motor-dependent) | Ensure correct current rating |
| Structure | Custom Arm Frame | 53 cm reach |
| Cables | CAN wiring, power cables | Shielded recommended |

---

## 💻 **Software Requirements**
- MATLAB R2023b+ (for main control UI)  
- Python 3.8+ (for optional Python control scripts)  
- Python libraries:  
  ```bash
  pip install pyserial numpy

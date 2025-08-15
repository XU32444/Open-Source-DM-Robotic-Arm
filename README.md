# **Open-Source DM Robotic Arm**  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  
![Platform](https://img.shields.io/badge/platform-MATLAB%20%7C%20Python-blue)  
![Motors](https://img.shields.io/badge/motors-DM4310%20%26%20DM4340-green)  

A self-built, open-source robotic arm powered by **DM4310** & **DM4340** BLDC motors with integrated **FOC modules**.  
It offers **53 cm max reach**, **500 g min payload**, and full control via MATLAB with per-joint tuning of **Kp**, **Kd**, **V_des**, **P_des**, and **T** for precise and flexible motion control.  

---

## 📷 **Preview**

<img width="1067" height="668" alt="image" src="https://github.com/user-attachments/assets/d6171dc3-892e-42c1-a29a-d9dea1c562b1" />


https://github.com/user-attachments/assets/50352871-9a13-4d8e-b3fd-fbdad3ffe666


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

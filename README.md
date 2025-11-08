# VOHEAD
Vohead – Project Documentation Repositoryy

This repository contains the open-source code, design files, and documentation for **VoHead**,  
a fully customizable, low-cost, and multimodal human–computer interaction system designed to improve  
digital gaming accessibility for individuals with physical disabilities.

---

## 📘 About the Paper
This project accompanies the research paper:

This paper presents VoHead, a fully customizable, low-cost, and multimodal human–computer interaction system designed to improve digital gaming accessibility for individuals with physical disabilities. The system integrates three complementary modalities—head-motion tracking, single-hand joystick control, and voice command recognition—to minimize dependence on bilateral hand movement during gameplay. A 3D-printed, parametric head-mounted frame, equipped with a Bosch BNO055 inertial measurement unit, enables natural directional input using linear acceleration data rather than orientation data. An Arduino-based microcontroller interprets sensor output and emulates a USB HID device to provide real-time mouse or joystick functions without the need for drivers. A configurable tactile button and software-based voice command system further increase flexibility and usability. Experimental evaluations and preliminary user feedback indicate improved accessibility, responsiveness, and ease of use in first-person shooter (FPS) games compared to traditional dual-hand controllers. VoHead demonstrates the potential of customizable, open-source assistive technologies to advance universal design and promote equitable digital participation.

## 🧩 System Overview
- **Hardware:** Arduino-based microcontroller + Bosch BNO055 IMU + tactile button  
- **Software:** Head-motion to mouse/joystick emulation via USB HID  
- **Input Modalities:**  
  - Head motion tracking  
  - Single-hand joystick  
  - Voice command control  
- **Output:** Real-time USB HID signals for gaming interfaces  
- **Design:** 3D-printed head-mounted parametric frame

---

## ⚙️ Repository Contents
| Folder | Description |
|--------|--------------|
| `/firmware/` | Arduino code for IMU data acquisition and HID emulation |
| `/voice/` | Voice recognition module and command configuration |
| `/3d_models/` | STL and CAD files for the headset design |
| `/docs/` | Research documentation and supplementary material |

---

## 🧠 Requirements
- Arduino IDE (v2.0+)
- Bosch BNO055 IMU
- Arduino-compatible microcontroller with USB HID support (e.g., Leonardo, Micro)
- Python (for optional voice recognition)
- 3D printer (for headset fabrication)

---

## 🚀 Usage
1. Flash the firmware to the Arduino board.  
2. Connect the BNO055 sensor and tactile button according to the provided wiring diagram.  
3. Run the voice recognition script (optional).  
4. Plug the device into a computer — it will appear as a standard mouse or joystick.  
5. Launch a game or application and configure input sensitivity as needed.

---

## 🔓 License
This project is released under the **MIT License © 2025 VoHead Research Team, Ege University.**  
See the [LICENSE](./LICENSE) file for full terms.

---

## 📄 Citation
If you use this code or design in your research, please cite the original paper as:

> VoHead Research Team. (2025). *VoHead: A multimodal human–computer interaction system for accessible gaming.*  
> Ege University, Türkiye.

---

## 🤝 Acknowledgments
Developed by the **VoHead Research Team** at **Ege University**.  
We thank all contributors and participants who supported testing and evaluation.

---

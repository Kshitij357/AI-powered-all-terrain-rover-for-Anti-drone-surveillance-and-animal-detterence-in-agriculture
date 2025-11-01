# AI-powered-all-terrain-rover-for-Anti-drone-surveillance-and-animal-detterence-in-agriculture

A modular **AI-powered rover** built for **defense surveillance, agricultural protection, and anti-drone applications**.  
Equipped with a **dual-axis pan-tilt gimbal**, the system performs **real-time target tracking** through onboard servos controlled via microcontrollers, guided by a laptop-based **machine learning vision module**.

---

## 🚀 About the Project
This project combines **embedded hardware control**, **real-time ML tracking**, and **wireless communication** into a single all-terrain platform.

The rover streams live video from an **ESP32-CAM** to a laptop, where the **Python-based tracking module** processes frames using computer vision models.  
Detected targets (humans, drones, or animals) are tracked using servo correction data transmitted back to the rover via **Bluetooth (HC-05)** — with an upcoming **ESP32 Wi-Fi upgrade** for lower latency and longer range.

---

## 🧠 Use Cases
- 🛡️ **Defense Surveillance:** Tracks human movement or intrusions in restricted zones.  
- ✈️ **Anti-Drone Operations:** Detects and follows low-flying drones in airspace around airports or high-security events.  
- 🌾 **Agricultural Protection:** Detects animals or birds approaching farmland to activate deterrent systems, preventing crop loss.  

---

## ⚙️ System Overview
- **Control & Processing:**  
  - Laptop runs Python-based ML tracking (OpenCV + deep learning models).  
  - Processes ESP32-CAM video feed and computes servo corrections.

- **Communication:**  
  - Real-time control data sent via **HC-05 Bluetooth module** (initial version).  
  - Future version supports **ESP32 Wi-Fi bridge** for faster, bidirectional communication.

- **Mechanical System:**  
  - Custom-built all-terrain chassis.  
  - Dual-axis **pan-tilt gimbal** for precise camera tracking.  
  - LED/MOSFET signaling and modular power distribution.

---

## 🧩 Features
- Real-time **object and face tracking** via laptop ML system.  
- Wireless control via **Bluetooth**, upgradeable to **Wi-Fi**.  
- Modular gimbal mount for camera or sensor payloads.  
- Field-ready all-terrain rover design.  
- Supports **multi-purpose models** (face, drone, animal, or vehicle tracking).  

---

## 🛠️ Tech Stack
**Languages & Libraries:** Python, OpenCV, NumPy, Mediapipe, TensorFlow, Arduino C++  
**Hardware Components:** Arduino Uno, ESP32-CAM, HC-05, Servo Motors (SG90 / MG995), DC Motors, Motor Driver L298N, MOSFET-LED System  
**Tools:** Arduino IDE, VS Code, Jupyter Notebook, Serial Communication Monitor  

---

## 📸 Workflow Overview
1. ESP32-CAM streams video to the laptop.  
2. ML model (face/object tracker) processes the frames.  
3. Calculated servo correction data (pan/tilt) sent to Arduino via Bluetooth.  
4. Rover adjusts gimbal position and activates signaling (e.g., LED).  
5. Optional: Wi-Fi bridge mode for higher precision and lower delay.

---

## 🎯 Future Enhancements
- Upgrade to **ESP32 Wi-Fi** for low-latency two-way communication  
- Add **GPS + Compass module** for autonomous navigation  
- Integrate **thermal or IR camera** for night vision and surveillance  
- Deploy **custom-trained models** for drones and animals  

---

## 👤 Contributors
**Kshitij Verma**  
🎓 CSJM University, Kanpur  
🔗 [LinkedIn](https://www.linkedin.com/in/kshitij098)

---

## 📄 License
This project is open-source under the **MIT License** — feel free to use and modify with credit.


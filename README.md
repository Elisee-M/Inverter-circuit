# ⚡ Smart Inverter Project
---
<img width="1261" height="597" alt="image" src="https://github.com/user-attachments/assets/6ef77774-c027-4f5d-b03d-58852c87ddbf" />
---
# 📝 Overview
This project is a **smart inverter system** designed to convert **DC (Direct Current)** from a battery or solar source into **AC (Alternating Current)** that can power household or industrial devices.

It combines **power electronics** and **microcontroller-based control** to ensure efficient and stable power output.

---

## ⚙️ Features
- 🔌 Converts **12V/24V DC** to **220V AC**
- ⚙️ **Automatic switching** between mains and inverter mode
- 🔋 **Battery monitoring** and protection from overcharge/overdischarge
- 💡 **Load management** for energy efficiency
- 🌞 Optional **solar input** support
- 🖥️ **LCD display** or LED indicators for system status

---

## 🧠 Working Principle
1. The **DC supply** (from battery or solar) feeds into the **oscillator circuit** that generates an AC signal.
2. The **MOSFETs or transistors** act as switches, converting DC into a square wave AC.
3. A **transformer** steps up the voltage to 220V AC.
4. The microcontroller monitors battery voltage and load, ensuring smooth switching and protection.

---

## 🧰 Components Used
- 🔋 12V/24V Battery  
- 🌀 Transformer (center-tapped)  
- ⚡ Power MOSFETs (e.g., IRFZ44N)  
- 🔌 Relays & Diodes  
- 🔧 Capacitors, Resistors, Heatsink, etc.

---

## 🧑‍💻 Microcontroller Control (if used)
- Reads **battery voltage** via analog input  
- Controls **PWM signal** to MOSFET drivers  
- Detects **AC mains presence**  
- Switches **relay** automatically between mains and inverter  

---

## 🧾 Future Improvements
- Add **solar MPPT charging**
- Include **IoT monitoring** (WiFi or Bluetooth)
- Improve waveform from **square wave** → **pure sine wave**
- Mobile app or web dashboard for remote status

---

## 🧩 Circuit Simulation (Optional)
You can simulate the circuit in **Proteus** or any electronic simulator by including:
- Transformer
- IRFZ44N MOSFETs
- Arduino / Controller
- Relays
- Battery source

---


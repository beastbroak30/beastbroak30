#  Flappy Card v1.0 | Technical Deep-Dive

> "Making Hardware Think" — A study in extreme embedded optimization.

This project is a physical manifestation of the **"Built to Finish"** philosophy. It compresses a real-time game engine, physics, and display drivers into a credit-card-sized PCB powered by an 8-bit architecture.

---

## Hardware Demonstration

<div align="center">
  <div style="width: 200px; height: 400px; overflow: hidden; display: flex; align-items: center; justify-content: center; border-radius: 8px; border: 1px solid #333;">
    <video 
      src="https://github.com/user-attachments/assets/1a019c49-8cb8-4815-9944-753374844a9a" 
      style="transform: rotate(270deg); min-width: 200px; min-height: 400px;" 
      autoplay 
      loop 
      playsinline>
    </video>
  </div>
  <p><i>Real-time C++ physics and 8x8 matrix rendering on the ATtiny85.</i></p>
</div>




---

##  Core Functions & Logic

* **Bare-Metal Game Engine:** Engineered in optimized **C++** to manage game states and collision logic within strictly limited resources.
* **8x8 LED Matrix Driver:** Custom-written refresh logic to render the "bird" and scrolling "pipes" with zero perceptible lag.
* **Low-Latency Input:** Utilizes an external hardware interrupt on the "Press it man!!" tactile switch for frame-perfect jumping.
* **NFC Data Transmission:** Features a passive **NFC chip** that allows the card to share portfolio data even when disconnected from power.
*  **Battery Time:** Can last upto ~28 Days in a single charge with 10 uses per day session of 1 min or less. 
* **Universal Powering:** Integrated **USB-C port** for modern compatibility across all mobile and computing devices.

---

## 📊 System Specifications

| Component | Specification | Purpose |
| :--- | :--- | :--- |
| **MCU** | ATtiny85 (8-bit) | Core Processing & Logic |
| **Flash** | 8KB | Storing Game Engine & Binary |
| **SRAM** | 512 Bytes | Real-time Variable Management |
| **Display** | 8x8 LED Matrix | Visual Output Interface |
| **Input** | Interrupt-driven Switch | Low-latency User Interaction |
| **Storage** | Integrated NFC | Passive Data Sharing |

---

## 🧠 The Optimization Challenge

Building this was about more than just a game; it was about proving that **impact** can be achieved with minimal resources. Managing a 94% accuracy mindset in research begins here—by ensuring every byte of memory and every clock cycle is used with intent.

**Current Status:** V1.0 Stable. Preparing for deployment to the **World**.

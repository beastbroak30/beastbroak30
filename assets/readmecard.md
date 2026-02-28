#  Flappy Card v1.0 | Technical Deep-Dive

> "Making Hardware Think" — A study in extreme embedded optimization.

This project is a physical manifestation of the **"Built to Finish"** philosophy. It compresses a real-time game engine, physics, and display drivers into a credit-card-sized PCB powered by an 8-bit architecture.

---

## Hardware Demonstration

<p align="center">
  <video src="assets/flappycard_demo.mp4" width="100%" controls autoplay loop muted>
    Your browser does not support the video tag.
  </video>
  <br>
  <i>Real-time C++ physics and 8x8 matrix rendering on the ATtiny85.</i>
</p>

---

##  Core Functions & Logic

* **Bare-Metal Game Engine:** Engineered in optimized **C++** to manage game states and collision logic within strictly limited resources.
* **8x8 LED Matrix Driver:** Custom-written refresh logic to render the "bird" and scrolling "pipes" with zero perceptible lag.
* **Low-Latency Input:** Utilizes an external hardware interrupt on the "Press it man!!" tactile switch for frame-perfect jumping.
* **NFC Data Transmission:** Features a passive **NFC chip** that allows the card to share portfolio data even when disconnected from power.
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

<p align="center">
  <img src="https://raw.githubusercontent.com/TurtlPass/turtlpass-firmware-arduino/master/assets/icon.png" alt="TurtlPass Logo" width="200" />
</p>

<h1 align="center">TurtlPass — Your Passwords, Physically Secured.</h1>

<p align="center">
  <sub>Secure, open-source password management built on reproducible hardware and cross-platform clients.</sub>
</p>

---

## ⚡ About TurtlPass

TurtlPass is a **hardware-based password management ecosystem** that focuses on **security, simplicity, and reproducibility**.  
Instead of storing passwords, it **derives them deterministically** from a secret seed that never leaves the device.


🔐 **Core Principles**
- **Reproducible Security** – Every device is built with open-source firmware and transparent cryptography.  
- **Deterministic Passwords** – Passwords are generated on demand, never stored or transmitted.  
- **Cross-Platform Integration** – Seamless support for Python, Chrome, and Android.  
- **Offline First** – No cloud dependency; your secrets stay in your hands.

🧩 The TurtlPass ecosystem spans **firmware**, **client apps**, and **protocol definitions** — all communicating via **Protocol Buffers** over USB for consistency across platforms.

---

## 📟 Firmware

📘 [**Firmware Documentation**](https://ryanamaral.gitbook.io/turtlpass/firmware-documentation)

- [![Arduino Firmware](https://img.shields.io/github/v/release/TurtlPass/turtlpass-firmware-arduino?color=green&label=Arduino%20Firmware&logo=arduino)](https://github.com/TurtlPass/turtlpass-firmware-arduino) The hardware heart of TurtlPass — firmware for passwords born in hardware, offline and reproducible (RP2040 / RP2350).
- [![Protocol Buffers](https://img.shields.io/github/v/release/TurtlPass/turtlpass-protobuf?color=green&label=Protocol%20Buffers&logo=google)](https://github.com/TurtlPass/turtlpass-protobuf) Protocol Buffer definitions and build script for TurtlPass — enabling multi-language integration across C++, Python, JavaScript and Kotlin.

---

## 🖥️ Clients

📘 [**Client Documentation**](https://ryanamaral.gitbook.io/turtlpass/client-documentation)

- [![Python CLI](https://img.shields.io/github/v/release/TurtlPass/turtlpass-python?color=green&label=Python%20CLI&logo=python)](https://github.com/TurtlPass/turtlpass-python) Interact with TurtlPass devices from the terminal — hardware-backed passwords and cryptographic seeds, safe and local.
- [![Chrome Extension](https://img.shields.io/github/v/release/TurtlPass/turtlpass-chrome-extension?color=green&label=Chrome%20Extension&logo=googlechrome)](https://github.com/TurtlPass/turtlpass-chrome-extension) Connect Chrome to your TurtlPass device — passwords are generated and typed locally, straight from your hardware.
- [![Android](https://img.shields.io/github/v/release/TurtlPass/turtlpass-android?color=green&label=Android&logo=android)](https://github.com/TurtlPass/turtlpass-android) Bring TurtlPass to mobile — connect via USB-OTG to generate and auto-type passwords directly from your hardware, fully offline.

---

<p align="center">
  <small>🛠️ Built with love, reproducibility, and security in mind — by the <b>TurtlPass Project</b> 💚</small>
</p>

---


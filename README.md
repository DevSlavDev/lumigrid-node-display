# ✨ LumiGrid - Display Node ✨

---

## 💡 What is this Node?

The Display Node is your canvas for visual content in the LumiGrid system! 🖼️📺 Built on the capable Raspberry Pi, this node specializes in driving high-density HUB75 LED matrix panels or acting as a powerful Digital Signage player for standard HDMI screens.

Developed with passion by **DevSlavDev** 👨‍💻 in collaboration with **Cube & Reclame Fabriek** 🏢.

---

## 🚀 Key Features

* **HUB75 Matrix Control:** Drive large, vibrant HUB75 LED matrix panels using the optimized hzeller/rpi-rgb-led-matrix library. 🟥🟩🟦
    * Supports driving up to 3 parallel chains!
* **HDMI Digital Signage:** Turn any standard HDMI display into a dynamic signage screen. 📊
    * Play images, videos, and potentially run specific applications. ▶️🖼️
* **Dynamic Content:** Display a variety of information.
    * Time, Date, Sensor Data, User Text/Images/Videos. ⏰🗓️📊📝🖼️▶️
    * Integrations for Crypto/Finance Tickers, Transport info, Weather, and AI interaction! 💲🚆☁️🤖
* **Control Modes:** Supports External (MQTT, Art-Net via Pi capabilities), Sync (Master/Slave), and Independent modes. 🚦
* **Calendar-Based Playback:** Equipped with an RTC for scheduled content playback. 🗓️
* **Preset Support:** Define presets for specific content frame configurations or media playback settings.
* **Sensor Data Integration:** Can receive and display data pushed from Sensor Nodes. 📊➡️🖼️
* **REST API & Web UI:** Configurable and controllable via local network using Flask. 🌐

---

## 🧠 Technology Stack

* **Hardware:** Raspberry Pi Zero 2 W / Raspberry Pi 4 / Raspberry Pi 5 🧠
* **Operating System:** Raspberry Pi OS (RPiOS)
* **Software:** C++, Python/Flask
* **Display Libraries:** hzeller/rpi-rgb-led-matrix (C++), potentially others for HDMI playback.
* **Communication:** Ethernet/WiFi, HTTP/REST, mDNS, UDP (for Sync), Art-Net, MQTT.

---

## 🚧 Work In Progress (WIP)! 🚧

This node is currently the **primary focus of development!** 💪 We are actively working on implementing its core functionality, integrating with the chosen display libraries, building the Web UI, and critically, tuning the Raspberry Pi sync mechanism. ✨

---

## 🤝 Contributions

Currently, contributions are not being actively accepted for this specific node as it is the main focus of ongoing development.

**HOWEVER!** We are building this with future collaboration in mind! 🎉 Once the core Display Node functionality and Pi sync are stable, we plan to open up contributions. Keep an eye on the main LumiGrid repository for updates! 👀

---

## 🔗 Stay Tuned!

Follow the main LumiGrid repository for updates on our progress! 😊

---

Made with ❤️ by DevSlavDev for Cube & Reclame Fabriek

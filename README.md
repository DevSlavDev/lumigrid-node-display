# 🖥️ lumigrid-node-display: Drive Your Displays! 🖥️

Welcome to the lumigrid-node-display repository! 🚀 This is where the code lives for the Raspberry Pi-powered Display Node, capable of driving HUB75 panels and HDMI displays. Get ready to show off your content! 🤩

This node is part of the LumiGrid ecosystem, brought to you by Cube & Reclame Fabriek, with development led by DevSlavDev.

## 📂 What's Inside?

This repository contains the code and resources for the Display Node:

* `app/`:  Source code for the Raspberry Pi application (C++). This handles HUB75 driving, HDMI output, the web server, and more. 💻
* `web/`:  Node-specific web UI components for managing display content and settings. 💅
* `config/`:  Default configuration files for the Display Node. ⚙️
* `scripts/`:  Scripts for building and deploying the application to the Raspberry Pi. 🛠️
* `README.md`:  That's me! 👋 Your guide to this repository.

## 🛠️ Project Structure

Here's the layout of the repository:

lumigrid-node-display/
├── app/        💻 (Raspberry Pi Application)
├── web/        💅 (Web UI)
├── config/     ⚙️ (Configuration)
├── scripts/    🛠️ (Build/Deploy Scripts)
└── README.md   📖 (You are here!)


## 🔗 Related Repositories

* [LumiGrid (Main Repository)](https://github.com/DevSlavDev/LumiGrid):  Contains shared resources and documentation. 🧠

## ✨ Features

* Drives up to 3 parallel HUB75 chains. [cite: 36]
* Functions as a digital signage player for HDMI displays. [cite: 36]
* Supports various content frames (time, date, sensor data, images, videos, etc.). [cite: 37]
* Provides a web interface and REST API for control. [cite: 38]
* Uses presets to define content frame configurations. [cite: 38]

## 🚀 Getting Started

1.  **Clone this repository:**

    ```bash
    git clone [https://github.com/DevSlavDev/lumigrid-node-display.git](https://github.com/DevSlavDev/lumigrid-node-display.git)
    cd lumigrid-node-display
    ```

2.  **Set up your Raspberry Pi:** Make sure you have Raspberry Pi OS installed.

3.  **Install dependencies:** You'll need the `rpi-rgb-led-matrix` library and other dependencies.

4.  **Explore the code in the `app/` directory.**

5.  **Build and run the application on your Raspberry Pi.**

6.  **Use the web UI to control your displays!**

## 🤝 Contributing

Contributions are welcome! If you have improvements to display driving, content handling, the web interface, or any other part of the project, please submit a pull request. 💪

## 🐛 Issues

Please report any bugs or issues in this repository.

## 📜 License

\[License information will go here]

## Let's make some eye-catching displays! 🤩

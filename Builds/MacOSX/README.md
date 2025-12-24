# Upmixer - Stereo to Surround Plugin

![Platform](https://img.shields.io/badge/platform-macOS-lightgrey)
![Framework](https://img.shields.io/badge/framework-JUCE-orange)
![Format](https://img.shields.io/badge/format-VST3%20|%20AU%20|%20AUv3-blue)
![License](https://img.shields.io/badge/license-GPLv3-green)

**Upmixer** is a real-time audio plugin designed to upmix stereo sources into immersive multichannel formats (5.1, 7.1). Built with the [JUCE Framework](https://juce.com/) specifically for macOS audio production workflows.
                                                                                                                                                         
![Upmixer GUI](assets/upmixer_gui.png)

## 🎛 Features

- **Real-time Upmixing:** Low-latency conversion from Stereo to 5.1/7.1 Surround.
- **Spatial Control:** Adjust width, depth, and center channel divergence.
- **LFE Management:** Dedicated low-frequency effects processing and crossover control.
- **Visual Feedback:** Real-time metering for all output channels.

## 🛠 Tech Stack

- **Language:** C++17
- **Framework:** JUCE 7/8
- **Formats:** VST3, AU, AUv3
- **Platform:** macOS (Universal Binary: Apple Silicon & Intel)

## 🚀 Installation & Downloads

### For Musicians & Producers (Pre-built)
Don't want to compile code? You can download the ready-to-use installer here:
👉 **[Download Installer (macOS)](LINK_TO_YOUR_RELEASES_OR_GUMROAD)**
*(Consider supporting the development if you find this tool useful!)*

### For Developers (Build from Source)

**Prerequisites:**
- macOS 10.15+
- Xcode 12+
- CMake or Projucer

Clone the repository

git clone https://github.com/qutschwalze/upmixer.git
cd upmixer
Initialize submodules (if needed)

git submodule update --init --recursive
Build with CMake

cmake -B build -G Xcode
cmake --build build --config Release
                

## 📄 Licensing & Commercial Use

This project is open-source software licensed under the **GPLv3 License**.

- **Open Source:** You are free to use, modify, and distribute this software under the terms of the GNU General Public License v3.0.
- **Commercial Integration:** If you wish to use this code in a proprietary (closed-source) commercial product, please contact me for a commercial license agreement.

## 🤝 Contributing

Contributions are welcome!
1. Fork the project.
2. Create your feature branch (`git checkout -b feature/NewAlgo`).
3. Commit your changes.
4. Open a Pull Request.

---
*Developed by Quetschwalze in Aßlar, Hessen.*

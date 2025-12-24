# [Plugin Name] - Stereo to Surround Upmixer

![Platform](https://img.shields.io/badge/platform-macOS-lightgrey)
![Framework](https://img.shields.io/badge/framework-JUCE-orange)
![Format](https://img.shields.io/badge/format-VST3%20|%20AU-blue)
![License](https://img.shields.io/badge/license-GPLv3-green)

**[Plugin Name]** is a VST3 and Audio Unit (AU) audio plugin designed to upmix stereo sources into immersive multichannel formats (5.1, 7.1). Built with the [JUCE Framework](https://juce.com/) specifically for macOS audio production workflows.

## 🎛 Features

- **Real-time Upmixing:** Low-latency conversion from Stereo to 5.1/7.1 Surround [web:1][web:8].
- **Spatial Control:** Adjust width, depth, and center channel divergence.
- **LFE Management:** Dedicated low-frequency effects processing and crossover control.
- **Visual Feedback:** Real-time goniometer and level metering for all output channels.

## 🛠 Tech Stack

- **Language:** C++ (C++17 or higher recommended)
- **Framework:** JUCE 7/8
- **Formats:** VST3, AU (Audio Unit)
- **Platform:** macOS (Universal Binary: Apple Silicon & Intel)

## 🚀 Installation

### Pre-built Binaries
1. Go to the [Releases](https://github.com/dein-username/dein-repo/releases) page.
2. Download the latest `.pkg` or `.zip` file for macOS.
3. Install the plugin or manually copy files to:
   - **VST3:** `/Library/Audio/Plug-Ins/VST3/`
   - **AU:** `/Library/Audio/Plug-Ins/Components/`

### Building from Source

To build this project, you need **Xcode** and **CMake** (or the Projucer) installed.

#### Prerequisites
- macOS 10.15+ (Catalina or newer)
- Xcode 12+
- JUCE Framework (installed or via submodule)

#### Using CMake (Recommended)


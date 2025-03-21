# 🚀 i3blocks Configuration

A sleek and efficient **i3blocks** setup for displaying system information in the i3bar. Includes essential indicators like **CPU usage, battery level, volume, brightness, and weather** for an improved workflow.

## ✨ Features
- 🎵 **Volume Control** – Displays current audio level.
- 🌤 **Weather** – Shows real-time weather updates.
- 🔆 **Brightness Indicator** – Adjust screen brightness easily.
- ⚡ **Battery Status** – Monitors battery level and charging status.
- 🔥 **CPU Usage** – Displays system load in real-time.

## 📂 Installation

Copy the configuration file to your i3blocks config directory:

```sh
mkdir -p ~/.config/i3blocks
cp i3blocks.conf ~/.config/i3blocks/config
```
then in the i3 config set:
```config
bar {
    status_command i3blocks
    ...
}
```

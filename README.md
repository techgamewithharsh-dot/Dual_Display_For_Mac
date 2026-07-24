<div align="center">
  <img src="icon.png" width="128" height="128" style="border-radius:24px;" alt="Dual Monitor For Mac">
  <h1>Dual Monitor For Mac</h1>
  <p><b>The ultimate zero-lag screen mirroring app. Turn your iPhone or iPad into a 120 FPS, 4K secondary display for your Mac.</b></p>
</div>

<br>

## Overview

Dual Monitor For Mac allows you to extend or mirror your macOS screen to your iOS devices natively with unparalleled performance. By utilizing direct hardware encoding (VideoToolbox) and direct USB tunneling (via `usbmuxd`), it achieves zero-perceivable latency, outperforming standard AirPlay and Wi-Fi solutions.

**[🌐 Visit the Website](https://YOUR_USERNAME.github.io/YOUR_REPO/)**

## Features

- **⚡️ Zero Latency USB Connection:** Bypass spotty Wi-Fi completely. Connect via a standard USB cable for true 0-lag performance.
- **🎮 120 FPS & 4K Ready:** High-framerate hardware accelerated H.264 decoding allows buttery smooth 120Hz display on ProMotion iPhones/iPads.
- **🔒 100% Private & Local:** All video and audio streams are routed strictly over local TCP/USB tunnels. No cloud servers, no data harvesting.
- **🔊 Audio Forwarding:** Routes your Mac's audio directly to your iPhone speakers for a complete multimedia experience.

## Download & Installation

Because the Mac Host app utilizes raw USB tunneling to communicate with the iPhone without latency, it cannot be hosted on the Mac App Store (which requires strict sandboxing that blocks these daemons). 

Therefore, the app is split into two parts:

### 1. Mac Host App (The Server)
1. Go to the [Releases](https://github.com/YOUR_USERNAME/YOUR_REPO/releases) page of this repository.
2. Download the latest `DualMonitorForMac.dmg`.
3. Open the `.dmg` and drag the app into your **Applications** folder.

### 2. iOS Client App (The Display)
1. Download **Dual Monitor For Mac** from the iOS App Store. *(Link coming soon)*

## Setup Instructions

1. Ensure both apps are installed.
2. **(Highly Recommended)** Connect your iPhone or iPad to your Mac using a USB Lightning or USB-C cable.
3. Open the **Dual Monitor For Mac Host** app on your Mac (you will see an icon in your top menu bar).
4. Open the **Dual Monitor For Mac** app on your iOS device.
5. Select your Mac from the discovery list.
6. Enter the 4-digit security PIN displayed on your Mac menu bar into the iOS app.
7. Your screen will instantly begin mirroring!

---

### Need Help?
If you encounter any issues, please open an Issue on this repository or check your Privacy settings on macOS to ensure the app has Screen Recording permissions.

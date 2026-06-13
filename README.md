# Apletty Desktop Control (ADC)

A cross-network remote desktop control application that enables real-time screen streaming, hardware monitoring, and full input control over a local or virtual private network.

> 🚧 **Active Development**  Core features are functional. UI polish and additional features are in progress.

---

## Features

- **Screen Streaming**: Real-time screen capture and display with JPEG compression over TCP
- **Mouse & Keyboard Control**: Full remote input control with event forwarding
- **Live Hardware Monitoring**: Real-time CPU, RAM, disk usage, device name, and battery status
- **Camera Streaming**: Live webcam feed streamed from the remote host
- **Live Chat**: Built-in text chat between controller and host during a session
- **Power Management**: Remote shutdown, restart, and sleep commands with countdown warning UI
- **Splash Screen**: Animated startup screen with custom branding



## Tech Stack
- **Language**: Java, C#
- **UI Framework**: JavaFX
- **Input Simulation**: Java AWT Robot
- **Hardware Monitoring**: WMI (Windows Management Instrumentation)
- **Communication**: TCP Socket
  - `9898` — Main Socket
  - `9797` — Camera Socket
  - `8787` — Full Control Socket
  - `8889` — Keyboard Press & Release
  - `8888` — Mouse Move & Click

## Screenshots

<img width="1052" height="741" alt="Screenshot 2026-06-13 094733" src="https://github.com/user-attachments/assets/70a2fa44-2750-4479-b768-a270f5943f35" />
<img width="1050" height="767" alt="Screenshot 2026-06-13 094648" src="https://github.com/user-attachments/assets/91638717-a50a-41a9-9e6e-c72dc8ef7ac8" />
<img width="1157" height="760" alt="Screenshot 2026-06-13 094549" src="https://github.com/user-attachments/assets/34c00145-ced3-45ba-9fd3-6f33df01b1d6" />
<img width="1155" height="763" alt="Screenshot 2026-06-13 094533" src="https://github.com/user-attachments/assets/112b537f-7907-4424-ad43-d15ecaf99df3" />
<img width="571" height="869" alt="Screenshot 2026-06-13 094522" src="https://github.com/user-attachments/assets/197a6cac-1570-419b-a268-3474d0f64f7b" />
<img width="1159" height="758" alt="Screenshot 2026-06-13 094513" src="https://github.com/user-attachments/assets/4038e010-df93-473e-9b3c-ae6816a4d2b3" />
<img width="579" height="862" alt="Screenshot 2026-06-13 094458" src="https://github.com/user-attachments/assets/6ca828a0-20e7-4f1c-aa1c-0070282d8a91" />
<img width="1151" height="759" alt="Screenshot 2026-06-13 094433" src="https://github.com/user-attachments/assets/3dea72e8-0561-4ae7-837c-ff6bdce01875" />


## Download

Head to the https://github.com/Zeldryn/Apletty-Desktop-Control/releases page to download the latest version.

### System Requirements

- Windows 10 / 11
- Both devices connected on the same network, or via VPN (e.g. ZeroTier / Tailscale)

---

## Network Setup

ADC works over any network where both machines can reach each other via IP:

- **Local Network (LAN)**: Works out of the box
- **Virtual Private Network**: Tested with [ZeroTier](https://www.zerotier.com) and [Tailscale](https://tailscale.com)

---

## Author

**Zeldryn**
Informatics Student — Universitas Bina Sarana Informatika (BSI)
Building toward a career in software/systems engineering.

---

## License

This project is currently unlicensed. All rights reserved.

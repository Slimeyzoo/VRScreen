# 🎥 VRScreen – Screen Sharing in WebVR using WebRTC (PeerJS)

**VRScreen** is a browser-based tool that allows users to share their desktop screen in real-time via a peer-to-peer connection, and view the stream inside a WebVR environment using [A-Frame](https://aframe.io/) and [PeerJS](https://peerjs.com/).

## 🌟 Features

- 🔗 Peer-to-peer connection using WebRTC (via PeerJS)
- 🖥️ Share your screen with others directly in the browser
- 🌐 Display the stream on a virtual screen in VR
- 🎛️ Adjust screen size and distance in VR space

## 🛠️ Built With

- HTML, CSS, JavaScript
- [A-Frame 1.4.2](https://aframe.io/)
- [PeerJS 1.5.4](https://peerjs.com/)

## 🚀 How It Works

1. Open `index.html` in a modern web browser (Chrome recommended).
2. A Peer ID is generated automatically.
3. Share this ID with your partner.
4. One peer shares their screen, the other receives the stream.
5. Use the sliders to adjust the virtual screen size and distance.

## 🧪 Test Locally

1. Open `index.html` in two tabs or browsers.
2. Share your Peer ID between tabs.
3. Start screen sharing from one, and receive it on the other.

> **Note:** Works only over HTTPS or on `localhost`.

## 📁 File Overview

```plaintext
index.html   # Main file with UI, logic, and A-Frame scene

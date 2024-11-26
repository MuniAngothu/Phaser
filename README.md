# RPG Front-End with Real-Time Updates using Phaser.js

---

## **Note**
This project assignment was initially incomplete due to the following reasons:
- **Time Constraints:** Balancing exams and training sessions limited my ability to dedicate sufficient time to the project.
- **Learning Curve:** Phaser.js required additional learning time, and while I understood backend concepts (like WebSockets), I faced challenges implementing them effectively.
- **Resource Limitations:** Lack of assets and other resources hindered the creation of a polished UI.
- **Testing Challenges:** Basic testing of the frontend and backend was conducted, but the UI failed to load properly during integration.

Despite these setbacks, I managed to demonstrate some **basic Phaser.js implementations** and gained foundational knowledge of backend integration with WebSockets. I have created this **README.md** as a detailed guide for completing this project in the future. I am committed to revisiting this assignment and delivering a fully functional product once my schedule permits.

Thank you for your understanding!

---

## Overview
This project is a simple RPG game built using **Phaser.js** for the front-end and WebSockets for the back-end. The goal is to create an interactive environment where users can:
- Control avatars in real-time.
- View other users' movements simultaneously.
- Receive updates when new users join the game.

The assignment emphasizes **code ownership**, **self-motivation**, and adherence to **best practices**.

---

## Features

### Front-End
- **Built with Phaser.js**: Provides a rich and interactive game environment.
- **Single-Level RPG**: Includes collision detection and interactable objects.
- **Custom Assets**: Assets implemented with AI and integrated seamlessly into the game.
- **Avatar Interaction**: Players can move avatars and interact with in-game objects.

### Back-End
- **Real-Time Updates**: Uses WebSockets to synchronize player movements and notify of new joiners.
- **Spawn Points**: Displays spawn locations for new players in real-time.
- **User Interaction**: Tracks and updates movement events live.

### Additional Goals
- Explore **video architectures** and **Selective Forwarding Units (SFUs)**.
- Research and discuss popular SFU implementations and their use cases.

---

## Installation and Setup

### Prerequisites
- Node.js (>= 16.x)
- npm or yarn
- Phaser.js
- A WebSocket server (e.g., Socket.io)

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-repo/rpg-phaser-project.git
   cd rpg-phaser-project

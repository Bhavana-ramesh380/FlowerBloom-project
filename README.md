# 🌸 Flower Bloom – Hand Gesture Controlled Interactive Flower

An interactive web application that uses **real-time hand gesture recognition** to control the growth and blooming of a procedurally generated flower. The project leverages **MediaPipe Hands**, **HTML5 Canvas**, and **JavaScript** to create a smooth, visually appealing experience directly in the browser.

---

## 📌 Project Overview

Flower Bloom is an AI-powered browser application that tracks your hand movements using your webcam and transforms those gestures into beautiful flower animations.

Instead of clicking buttons or using a mouse, users interact with the flower naturally through hand gestures.

The application detects:
- 🌸 Flower Bloom Level
- 🌱 Flower Growth
- 🌬️ Wind Effect

All animations are rendered in real-time using the HTML5 Canvas API.

---

## ✨ Features

- 🎥 Real-time webcam access
- ✋ AI hand tracking using MediaPipe Hands
- 🌸 Gesture-controlled flower blooming
- 🌱 Dynamic flower growth animation
- 🌬️ Wind effect based on hand movement
- ✨ Floating particle animations
- 🍃 Animated leaves and branches
- 💡 Glow and lighting effects
- 📱 Responsive full-screen interface
- ⚡ Smooth 60 FPS animation

---

# 🛠 Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- HTML5 Canvas API
- MediaPipe Hands
- Webcam API

---

# 📂 Project Structure

```
FlowerBloom/
│
├── index.html
├── style.css
└── app.js
```

---

# 🚀 How It Works

```
User Opens Website
        │
        ▼
Camera Permission Requested
        │
        ▼
MediaPipe Starts Hand Detection
        │
        ▼
Hand Landmarks Detected
        │
        ▼
JavaScript Processes Gestures
        │
        ▼
Canvas Updates Flower Animation
        │
        ▼
Flower Responds in Real Time
```

---

# 🎮 Gesture Controls

## 🌸 Left Hand – Bloom Control

Move your **thumb** and **index finger** apart to increase blooming.

Pinch your fingers together to close the flower.

```
Thumb + Index

👌
```

---

## 🌱 Right Hand – Growth Control

Move your **thumb** and **index finger** apart.

The flower stem grows taller.

Pinch again to reduce growth.

---

## 🌬️ Wind Effect

Move either hand quickly from left to right or right to left.

The flower naturally sways with the generated wind.

---

# 🌺 Flower Components

The flower is procedurally drawn using the Canvas API.

It includes:

- Stem
- Leaves
- Branches
- Main Flower
- Side Flowers
- Glow Effects
- Floating Particles

No images are used.

Everything is generated dynamically using JavaScript.

---

# 🎥 Application Workflow

```
Start Application
        │
        ▼
Initialize Canvas
        │
        ▼
Initialize Webcam
        │
        ▼
Load MediaPipe Model
        │
        ▼
Detect Hands
        │
        ▼
Recognize Gestures
        │
        ▼
Calculate
    • Bloom
    • Growth
    • Wind
        │
        ▼
Render Flower
        │
        ▼
Update Animation
        │
        ▼
Repeat Every Frame
```

---

# ▶️ How to Run

### Clone or Download

```bash
git clone https://github.com/yourusername/FlowerBloom.git
```

or simply download the ZIP file.

---

### Open Project

Open the folder in **Visual Studio Code**.

---

### Install Live Server

Install the **Live Server** extension.

---

### Run

Right-click **index.html**

Select

```
Open with Live Server
```

Allow webcam permission when prompted.

---

# 📋 Requirements

- Google Chrome / Microsoft Edge / Firefox
- Webcam
- Internet connection (required for MediaPipe CDN)

---

# 💻 Future Enhancements

- Multiple flower species
- Rain animation
- Butterfly interaction
- Background music
- Gesture customization
- Flower color selection

---

# 📸 Preview

```
        🌸
      🌸🌸🌸
        │
      🍃│🍃
        │
        │
        │
```

The flower blooms, grows, and sways naturally according to the user's hand gestures.

---

If you found this project helpful, feel free to ⭐ the repository.

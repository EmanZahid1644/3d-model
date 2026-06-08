# Hand Tracking with Virtual Buttons

A browser-based hand tracking application built using **TensorFlow.js** and the **Handpose Model**. The application uses a webcam to detect hand landmarks in real time and allows users to interact with virtual on-screen buttons using hand movements.

## 🚀 Features

* Real-time webcam hand tracking
* Hand landmark detection using TensorFlow.js
* Interactive virtual buttons
* Visual feedback when a hand hovers over a button
* Mirrored webcam view for natural interaction
* Debug logging through browser console
* Responsive fullscreen canvas

---

## 🛠️ Technologies Used

* HTML
* Handpose Model
* WebRTC (Camera Access)

---

## 📸 How It Works

1. The browser requests webcam access.2
2.The model detects hand landmarks in real time.
3. Detected landmarks are displayed as red dots.
4. Virtual buttons are drawn on the screen.
5. When a hand landmark enters a button area:

   * The button changes color.
   * Hover detection is triggered.

---

## 📂 Project Structure

```text
hand-tracking-project/
│
├── index.html
├── README.md
│
└── assets/
    └── screenshots/
```

---

## ▶️ Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-username/hand-tracking-project.git
cd hand-tracking-project
```

### Run the Project

Simply open the `index.html` file in a modern browser.

Or use a local development server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

---

## 📋 Requirements

* Modern browser (Chrome, Edge, Firefox)
* Webcam access enabled
* Internet connection (for CDN libraries)

---

## 🎯 Functionality

### Hand Detection

The application detects:

* Palm position
* Finger joints
* Fingertips
* Hand movement

### Virtual Buttons

Three interactive buttons are displayed:

| Button        | Color  |
| ------------- | ------ |
| Left Button   | Blue   |
| Center Button | Green  |
| Right Button  | Orange |

When a hand landmark hovers over a button, its color changes to **red**.

---

## 🧠 TensorFlow Libraries

The project loads:

```html
<script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs-core@3.14.0"></script>
<script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs-converter@3.14.0"></script>
<script src="https://cdn.jsdelivr.net/npm/@tensorflow-models/handpose@0.0.7"></script>
```

---

## 🔧 Future Improvements

* Click gesture detection
* Finger pinch interactions
* Sound effects on hover
* Button actions and navigation
* Multi-hand tracking support
* Game and educational applications
* Gesture-based controls

---

## 🎓 Learning Objectives

This project demonstrates:

* Computer Vision in the Browser
* TensorFlow.js Integration
* Real-Time Hand Tracking
* Canvas Rendering
* Webcam Access using WebRTC
* Interactive Gesture-Based UI Design

---

## 👨‍💻 Author

**Eman Zahid**


---

## 📜 License

This project is developed for educational and learning purposes.

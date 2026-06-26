# 🎨 Air Drawing Studio

Draw in the air using your webcam and hand gestures.

**Air Drawing Studio** is a browser-based hand gesture drawing application that transforms your hand movements into digital artwork. Using **MediaPipe Hands**, the application detects finger gestures in real time, allowing you to draw, erase, and move strokes without touching your screen.

The application runs entirely in your browser, ensuring that webcam processing and drawings remain on your device without requiring a backend server.

---

## ✨ Features

* ✋ Real-time hand tracking using MediaPipe Hands
* 🎨 Draw naturally with your index finger
* 🧽 Erase strokes using a two-finger gesture
* 🤏 Move existing drawings with a pinch gesture
* 📤 Export drawings as point data
* 🖥️ Modern, responsive dashboard
* ⚡ Fast and lightweight browser-based experience
* 🔒 Client-side processing for enhanced privacy

---

## 🎮 Gesture Controls

| Gesture                       | Action                |
| ----------------------------- | --------------------- |
| ☝️ Index Finger               | Draw                  |
| ✌️ Index + Middle Finger      | Erase nearby strokes  |
| 🤏 Thumb + Index Finger Pinch | Move existing strokes |

---

## 📂 Project Structure

```text
Air-Drawing-Studio/
│
├── assets/               # Images and UI assets
├── js/
│   ├── scriptent.js      # Camera & gesture detection
│   └── strokes.js        # Stroke management
├── index.html            # Main application
├── stylent.css           # Application styling
└── README.md
```

---

## 🚀 Getting Started

1. Clone the repository.

```
git clone https://github.com/yourusername/Air-Drawing-Studio.git
```

2. Open the project folder.

3. Launch `index.html` using a local web server (recommended).

4. Allow browser access to your webcam.

5. Start drawing using the supported hand gestures.

---

## 💡 Tips for Best Performance

* Use the application in a well-lit environment.
* Keep your hand fully visible to the camera.
* Maintain a steady distance from the webcam.
* Avoid overlapping fingers during gestures.
* Use a plain background whenever possible for improved tracking.

---

## 🛠️ Built With

* HTML5
* CSS3
* JavaScript
* MediaPipe Hands
* Canvas API

---

## 📌 Future Enhancements

* Additional gesture shortcuts
* Custom brush styles and colors
* Undo and redo support
* Shape drawing tools
* Dark and light theme switching
* Save drawings as PNG or SVG
* Touchscreen support

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Developed by **Your Name**

If you found this project useful, consider giving it a ⭐ on GitHub.

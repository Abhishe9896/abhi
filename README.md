# Gesture-Controlled Virtual Mouse

The Gesture-Controlled Virtual Mouse** is an innovative project that simplifies human-computer interaction by using hand gestures and voice commands to perform mouse operations. It eliminates the need for traditional hardware like a mouse, offering a contactless and intuitive user experience.

---

## 📜 Features

- **Hand Gesture Recognition**: Detects and interprets hand gestures in real-time.
- **Voice Command Integration**: Enables voice-based control for additional functionalities.
- **Customizable Input Modes**: Supports both bare-hand detection and glove-based detection.
- **High Accuracy**: Uses advanced machine learning models (CNN) for precise gesture recognition.
- **Platform Support**: Works seamlessly on Windows systems.

---

## 🔧 Technologies Used

### **Programming Language**
- Python

### **Libraries and Tools**
- **MediaPipe**: Real-time hand tracking and gesture recognition.
- **OpenCV**: Image processing and computer vision.
- **Pybind11**: Binding C++ with Python for performance optimization.
- **Numpy & Pandas**: Data manipulation and numerical computations.

### **Machine Learning**
- Convolutional Neural Networks (CNN) for gesture classification.

---

## ⚙️ How It Works

1. **Hand Detection Module**:
   - Captures video input using a webcam.
   - Detects hand landmarks using MediaPipe and tracks movements.

2. **Gesture Recognition Module**:
   - Maps hand gestures to mouse actions (e.g., left-click, right-click, drag, scroll).

3. **Voice Command Module** (Optional):
   - Recognizes voice inputs to execute commands.

4. **Execution**:
   - Integrates gesture and voice inputs to control the virtual mouse.

---

## 🚀 Installation & Setup

### Prerequisites
- Python 3.7 or higher
- Webcam for gesture detection

### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Gesture-Controlled-Virtual-Mouse.git
   cd Gesture-Controlled-Virtual-Mouse

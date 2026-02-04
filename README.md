# virtual-air-keyboard
# ✨ Virtual Air Keyboard using Hand Gestures

A futuristic computer vision project that allows users to type in the air without touching a physical keyboard.  
This system uses **MediaPipe Hand Tracking** and **OpenCV** to detect finger movements and convert them into keyboard inputs in real-time.

## 🚀 Features
✅ Touchless typing using hand gestures  
✅ Real-time hand tracking with MediaPipe  
✅ Pinch gesture to press keys  
✅ Open palm gesture to delete text  
✅ Smooth glass-style virtual keyboard UI  
✅ Supports letters, numbers, and symbols  
✅ Backspace and Space functionality  
✅ Cursor blinking effect  
✅ Toggle between symbols and letters  
✅ Fully contactless interaction  

## 🧠 How It Works
1. The webcam captures live video.
2. MediaPipe detects 21 hand landmarks.
3. The system tracks the **index finger** as a cursor.
4. A **pinch gesture** (thumb + index finger) is recognized as a key press.
5. An **open palm hold** deletes characters.
6. Typed text is displayed on the screen in real-time.

This project demonstrates the power of **Computer Vision** and **Human-Computer Interaction (HCI)**.

## 🛠️ Technologies Used
- **Python**
- **OpenCV**
- **MediaPipe Tasks API**
- **NumPy**

## 📂 Project Structure
```

AirKeyboard/
│
├── models/
│     hand_landmarker.task
│
├── air_keyboard.py
└── README.md

````

## ⚙️ Installation
### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/virtual-air-keyboard.git
cd virtual-air-keyboard
````
### 2️⃣ Install dependencies
```bash
pip install opencv-python mediapipe numpy
```
### 3️⃣ Download MediaPipe Model
Download the hand landmark model:

👉 [https://storage.googleapis.com/mediapipe-models/hand_landmarker/hand_landmarker/float16/1/hand_landmarker.task](https://storage.googleapis.com/mediapipe-models/hand_landmarker/hand_landmarker/float16/1/hand_landmarker.task)

Create a folder named **models** and place the file inside:
```
models/hand_landmarker.task
```

### 4️⃣ Run the project
```bash
python air_keyboard.py
```
Press **Q** to quit.

## 🎮 Controls / Gestures

| Gesture                  | Action                |
| ------------------------ | --------------------- |
| 👉 Move Index Finger     | Hover over keys       |
| 🤏 Pinch (Thumb + Index) | Press key             |
| ✋ Open Palm (Hold)       | Delete text           |
| 🔤 Symbols Key           | Switch keyboard       |
| 🔙 Backspace             | Remove last character |

## 💡 Applications
* Touchless interfaces
* Smart classrooms
* Public kiosks
* AR/VR environments
* Assistive technology
* Future human-computer interaction systems

## 🔮 Future Improvements
⭐ Add predictive text
⭐ Sound feedback on key press
⭐ Multi-language support
⭐ AI auto-correction
⭐ Gesture customization
⭐ Mobile version
⭐ Dark mode UI


```

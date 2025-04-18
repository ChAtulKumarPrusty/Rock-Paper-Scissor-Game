# 🖐️ Rock Paper Scissors with Hand Gestures (OpenCV + cvzone)

An interactive Rock-Paper-Scissors game where you play against an AI using just your hand gestures! Built with Python, OpenCV, and the `cvzone.HandTrackingModule`.


---

## 🎮 Features

- Real-time hand detection using your webcam
- Gesture recognition for:
  - ✊ Rock (all fingers down)
  - ✋ Paper (all fingers up)
  - ✌️ Scissors (only index and middle finger up)
- AI randomly chooses a move
- Scores are tracked live on a game board
- Engaging UI with background and overlay graphics

---

## 🛠️ Tech Stack

- Python 🐍
- OpenCV 🎥
- cvzone ✋
- MediaPipe (via cvzone)
- NumPy

---

## 📦 Installation

### 1. Clone the Repository

git clone https://github.com/ChAtulKumarPrusty/Rock-Paper-Scissor-Game.git
cd rock-paper-scissors-gesture

2. Install Dependencies
Make sure you have Python 3.7+ installed.
pip install opencv-python cvzone numpy

3. Add Resources
Download and add the following files to the Resources/ folder:
BG.png – The main game background
1.png, 2.png, 3.png – AI gesture images (Rock, Paper, Scissors)

📁 Your folder structure should look like this:
rock-paper-scissors-gesture/
├── Resources/
│   ├── BG.png
│   ├── 1.png
│   ├── 2.png
│   └── 3.png
├── main.py
└── README.md

🚀 Run the Game
python main.py

Press S to start a round. After a 3-second countdown, show your hand gesture to play against the AI!

🤖 AI Move Logic
The AI move is randomly selected from Rock, Paper, or Scissors.
🧠 Hand Detection Logic
fingersUp() method checks which fingers are raised.
Based on the pattern, it maps to:
[0, 0, 0, 0, 0] → Rock
[1, 1, 1, 1, 1] → Paper
[0, 1, 1, 0, 0] → Scissors

👨‍💻 Author
Your Name – @ChAtulKumarPrusty

⭐️ Show Your Support
If you like this project, give it a ⭐️ and consider sharing it! Feel free to fork and improve it with new features like:
Multiple rounds
Gesture customization
Multiplayer support

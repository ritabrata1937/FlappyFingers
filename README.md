# FlappyFingers (Flappy Bird with OpenCV Hand Tracking)

## Project Overview

This is a unique implementation of the classic Flappy Bird game that uses computer vision and hand tracking to control the game.
Instead of traditional keyboard or mouse controls, players can now navigate the bird by moving their hand in front of a camera.

🎮 Game Features

- Classic Flappy Bird gameplay
- OpenCV-based hand tracking controls
- Real-time finger movement detection
- Interactive and innovative control mechanism
- Customizable difficulty levels

🛠 Technologies Used

- Python
- Pygame
- OpenCV
- NumPy
- Mediapipe (Optional: for advanced hand tracking)

🔧 Prerequisites

- Python 3.7+
- pip package manager

📦 Installation

Install required dependencies.

pip install pygame opencv-python numpy mediapipe

🎮 How to Play

Position yourself in front of the camera.
Move your hand/fingers up and down to control the bird.
Avoid hitting pipes and stay in the game.
Aim for the highest score!
To close the game window move your open palm and move it upwards.

🖐️ Hand Tracking Mechanism
The game uses OpenCV to:

Detect hand position
Track finger movements
Translate hand gestures into game controls


📸 Screenshots

📝 License
Distributed under the MIT License. See LICENSE for more information.

🙌 Acknowledgments

Pygame Community
OpenCV Developers
Original Flappy Bird Creators

🐛 Known Issues

Lighting conditions might affect hand tracking accuracy
Requires a webcam for gameplay

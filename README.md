# Hand_gestures
Project Overview
This repository hosts a robust Computer Vision program that enables users to control specific keyboard inputs using real-time hand gestures. This system is designed for practical applications, such as improving accessibility or providing a novel input method for PC games.

The current implementation is optimized to simulate the Left (←) and Right (→) arrow key presses, making it ideal for controlling simple driving or side-scrolling games (e.g., Hill Climb Racing).

⚙️ Core Technology Stack
This program is built entirely in Python, leveraging powerful machine learning and computer vision libraries:

Language: Python 3.8.3

Computer Vision Framework: OpenCV (cv2)

Hand Tracking: Google MediaPipe (Used for highly accurate, real-time hand landmark detection)

✨ Key Functionality
Real-time Hand Tracking: Utilizes MediaPipe to accurately detect the position and geometry of the user's hand.

Gesture Mapping: Specific hand movements or poses are mapped directly to standard keyboard events (e.g., moving the hand left simulates the ← key).

fist closed - left arrow (continious)
open hand - right arrow (continious)

Application Control: The program can reliably control applications and games that rely on standard keyboard arrow inputs.

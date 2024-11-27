# Hand Gesture Recognition for Chrome Dinosaur Game

A real-time hand gesture recognition system built with OpenCV to control the Chrome Dinosaur game. The system uses computer vision to detect hand gestures and triggers in-game actions like jumping via automated key presses using DirectKeys.

## Features
- **Real-Time Detection**: Detects hand gestures in real-time using a webcam.
- **Game Control**: Controls the Chrome Dinosaur game with gestures.
- **Automation**: Uses DirectKeys to simulate key presses for smooth gameplay.

## Tools and Technologies
- **Programming Language**: Python
- **Libraries**: OpenCV, cvzone, NumPy, Time
- **Key Press Automation**: DirectKeys

## How It Works
1. Captures live video feed using OpenCV.
2. Detects hand gestures with `cvzone`'s `HandDetector`.
3. Triggers specific actions based on the detected finger configuration:
   - **Thumb up**: Jump.
   - **Closed fist**: No jump.
   - **Other gestures**: Normal movement (no jump).
4. Sends key press signals to the game using DirectKeys.

## Prerequisites
- Python 3.7+
- Webcam
- Chrome Dinosaur game (playable offline or via [this link](chrome://dino))


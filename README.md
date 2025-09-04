Hand Gesture Game Controller

This project allows you to control games such as CS2 using hand gestures detected through your webcam. It uses OpenCV, cvzone’s HandTrackingModule, and pynput to map hand gestures to keyboard and mouse inputs.

Features

Detects hand gestures via webcam.

Maps gestures to keyboard inputs for controlling movement.

Supports mouse clicks for in-game actions.

Exit gesture to close the program safely.

Gesture Mappings
Gesture	Action
Index finger up	Press and hold W
Index and middle fingers up	Press and hold S
Thumb up	Press and hold A
Index, middle, and ring up	Press and hold D
Fist (all fingers down)	Left mouse click
Open palm (all fingers up)	Exit the program
Requirements

Python 3.x

OpenCV

cvzone

pynput

Install dependencies with:

pip install opencv-python cvzone pynput

How to Run

Clone this repository.

Ensure your webcam is connected.

Run the script:

python hand_gesture_controller.py


Use the defined hand gestures to control your game.

Notes

The detection works best in a well-lit environment.

Some games may require running the script with administrator permissions to allow simulated key presses.

Gesture recognition depends on webcam quality and hand visibility.

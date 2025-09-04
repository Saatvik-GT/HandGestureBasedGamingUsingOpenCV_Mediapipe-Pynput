Gesto-Game: A Gesture-Based Gaming Controller
Gesto-Game is a Python script that turns your webcam into a virtual controller, allowing you to play games using natural hand gestures. By leveraging computer vision, it detects specific hand poses and translates them into keyboard presses and mouse clicks, offering a unique and engaging way to interact with your PC.

The project is built with the cvzone library for hand detection and pynput for controlling the keyboard and mouse. It’s perfect for anyone interested in exploring the intersection of computer vision and gaming.

Features
Gesture-to-Key Mapping: Control your games with intuitive hand movements.

Dynamic Control: Press and hold keys for continuous movement.

Mouse Click: Perform left mouse clicks with a simple fist gesture.

Graceful Exit: A specific hand gesture allows you to exit the program cleanly.

Prerequisites
Before you can run the script, make sure you have Python installed on your system. You will also need the following libraries:

opencv-python

cvzone

pynput

Installation
You can install the required libraries using pip:

pip install opencv-python
pip install cvzone
pip install pynput

Usage
Clone this repository or copy the code into a local file (e.g., gesto_game.py).

Open your command line or terminal.

Navigate to the directory where you saved the file.

Run the script:

python gesto_game.py

Allow camera access. The script will start detecting your hand and the corresponding actions will be triggered.

Gesture Guide
Gesture

Action

Index Finger Up

Press and hold W

Index + Middle Finger Up

Press and hold S

Thumb Up

Press and hold A

Index + Middle + Ring Finger Up

Press and hold D

Fist (all fingers down)

Left mouse click

Open Palm (all fingers up)

Exit the program

Contributing
Feel free to fork the repository and contribute! Whether it's adding new gestures, optimizing performance, or fixing bugs, all contributions are welcome.

License
This project is licensed under the MIT License.

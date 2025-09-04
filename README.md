# Hand Gesture Game Controller  

This project allows you to control games such as CS2 using hand gestures detected through your webcam. It uses OpenCV, cvzone’s HandTrackingModule, and pynput to map hand gestures to keyboard and mouse inputs.  

## Features  

1. Detects hand gestures via webcam.  
2. Maps gestures to keyboard inputs for controlling movement.  
3. Supports mouse clicks for in-game actions.  
4. Exit gesture to close the program safely.  

## Gesture Mappings  

| Gesture                        | Action              |  
|--------------------------------|---------------------|  
| Index finger up                | Press and hold W    |  
| Index and middle fingers up    | Press and hold S    |  
| Thumb up                       | Press and hold A    |  
| Index, middle, and ring up     | Press and hold D    |  
| Fist (all fingers down)        | Left mouse click    |  
| Open palm (all fingers up)     | Exit the program    |  

## Requirements  

- Python 3.x  
- OpenCV  
- cvzone  
- pynput  

Install dependencies with:  
```bash
pip install opencv-python cvzone pynput
```  

## How to Run  

1. Clone this repository.  
2. Ensure your webcam is connected.  
3. Run the script:  
```bash
python hand_gesture_controller.py
```  
4. Use the defined hand gestures to control your game.  

## Notes  

- The detection works best in a well-lit environment.  
- Some games may require running the script with administrator permissions to allow simulated key presses.  
- Gesture recognition depends on webcam quality and hand visibility.  

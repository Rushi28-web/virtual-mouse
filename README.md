# virtual-mouse
This project uses OpenCV, MediaPipe, and PyAutoGUI to recognize hand gestures from your webcam and control your computer.
You can move the mouse, click, scroll, change volume, adjust brightness, and more — all without touching your mouse or keyboard.

Features
Cursor Control – Move your hand to control the mouse pointer.
Click Actions – Single-click, double-click, and right-click via gestures.
Drag and Drop – Grab and move windows or files.
Volume Control – Adjust system volume using pinch gestures.
Brightness Control – Change screen brightness with pinch gestures.
Scrolling – Vertical and horizontal scroll using pinch gestures.
Multi-Hand Support – Detects left and right hand separately

Requirements
Make sure you have Python 3.7+ installed, then install the dependencies:
pip install opencv-python mediapipe pyautogui pycaw comtypes screen-brightness-control google.protobuf

| Gesture Name          | Action                       |
| --------------------- | ---------------------------- |
| ✌ V-Gesture           | Move mouse cursor            |
| ✊ Fist                | Click and hold (drag)        |
| ☝ Index               | Right click                  |
| ✌ (two-finger closed) | Double click                 |
| Pinch (Minor hand)    | Scroll (vertical/horizontal) |
| Pinch (Major hand)    | Volume / Brightness control  |


How to Run
Clone the Repository

Install dependencies
pip install -r requirements.txt

Run the program
python mouse.py

Use your webcam
Stand in front of the camera with good lighting.

demo:-
<img width="668" height="572" alt="image" src="https://github.com/user-attachments/assets/a7e8582d-16e7-4dc5-9a76-aff2ca4ea249" />

Use the gestures from the table above to control your PC.
Press Enter to exit.

# Hand Gesture Mouse Control

This Python script utilizes the MediaPipe library to detect hand gestures from the webcam feed and control the mouse cursor accordingly. It allows the user to set a start and end point on the screen and control the mouse cursor within that region using hand gestures.

## Prerequisites

Before running the script, ensure you have the following dependencies installed:

- Python 3.x
- OpenCV (`pip install opencv-python`)
- MediaPipe (`pip install mediapipe`)
- Autopy (`pip install autopy`)
- PyAutoGUI (`pip install pyautogui`)

## Usage

1. Clone the repository or download the script.
2. Ensure your webcam is connected and accessible.
3. Run the script using the command `python hand_gesture_mouse_control.py`.
4. Follow the instructions to set the start and end points on the screen.
5. Perform hand gestures to control the mouse cursor within the defined region.
6. Press 'Esc' to exit the script.

## Script Overview

- The script captures video from the webcam and processes it to detect hand gestures using the MediaPipe library.
- It allows the user to set a start and end point on the screen by clicking with the left and right mouse buttons, respectively.
- The script tracks hand movements within the defined region and moves the mouse cursor accordingly.
- Hand gestures are interpreted to perform mouse clicks when appropriate.
- Pressing 'Esc' during execution quits the script.

## Acknowledgments

- This script utilizes the MediaPipe library for hand gesture detection and the Autopy library for mouse control.
- Special thanks to the OpenCV and PyAutoGUI communities for providing robust computer vision and automation tools.
  
## References

- [MediaPipe](https://mediapipe.dev/)
- [OpenCV](https://opencv.org/)
- [Autopy](https://pypi.org/project/autopy/)
- [PyAutoGUI](https://pyautogui.readthedocs.io/)

Feel free to modify and extend this script according to your requirements! If you have any questions or suggestions, please feel free to reach out.

# Hand-Gesture-Volume-Control

This project demonstrates a computer vision application that allows you to control your laptop's volume using finger gestures. It utilizes the OpenCV and MediaPipe libraries for hand tracking and gesture recognition, and the PyCAW library for system volume control on Windows.

## Features
- Real-time hand tracking using MediaPipe
- Gesture recognition for volume control
- Integration with PyCAW for system volume adjustment
- Simple GUI overlay for visual feedback (optional)

## Requirements
- Python 3.x
- OpenCV
- MediaPipe
- PyCAW

## Installation
1. Clone the repository:
    ```
    git clone https://github.com/karimelhou/hand-gesture-volume-control.git
    ```

2. Install the required Python packages:
    ```
    pip install opencv-python mediapipe pycaw
    ```

## Usage
1. Run the `main.py` script:
    ```
    python main.py
    ```

2. Position your hand in front of the webcam and use gestures to control the volume:
    - Move your thumb and index finger closer together to decrease the volume.
    - Move your thumb and index finger further apart to increase the volume.

## Customization
- Adjust the volume control sensitivity and gesture recognition parameters by tweaking the constants in the code.
- Customize the GUI overlay to display additional information or visual feedback.

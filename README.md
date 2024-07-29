### Hand Gesture Volume Control

This project uses computer vision to control the system volume through hand gestures. By leveraging MediaPipe for hand tracking and PyAutoGUI for volume control, it provides a hands-free way to adjust your computer's volume dynamically based on the distance between your thumb and index finger.

#### Features

- **Real-time Hand Tracking**: Utilizes MediaPipe to accurately detect and track hand movements.
- **Dynamic Volume Control**: Adjusts the system volume based on the distance between the thumb and index finger.
- **Interactive System**: Offers an intuitive and responsive way to control volume without touching the computer.

#### Requirements

- **Python 3.x**
- **OpenCV**: For capturing and processing video from the webcam.
- **MediaPipe**: For detecting and tracking hand landmarks.
- **PyAutoGUI**: For simulating volume control key presses.
- **NumPy**: For numerical operations and distance calculations.

#### Installation
1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-username/hand-gesture-volume-control.git
    cd hand-gesture-volume-control
    ```

2. **Install dependencies**:
    ```sh
    pip install opencv-python mediapipe pyautogui numpy
    ```

#### Usage

1. **Ensure all dependencies are installed**.
2. **Run the script**:
    ```sh
    python hand_gesture_volume_control.py
    ```
3. **Use your thumb and index finger to control the volume**:
    - **Close together**: Volume decreases.
    - **Far apart**: Volume increases.

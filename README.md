# Gesture-Controlled Multimedia Playback and Volume Adjustment System

This project utilizes computer vision techniques to create a gesture-controlled system for multimedia playback and volume adjustment. By detecting hand gestures using a webcam, the system interprets these gestures to control multimedia playback and adjust the volume accordingly.

## Requirements

- Python 3.x
- OpenCV
- PyAutoGUI
- Mediapipe

## Usage

1. Run the script `handgesturevolumecontrol.py`:

    ```bash
    python handgesturevolumecontrol.py
    ```

2. Ensure your webcam is properly set up and facing you.

3. Position your hand in front of the webcam.

4. Perform gestures to control multimedia playback and volume:

    - To increase volume: Bring your thumb and index finger closer together.
    - To decrease volume: Spread your thumb and index finger apart.

5. To exit the application, press the 'Esc' key.

## How it Works

- The program captures video frames from the webcam in real-time.
- It uses the `Mediapipe` library to detect hand landmarks in the video frames.
- Based on the positions of specific landmarks (e.g., thumb and index finger), it interprets gestures to control multimedia playback and adjust volume.
- Multimedia playback control and volume adjustment are achieved using the `PyAutoGUI` library, which simulates keyboard presses.

## Contributing

Contributions are welcome! Feel free to open issues or pull requests for any improvements or bug fixes.



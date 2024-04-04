# GazePoint-Control


This project demonstrates how to control the mouse cursor using eye tracking with Python and OpenCV.

## Setup and Requirements

To run this code, you need Python installed on your system along with the following dependencies:

- OpenCV (`pip install opencv-python`)
- Mediapipe (`pip install mediapipe`)
- PyAutoGUI (`pip install pyautogui`)

## Usage

1. Connect your webcam to the computer.
2. Run the `eye_controlled_mouse.py` script.
3. Position your face in front of the webcam.
4. Move your eyes to control the mouse cursor.
5. Blink to perform a click action.

## Code Explanation

- The script uses OpenCV to capture video frames from the webcam.
- It utilizes the Mediapipe library to detect facial landmarks, particularly the position of the eyes.
- PyAutoGUI is used to control the mouse cursor based on the detected eye movements.
- A click action is triggered when the user blinks their eyes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue to report bugs or suggest improvements.

## Authors

- [Bharath](https://github.com/bharath-shanmugasundaram)

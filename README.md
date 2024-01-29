# AI Virtual Painter

AI Virtual Painter is a Python-based project that allows users to paint virtually using hand gestures captured through a webcam. This project utilizes the Mediapipe library for hand tracking and OpenCV for image processing.

## Features

- Hand tracking: Detects hand landmarks using the Mediapipe library.
- Gesture recognition: Recognizes hand gestures to switch between selection mode and drawing mode.
- Color selection: Users can select different drawing colors by hovering over corresponding color options.
- Brush and eraser functionality: Implements drawing and erasing capabilities based on hand movements.
- Real-time canvas: Displays the drawing canvas and updates in real-time as the user interacts with the application.

## Dependencies

- Python 3.x
- OpenCV (`opencv-python`)
- Mediapipe (`mediapipe`)

## Installation

1. Clone the repository:

   ```
   git clone 'link'
   ```

2. Install the required dependencies:

   ```
   pip install opencv-python mediapipe
   ```

## Usage

1. Run the `VirtualPainter.py` script:

   ```
   python VirtualPainter.py
   ```

2. Ensure your webcam is connected and positioned properly to capture hand movements.

3. Use hand gestures to switch between modes and draw on the canvas:

   - Selection Mode: Use the index and middle fingers to select colors.
   - Drawing Mode: Use the index finger to draw or erase on the canvas.

4. Enjoy painting virtually!

## File Structure

- `HandTrackingModule.py`: Contains the `handDetector` class for hand tracking and gesture recognition.
- `VirtualPainter.py`: Main script that initializes the application and handles user interactions.
- `Header/`: Directory containing images used for color selection.


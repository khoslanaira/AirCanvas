# AirCanvas
AirCanvas: A Real-Time Hand Tracking Paint App
AirCanvas is an interactive Python application that leverages hand tracking to create a virtual painting experience. By using a webcam (or EpocCam) and the power of MediaPipe, users can control their paintbrush with their fingertips, drawing and creating art in real-time.

Features:

1. Hand Tracking: Utilizes MediaPipe's hand detection model to accurately track hand movements and translate them into brush strokes.
2. Multi-Color Painting: Supports four distinct colors (blue, green, red, and yellow) for versatile drawing.
3. Color Selection: Change colors by hovering your thumb over designated areas on the canvas.
4. Clear Canvas: Reset the painting area by hovering your thumb within a specific region.
5. Real-Time Canvas: Seamlessly updates the drawing surface based on hand movements, providing a natural and immersive experience.

Getting Started

Prerequisites:

Python 3.x (Ensure you have the necessary libraries installed: OpenCV, NumPy, MediaPipe)
A webcam (or EpocCam for wireless connection)
Installation:

Clone or download the AirCanvas repository.
Navigate to the project directory in your terminal.
Run pip install -r requirements.txt (if you don't have a requirements.txt file, create one with the necessary libraries listed above).
Run the application:

Execute python AirCanvas.py from your terminal.

Usage:
Open AirCanvas.
Point your hand at the webcam (or EpocCam).
Move your index finger around the screen to draw.
Hover your thumb near the designated color regions (top of the canvas) to switch colors.
Hover your thumb within the clear area (top left corner) to reset the canvas.
Technical Details

AirCanvas leverages the following libraries:
OpenCV: For computer vision tasks like frame capture and image manipulation.
NumPy: For numerical computations and array handling.
MediaPipe: Enables real-time hand detection and landmark tracking.

Customization:
You can experiment with different brush sizes, line styles, and color palettes by modifying the code within the AirCanvas.py file.

Future Enhancements:
Implement additional drawing tools (e.g., eraser, shapes).
Explore options for saving and exporting artwork.
Integrate gesture recognition for more advanced controls.

Contributing:
We welcome contributions to the AirCanvas project! Feel free to fork the repository, make your changes, and submit a pull request.

# Real-Time Multi-Purpose Hand, Body, and Face Tracking using MediaPipe and OpenCV

## Project Overview

Welcome to the "Real-Time Multi-Purpose Tracking with MediaPipe and OpenCV" GitHub repository. This project showcases a highly sophisticated Python script that enables real-time tracking of multiple elements using the powerful combination of the MediaPipe library and OpenCV. By seamlessly integrating the MediaPipe Hand, Pose, and Face Mesh modules, this script provides accurate detection and tracking of landmarks across various subjects within video frames.

## Prerequisites

Before you dive into the project, ensure that your Python environment meets the following prerequisites:

- OpenCV (cv2)
- MediaPipe (mediapipe)
- NumPy (numpy)

To effortlessly install these dependencies, execute the following command:

```sh
pip install opencv-python mediapipe numpy
```

## Key Features

- **Real-Time Hand Tracking:** This script takes advantage of the advanced capabilities of the MediaPipe Hand module to accurately detect and track landmarks on human hands in real-time.

- **Precise Body Pose Estimation:** Leveraging the integrated MediaPipe Pose module, the script provides accurate estimations of both 2D and 3D poses for human bodies.

- **Dynamic Face Mesh Tracking:** The MediaPipe Face Mesh module is seamlessly integrated to dynamically track and trace facial landmarks in real-time.

- **Hand Handedness Detection:** The script goes beyond tracking by identifying whether the detected hand is the left or right one, conveniently displaying this information directly on the video frames.

- **Frames Per Second (FPS) Measurement:** Enjoy the benefit of automatic frames per second (FPS) calculation and display on the video frames, assisting you in gauging real-time performance.

## Excel Integration

For those interested in storing tracking coordinates in an Excel file, we recommend utilizing the `openpyxl` library. This library enables seamless integration with Excel files for data storage and manipulation.

## Upcoming Enhancements

Stay tuned for our continuous efforts in refining and enhancing this multi-purpose tracking script. We are committed to elevating its capabilities and functionalities.

## User Controls

- Exit the application anytime by pressing the 'q' key.

## Acknowledgments

- Our project deeply appreciates the innovation brought forth by Google's MediaPipe library, a key component in realizing this endeavor.

- The codebase driving hand, body, and face tracking, alongside the visualization aspects, builds upon a robust foundation.

## Licensing

This project operates under the permissive MIT License. Detailed information is available in the [LICENSE](LICENSE) file.


We invite contributions, customization, and utilization of this code to meet your specific requirements. If you encounter challenges or possess ideas for further enhancements, feel free to initiate a GitHub issue within our repository. Your engagement is invaluable to us.

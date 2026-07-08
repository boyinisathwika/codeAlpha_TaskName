# codeAlpha_TaskName
# Motion Detection System

## Overview

The Motion Detection System is a computer vision application that detects movement in real-time using a webcam or video feed. It compares consecutive video frames to identify changes and highlights moving objects with bounding boxes.

This project is built using **Python** and **OpenCV**, making it suitable for learning computer vision concepts and developing basic surveillance applications.

---

## Features

- Real-time motion detection
- Webcam and video file support
- Motion highlighted with bounding boxes
- Lightweight and easy to use
- Press **Q** to exit the application

---

## Technologies Used

- Python 3.x
- OpenCV
- NumPy

---

## Project Structure

```
Motion-Detection/
│── motion_detection.py
│── requirements.txt
│── README.md
```

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/motion-detection.git
cd motion-detection
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install opencv-python numpy
```

---

## Usage

Run the application:

```bash
python motion_detection.py
```

If using a video file:

```python
cap = cv2.VideoCapture("video.mp4")
```

For webcam:

```python
cap = cv2.VideoCapture(0)
```

Press **Q** to quit.

---

## How It Works

1. Capture video frames.
2. Convert frames to grayscale.
3. Apply Gaussian Blur to reduce noise.
4. Compute the difference between consecutive frames.
5. Apply thresholding to detect motion.
6. Find contours around moving objects.
7. Draw bounding boxes around detected motion.
8. Display the processed video.

---

## Requirements

- Python 3.8 or higher
- OpenCV
- NumPy
- Webcam (optional)

---

## Applications

- Home security
- Office surveillance
- Smart monitoring systems
- Object movement detection
- Computer vision learning

---

## Future Improvements

- Motion recording
- Email notifications
- Face detection integration
- Object tracking
- Motion sensitivity adjustment
- Cloud storage support

---

## Example Output

```
Motion Detected!
+----------------------+
|      ████████        |
|   Moving Object      |
+----------------------+
```

---

## License

This project is licensed under the MIT License.

---

## Author

Developed by **Your Name**.

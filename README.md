# Face Mask Detection Using MTCNN

This project demonstrates face detection and facial landmark localization using the **MTCNN** (Multi-task Cascaded Convolutional Networks) deep learning model with OpenCV in Python. It includes two main functionalities:

1. Detect faces and facial landmarks on a static image.
2. Real-time face detection from webcam video stream.

---

## Features

- **Static image face detection:** Detects faces and key facial landmarks (eyes, nose, mouth corners) on input images.
- **Real-time webcam detection:** Continuously captures video from the webcam and detects faces in real-time.
- **Visual annotations:** Draws bounding boxes around detected faces and marks facial landmarks with colored circles.
- **Simple and lightweight:** Uses MTCNN for robust and fast face detection without heavy dependencies.

---

## Technologies Used

- [OpenCV (cv2)](https://opencv.org/) — For image and video capture, drawing shapes, and display.
- [MTCNN](https://github.com/ipazc/mtcnn) — Deep learning-based face detection and facial landmark detection.
- Python 3.x

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/face-mask-detection-using-mtcnn.git
   cd face-mask-detection-using-mtcnn

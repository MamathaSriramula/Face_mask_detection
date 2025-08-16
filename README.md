# Face Mask Detection Using Deep Learning

This project implements a real-time **face mask detection system** using computer vision and deep learning. The system detects faces from a webcam feed, classifies them as **"With Mask"** or **"Without Mask"**, and sends an email alert when someone is detected without a mask.

## Features

- **Real-time Detection:** Detects multiple faces in live video.
- **Mask Classification:** Labels faces with confidence scores.
- **Alert Mechanism:** Sends email alerts for unmasked faces with a configurable time interval.
- **Visualization:** Draws bounding boxes around faces (green = masked, red = unmasked).
- **Preprocessing:** Grayscale conversion, histogram equalization, and normalization for improved accuracy.

## Applications

- Monitoring mask compliance in public places (airports, offices, hospitals)
- Automated health and safety alerts
- Integration with IoT or smart surveillance systems

## Technologies Used

- Python
- OpenCV
- TensorFlow / Keras


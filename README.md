# GMM Background Subtraction

This project implements **Gaussian Mixture Model (GMM) Background Subtraction** using OpenCV in Python, typically used in video surveillance and motion detection systems.

## 📌 Overview

Background subtraction is a key technique in computer vision for detecting moving objects in videos. In this project, the **MOG2** algorithm (Mixture of Gaussians version 2) is used to separate the foreground (moving objects) from the static background in a video stream.

This notebook:
- Captures video from a file or webcam.
- Applies GMM-based background subtraction using `cv2.createBackgroundSubtractorMOG2()`.
- Displays the original frame and the corresponding foreground mask in real time.

---

## 🧠 Algorithm Used

**Gaussian Mixture-based Background/Foreground Segmentation Algorithm (MOG2)**  
- Models each background pixel as a mixture of Gaussians.
- Updates the model over time.
- Automatically detects shadows.

---

## 🔧 Requirements

Install dependencies using pip:

```bash
pip install opencv-python numpy

Replace the videos if you wish to in the directory when you pu the code



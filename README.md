# Real-Time Face Detection using OpenCV

This project demonstrates a real-time face detection system using Python and OpenCV. It utilizes the Haar Cascade Classifier to detect faces from webcam video frames.

## 🔍 Features

- Real-time face detection from webcam
- Uses Haar Cascade for facial feature detection
- Highlights detected faces with a bounding box and label
- Simple and lightweight script for beginners

## 🧰 Technologies Used

- Python
- OpenCV (`cv2`)
- Haar Cascade Classifier (`haarcascade_frontalface_default.xml`)


## 🛠️ How It Works

1. Capture real-time video frames using OpenCV.
2. Convert each frame to grayscale.
3. Detect faces using `detectMultiScale()` on the grayscale image.
4. Draw rectangles around detected faces and label them.

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/face-detection-opencv.git
cd face-detection-opencv



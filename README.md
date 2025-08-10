---

# Face-Detection-Model
This is my little machine learning experiment that ended up becoming a real-time face detector. It takes a webcam feed (or an image) and finds human faces with surprising accuracy — thanks to Python, OpenCV, and some good old ML magic.

---

# ✨ What it Does
- Detects faces in real-time from your webcam.

- Works with images and video files too!

- Fast and lightweight — runs on most laptops without GPU.

- Powered by Haar Cascades / OpenCV

---

# 🛠 The Recipe
- Python for the main logic

- OpenCV for image processing and face/image detection

- NumPy for handling arrays and image data

- Keras (model from json) for loading the trained CNN model architecture

- A pre - trained 'HAAR CASCADE' model for detection

---

# 👀 Get the Detector Rolling

## 1. Install Python
- Download Python 3.x from (https://www.python.org/downloads/)

- While installing, tick **"Add Python to PATH"**

## 2. Download the Project

### 1. Clone using Git
git clone https://github.com/SheikhFarhan07/Face-Detection-Model .git

cd Face-Detection-Model

### 2. Download as ZIP
click "Download ZIP" on Github and extract it.

## 3. Install Dependencies
Install dependencies from the requirements file:

pip install -r requirements.txt

## 4. Make Sure the model files are present
Basically the folder should contain:
- facedetector.json (model architecture)
- facedetector.h5 (model weights)
- haarcascade_frontalface_default.xml (comes with OpenCV)

## 5. Run the Project

python realtime_detection.py

- Your webcam will open
- A window will show your face with an emotion label
- Close the window to stop

## 6. Troubleshooting

- If you get **ModuleNotFoundError**, make sure dependencies from Step 3 are installed properly.
- If your webcam doesn't open, try changing cv2.VideoCapture(0) to cv2.VideoCapture(1) in the code.
- **haarcascade_frontalface_default.xml not found**: Ensure the file is in the same folder as your Python script, or update the path in the code.

---

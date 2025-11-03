# 🎥 OpenCV Motion Detection and Object Tracking using Python

This project demonstrates **real-time motion detection and object tracking** using **OpenCV**, **Python**, and **NumPy**.
It processes a video file frame by frame to identify moving objects through **frame differencing**, **thresholding**, and **contour-based detection** techniques.

---

## 🧠 Overview

The system reads consecutive frames from a video, detects motion by comparing them, and draws **bounding boxes** around moving objects.
This approach can be applied in various fields such as:

* 🔒 Security and surveillance systems
* 🚗 Vehicle or human tracking
* 🎥 Smart camera applications
* 📊 Automated video analytics

---

## 🚀 Features

* Frame differencing for detecting motion
* Gaussian blur for noise removal
* Binary thresholding for motion segmentation
* Contour detection and bounding box tracking
* Works with both webcam and video files
* Adjustable threshold via OpenCV trackbar (optional)

---

## 🧩 Tech Stack

* **Python 3.x**
* **OpenCV (cv2)**
* **NumPy**

---

## ⚙️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Shamanthula-Bhavana05/OpenCV-Motion-Detection-and-Object-Tracking-using-Python.git
   cd OpenCV-Motion-Detection-and-Object-Tracking-using-Python
   ```

2. Install dependencies:

   ```bash
   pip install opencv-python numpy
   ```

---

## 🎯 How It Works

1️⃣ Reads two consecutive frames from the video input
2️⃣ Finds their **absolute difference** to detect moving regions
3️⃣ Converts the difference to grayscale and applies **Gaussian blur**
4️⃣ Uses **thresholding** to highlight motion areas
5️⃣ Detects **contours** and draws **bounding boxes** around moving objects

---

## 🖼️ Output Visualization

* 🟩 **Green Contours** → Detected motion regions
* 🟥 **Red Boxes** → Tracked moving objects

---

## 🎬 Demo Video

▶️ **Watch on YouTube:** [OpenCV Motion Detection and Object Tracking using Python](https://youtu.be/mDW6vWGGuNw)

---

## 🔮 Future Enhancements

* Multi-object motion tracking across frames
* Integration with object classification models (e.g., YOLO, SSD)
* Real-time alert or logging system for motion activity

---

## 👩‍💻 Author

**Bhavana Shamanthula**
💡 Passionate about Computer Vision, AI, and Deep Learning
🔗 [LinkedIn](https://www.linkedin.com/in/shamanthula-bhavana-7343bb331)
📂 [GitHub Repository](https://github.com/Shamanthula-Bhavana05/OpenCV-Motion-Detection-and-Object-Tracking-using-Python)


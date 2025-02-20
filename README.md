# Vehicle-tracking-and-Counting-system


## 🚀 Overview
This project is a **Vehicle Tracking and Counting System** built using **OpenCV** and **Python**. It processes video input to detect, track, and count vehicles crossing a predefined line using motion detection techniques.

## 📌 Features
- Detects moving vehicles in a video stream
- Tracks vehicle movement and counts them when they cross a designated line
- Uses **Background Subtraction (MOG2)** for motion detection
- Implements **contour detection** and **bounding boxes** for vehicle tracking
- Displays real-time count overlay on the video

## 🛠️ Technologies Used
- **Python**
- **OpenCV**
- **NumPy**

## 🎯 Prerequisites
Make sure you have Python installed along with the required libraries:

```bash
pip install opencv-python numpy
```

## 📂 Installation & Usage
1. **Clone the repository:**
   ```bash
   git clone https://github.com/ankit1068/vehicle-tracking.git
   cd vehicle-tracking
   ```

2. **Place your video file in the project directory and rename it as `video.mp4`** (or modify the code to use your filename).

3. **Run the script:**
   ```bash
   python vehicle_tracking.py
   ```

4. **Press 'q' to exit the program.**

## 📝 Code Explanation
### **Main Components:**
- **Background Subtraction:** `cv2.createBackgroundSubtractorMOG2()`
- **Grayscale & Blur Processing:** `cv2.cvtColor()`, `cv2.GaussianBlur()`
- **Contour Detection & Filtering:** `cv2.findContours()`
- **Bounding Box Creation:** `cv2.boundingRect()`
- **Vehicle Tracking & Counting:** Tracks object center positions and increments the counter when a vehicle crosses the detection line.

## 📺 Demo
(Add an image or GIF showing the system in action)

## 🔥 Future Improvements
- Implement **YOLO** or **Deep Learning** for better accuracy
- Track vehicle speed and classify vehicle types
- Support real-time **webcam** input

## 🤝 Contribution
Feel free to fork, improve, and submit a **pull request**. Suggestions and improvements are welcome!

## 📜 License
This project is licensed under the MIT License.





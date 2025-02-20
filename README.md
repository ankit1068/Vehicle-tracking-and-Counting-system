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

## 📺 Screenshots
![Screenshot (11)](https://github.com/user-attachments/assets/24201aae-dfbe-4bcc-b9f3-40a66e19052b)
![Screenshot (12)](https://github.com/user-attachments/assets/36f0014a-0baf-4bf7-bc6e-14e9ba1f78e5)
![Screenshot (13)](https://github.com/user-attachments/assets/66fd5b02-dfd3-4d60-a038-e37406bdf76f)


## 🔥 Future Improvements
- Implement **YOLO** or **Deep Learning** for better accuracy
- Track vehicle speed and classify vehicle types
- Support real-time **webcam** input

## 🤝 Contribution
Feel free to fork, improve, and submit a **pull request**. Suggestions and improvements are welcome!

## 📜 License
This project is licensed under the MIT License.
🤝 Contributing
Feel free to fork this repository and submit a pull request if you have any improvements!

## Contact
For any questions or feedback, feel free to contact:

Ankit kumar

Email: your-ankitrajj1068@gmail.com

GitHub: ankit1068





# Real-Time Object Recognition using OpenCV & MobileNet-SSD

This project performs **real-time object recognition using a webcam** with the **MobileNet-SSD deep learning model**.

The system detects multiple objects such as:

- Person
- Car
- Dog
- Cat
- Bicycle
- Bus
- Bottle
- Train
- TV Monitor
- Mobile

The project uses **OpenCV's Deep Neural Network (DNN) module** for fast object detection.

---

## Technologies Used

- Python
- OpenCV
- MobileNet-SSD
- NumPy
- Imutils

---

## Project Structure
object-recognition-opencv
│
├──
│ ├── MobileNetSSD_deploy.caffemodel
│ └── MobileNetSSD_deploy.prototxt.txt

├── 
│ └── main.py

├── requirements.txt
├── README.md


---

## Installation

Clone the repository:

```bash
git clone https://github.com/selvan-01/object-recognition-opencv.git

How It Works: 
The MobileNet-SSD model is loaded using OpenCV DNN.
Webcam frames are captured in real time.
Frames are converted into blobs.
The deep learning model predicts objects.
Bounding boxes and labels are drawn on the detected objects.
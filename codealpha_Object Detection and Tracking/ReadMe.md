# Object Detection and Tracking

## Task Overview

This project is developed as part of **Task 3: Object Detection and Tracking** under the **Artificial Intelligence Internship Program at CodeAlpha**.

The objective of this task is to build a real-time object detection and tracking system using computer vision and deep learning techniques. A pre-trained YOLO model is used to detect objects in video frames, and tracking is applied to maintain object identities across frames.

In this implementation, **biscuits** are used as the target objects for detection and tracking.

---

## Features

* Real-time video input using **OpenCV**
* Object detection using a **pre-trained YOLO model**
* Bounding boxes drawn around detected objects
* Object tracking with unique **tracking IDs**
* Real-time display of detection results with labels
* Works with webcam or video file input

---

## Technologies Used

* Python
* OpenCV
* YOLO (You Only Look Once)
* NumPy
* Deep Learning
* Computer Vision

---

## Project Structure

```
codealpha_Object Detection and Tracking/
│
├── model/                 # YOLO model files
├── utils/                 # Helper functions (if any)
├── main.py                # Main detection and tracking script
├── requirements.txt       # Required libraries
└── README.md              # Project documentation
```

---

## Installation & Setup

1. Clone the repository:

```bash
git clone https://github.com/NithiinSathya07/codealpha_tasks.git
```

2. Navigate to the project directory:

```bash
cd codealpha_Object Detection and Tracking
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## How It Works

1. The webcam/video feed is captured using OpenCV.
2. Each frame is passed through the YOLO model for object detection.
3. Detected objects are enclosed with bounding boxes.
4. Tracking logic assigns a unique ID to each detected object.
5. Labels and tracking IDs are displayed in real time.

---

## Output

* Real-time video stream
* Bounding boxes around detected biscuits
* Object labels and tracking IDs displayed on screen

---

## Demo

A **working model demo video** has been created to showcase real-time detection and tracking performance.

---

## GitHub Repository

🔗 [https://github.com/NithiinSathya07/codealpha_tasks/tree/main/codealpha_Object%20Detection%20and%20Tracking](https://github.com/NithiinSathya07/codealpha_tasks/tree/main/codealpha_Object%20Detection%20and%20Tracking)

---

## Internship Details

**Artificial Intelligence — Internship Program**
CodeAlpha is a leading software development company focused on innovation and emerging technologies. This AI internship provides hands-on experience in AI model development, machine learning workflows, and real-time data processing with expert mentorship.

---

## Author

**U Nithin Sathya**
Artificial Intelligence Intern
🔗 LinkedIn: [https://www.linkedin.com/in/u-nithin-sathya-abc123/](https://www.linkedin.com/in/u-nithin-sathya-abc123/)

---

## Acknowledgment

Thanks to **CodeAlpha** for providing the opportunity to work on real-world AI and computer vision projects as part of this internship.

# DRIVER DROWSINESS DETECTION SYSTEM
 This repository contains a Drowsiness Detection System built using Python, OpenCV, and a Convolutional Neural Network (CNN) model. The system monitors a person’s eyes via a webcam and detects signs of drowsiness by classifying the state of the eyes (open or closed). If the system identifies drowsiness based on a threshold score, it triggers an alert to help prevent accidents or hazardous situations.
## TABLE OF CONTENTS
- [Project Overview](#project-overview)
- [System Workflow](#system-workflow)
- [Project Prerequisites](#project-prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-Used)
- [Future Enhancements](#future-enhancements)
- [Contributors](#contributors)
## Project Overview
Drowsiness detection is crucial in scenarios like driving, where a lack of alertness can lead to serious accidents. This project leverages deep learning and computer vision techniques to determine whether a person’s eyes are open or closed. By continuously monitoring the state of the eyes, the system calculates a score to indicate the person’s drowsiness level. This project can be integrated into safety applications to reduce incidents caused by fatigue.


![5wepheyf](https://github.com/user-attachments/assets/7157de13-a434-423e-9054-882cb8d6f756)

![image](https://github.com/user-attachments/assets/d1ebc53b-2d6e-4848-b8e2-7cbfe0b31261)

## System Workflow
The system follows these steps to detect drowsiness:

1.Capture Image: Obtain real-time images from the webcam.

2.Face Detection: Identify and create a Region of Interest (ROI) around the face.

3.Eye Detection: Detect the eyes within the ROI and feed them into the classifier.

4.Classification: The classifier categorizes the eyes as either open or closed.

5.Drowsiness Score Calculation: Based on consecutive frames, a score is calculated to determine if the person is drowsy.

## Project Prerequisites
To run this project, you need a webcam for capturing real-time images. Install Python (version 3.6 recommended) and use pip to install the required packages:
1. **OpenCV** - For face and eye detection:
    ```bash
    pip install opencv-python
    ```
2. **TensorFlow** - The backend for Keras:
    ```bash
    pip install tensorflow
    ```
3. **Keras** - To build and train the CNN model:
    ```bash
    pip install keras
    ```
## **Installation**
1. Clone the Repository:
    ```bash
    git clone https://github.com/yourusername/Drowsiness-Detection-System.git
    cd Drowsiness-Detection-System
    ```
2. **Install Dependencies:** Install the necessary libraries if not already installed:
    ```bash
    pip install -r requirements.txt
    ```
3. **Run the System:**
    ```bash
   driver_drowsiness_detection1.ipynb
    ```
## Usage
1. **Start Webcam**: The script automatically activates the webcam and begins capturing frames.
2. **Drowsiness Detection**: The model processes the frames, detects the eyes, and classifies their state.
3. **Alert System**: When the score exceeds a certain threshold indicating drowsiness, an alert can be triggered (e.g., sound alarm).

## Technologies Used

**Python**: Core programming language for developing the application.
**OpenCV**: Library for computer vision tasks like face and eye detection.
**Keras & TensorFlow**: For building and training the CNN model.

## Output
![Screenshot 2024-11-16 164947](https://github.com/user-attachments/assets/77e83586-de51-4b5e-ba9b-e1b68f8ee357)


## Future Enhancements
**Improved Alert System**: Implement an audio alarm or haptic feedback for real-world scenarios.
**Multimodal Detection**: Combine eye tracking with other indicators like head position or yawning detection.
**Real-Time Optimization**: Optimize model performance for real-time applications on low-power devices.
## Contributors
- GAURAV











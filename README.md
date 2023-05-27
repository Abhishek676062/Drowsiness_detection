# Real-time Drowsiness Detection System

This repository contains code and resources for a real-time drowsiness detection system for drivers. The system is designed to alert the driver if they are falling asleep or experiencing fatigue while driving, helping to prevent accidents caused by drowsy driving.

# Requirements

To run the code in this repository, you need to have the following dependencies installed:
```
Python 
OpenCV 
NumPy
Dlib 
SciPy
Playsound 
```
You can install the required packages using pip:
```
pip install opencv-python numpy dlib scipy playsound
```
# Dataset

A dataset specifically for drowsiness detection is not included in this repository. However, the system can be trained on various datasets. The dataset should consist of images or videos labeled with drowsiness and alertness frames.

# Model

The drowsiness detection system utilizes a combination of facial landmarks detection and eye aspect ratio (EAR) calculation to determine if the driver's eyes are closing or showing signs of drowsiness. The dlib library is used for facial landmarks detection, and the EAR is calculated based on the position of specific facial landmarks.

# Usage

To run the real-time drowsiness detection system, follow these steps:

Ensure that your webcam or video source is properly connected and accessible.

Adjust the configuration parameters in the config.py file, such as the video source (webcam or file) and detection thresholds.

Run the drowsiness_detection.py script to start the system:
```
python drowsiness_detection.py
```
The system will capture frames from the video source, analyze the driver's eyes, and determine if drowsiness is detected.

If drowsiness is detected, an alert sound will be played to alert the driver.

# Customization

The system can be customized and enhanced in several ways:

Fine-tuning the detection thresholds in the config.py file to adjust the sensitivity of the drowsiness detection.

Implementing additional detection mechanisms, such as head pose estimation or driver behavior analysis, to improve accuracy.

Integrating the system with other driver assistance technologies or alarm systems for enhanced safety.

# License

The code and resources in this repository are available under the MIT License.

# Acknowledgements

The system utilizes the dlib library for facial landmarks detection. Please refer to the dlib documentation for more details.

The dataset used for training or testing the system is not included in this repository. Please refer to the appropriate dataset source for licensing and usage terms.Acknowledgements

The system utilizes the dlib library for facial landmarks detection. Please refer to the dlib documentation for more details.

The dataset used for training or testing the system is not included in this repository. Please refer to the appropriate dataset source for licensing and usage terms.

# References
[https://www.researchgate.net/publication/353109539_Driver_Drowsiness_Detection_and_Alert_System]

For any questions or inquiries, please contact [shabhishek055@gmail.com].

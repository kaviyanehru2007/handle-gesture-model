 Task Description
This project focuses on developing a hand gesture recognition system that can accurately identify and classify different hand gestures from image data. The model enables intuitive human–computer interaction and can be extended to gesture-based control systems.
Dataset
Dataset Name: Leap Gesture Recognition Dataset
Source: Kaggle
Link: https://www.kaggle.com/gti-upm/leapgestrecog
 Dataset Structure
Copy code

leapGestRecog/
├── 00/
│   ├── 01_palm/
│   ├── 02_l/
│   ├── 03_fist/
│   ├── 04_fist_moved/
│   ├── 05_thumb/
│   ├── 06_index/
│   ├── 07_ok/
│   ├── 08_palm_moved/
│   ├── 09_c
│   └── 10_down/
├── 01/
├── 02/
└── ...
Each folder represents a different hand gesture class.
Technologies Used
Python
OpenCV
NumPy
Scikit-learn
Scikit-image (HOG)
Matplotlib
tqdm
 Algorithm Used
Support Vector Machine (SVM)
Linear kernel
Supervised multi-class classification
Works efficiently with extracted features
Feature Extraction
HOG (Histogram of Oriented Gradients)
Captures edge and shape information of hand gestures
 Project Workflow
Load gesture images from dataset
Convert images to grayscale
Resize images to fixed dimensions
Extract HOG features
Encode gesture labels
Split dataset into training and testing sets
Train SVM classifier
Evaluate model performance
 Installation
Install required dependencies using:
Copy code
Bash
pip install numpy opencv-python scikit-learn scikit-image matplotlib tqdm
 How to Run
Download and extract the dataset from Kaggle
Place the dataset folder in the project directory
Run the Python script:
Copy code
Bash
python hand_gesture_recognition.py
 Future Enhancements
Real-time gesture recognition using webcam
CNN-based deep learning implementation
Gesture-based application control
Improve accuracy using data augmentation
 Conclusion
This project demonstrates how traditional machine learning techniques combined with effective feature extraction can solve real-world computer vision problems like hand gesture recognition.

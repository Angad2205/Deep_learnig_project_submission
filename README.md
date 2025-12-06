# Deep_learnig_project_submission
# Hand Gesture Recognation using CNN

A simple deep-learning project built during the “Deep Learning & Applications” course.  
This implements a Convolutional Neural Network (CNN) to classify static hand-gesture images. The model is trained on a custom dataset and demonstrates gesture recognition performance.

---

## What is this about

Computers, robots or smart devices can work with humans more naturally when they understand hand gestures.  
This project aims to build a system that — given an image of a hand gesture — classifies it correctly.  
It’s useful for sign-language interpretation, touchless interaction, robotics input, and more.  

---

## What’s inside the repo

| File / Notebook | Purpose |
|-----------------|---------|
| `hand_gesture_recognition.ipynb` | Data preprocessing, model definition, training & evaluation scripts |
| `DL_Micro_Project_report.pdf` | Detailed project report (motivation, design choices, results, discussion) |
| `README.md` | This file — overview and usage guide |

---

## Quick Start / How to run

1. Clone this repository  
   ```bash
   git clone https://github.com/Angad2205/Deep_learnig_project_submission.git
   cd Deep_learnig_project_submission

## Model & Results

This project uses a Convolutional Neural Network (CNN) with a simple and effective architecture designed for static hand-gesture classification.  
The model includes:

- Convolution layers for feature extraction  
- Pooling layers for spatial down-sampling  
- Dropout layers for regularization  
- Dense layers for final classification  

The dataset was split into **training, validation, and test** partitions to ensure proper evaluation.

## Results

<img width="940" height="525" alt="image" src="https://github.com/user-attachments/assets/9751dd37-2f23-474f-8e44-6442c086a3ca" />
<img width="940" height="525" alt="image" src="https://github.com/user-attachments/assets/7bf9b7b9-1dd8-42b4-b13a-18fe17d54fe1" />


**Training performance highlights:**

- Achieved a final accuracy in the range of **96–98%**  
- Accuracy improved quickly in the early epochs  
- Validation accuracy closely followed training accuracy  
- Training and validation loss curves remained smooth  
- Minimal overfitting observed  

Training graphs for both accuracy and loss are available in the notebook, showing stable convergence and strong generalization.

---

## Why This Project Matters

This project demonstrates the full deep-learning workflow:

- Data preprocessing  
- Model design  
- Training  
- Evaluation  
- Interpretation of results  

It introduces the core ideas of **computer vision through CNNs**, making it a great foundation for anyone learning image-based deep learning.  
Hand-gesture recognition is widely applicable in:

- Sign-language translation  
- Human–computer interaction  
- Robotics control  
- Touchless interfaces  
- Smart systems and IoT applications  

---

## Future Directions

There are several meaningful directions to extend this project:

### **1. Real-Time Gesture Detection**
Integrate the model with a webcam feed using **OpenCV** or **MediaPipe** to perform real-time gesture recognition.

### **2. Dynamic Gesture Recognition**
Move beyond static images by recognizing gesture sequences. This can be done using:

- CNN + LSTM  
- GRU networks  
- 3D CNNs  
- MediaPipe Holistic tracking  

### **3. Transfer Learning**
Improve accuracy and reduce training time using pretrained models such as:

- ResNet  
- MobileNet  
- EfficientNet  

### **4. Mobile Deployment**
Convert the trained model into **TensorFlow Lite** for deployment on:

- Android apps  
- IoT devices  
- Edge computing hardware  

This would allow lightweight, on-device inference without needing cloud support.

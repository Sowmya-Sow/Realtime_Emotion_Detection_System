# Realtime_Emotion_Detection_System
Real-time emotion detection system using computer vision and deep learning to analyze facial expressions from live webcam input. Detects faces, processes them through a CNN model, and displays predicted emotions instantly on screen.

![Status](https://img.shields.io/badge/status-Completed-brightgreen)
![Tech](https://img.shields.io/badge/Python-ComputerVision-blue)
![Model](https://img.shields.io/badge/Model-CNN-orange)
![Framework](https://img.shields.io/badge/Framework-TensorFlow-yellow)

---

## 📌 Overview

Human emotions play a critical role in communication and decision-making. This project builds a real-time emotion detection system using computer vision and deep learning to analyze facial expressions from live webcam input.

The system detects faces, processes facial features, and predicts emotions instantly, demonstrating how AI can interpret human expressions in real-world scenarios.

---

## 🎯 Objectives

🔹 Detect human faces in real-time using computer vision  
🔹 Preprocess facial regions for model input  
🔹 Load and utilize a trained deep learning model  
🔹 Predict emotions from facial expressions  
🔹 Display real-time emotion labels on video feed  
🔹 Build an end-to-end AI pipeline from input to prediction  

---

## ⚙️ Key Capabilities

### 1. Face Detection

- Uses Haar Cascade Classifier (OpenCV)  
- Detects faces from live webcam feed  
- Draws bounding boxes around detected faces  

---

### 2. Image Preprocessing

- Converts frames to grayscale  
- Resizes images to 48x48 pixels  
- Normalizes pixel values  
- Formats input for CNN model  

---

### 3. Deep Learning Model

- Pre-trained CNN model (`Emotion_Detection.h5`)  
- Predicts emotion probabilities  
- Selects highest probability class  

---

### 4. Real-Time Prediction

- Captures live video stream  
- Processes each frame instantly  
- Displays predicted emotion on screen  

---

### 5. Emotion Classification

Supported emotions:

- Angry  
- Happy  
- Neutral  
- Sad  
- Surprise  

---

## 🧭 System Pipeline

Webcam Input  

   ↓  

Face Detection (OpenCV)  

   ↓  

Preprocessing (Grayscale + Resize + Normalize)  

   ↓  

CNN Model Prediction  

   ↓  

Emotion Label Output  

---

## 🧰 Technology Stack

🔹 Python  
🔹 OpenCV  
🔹 TensorFlow / Keras  
🔹 NumPy  

---

## 🤖 Model Details

Model Type: Convolutional Neural Network (CNN)  

Input Shape: 48 × 48 grayscale images  

Output: Emotion class probabilities  

---

## 📊 Sample Output

- Real-time video window  
- Face bounding box  
- Emotion label displayed above face  

Example:

🙂 → Happy  
😐 → Neutral  
😠 → Angry  

---

## 💼 Use Cases

### For Data & AI Applications

- Emotion-aware AI systems  
- Human-computer interaction  
- Behavioral analysis  

### For Businesses

- Customer experience analysis  
- Retail sentiment monitoring  
- Interactive kiosks  

### For Healthcare

- Mental health monitoring  
- Patient emotion tracking  

---

## 🧪 How to Run

1. Clone the repository  

2. Install dependencies:

```bash
pip install tensorflow==2.10 numpy==1.23.5 opencv-python
```

3. Ensure files are in the same directory:

- test.py  
- Emotion_Detection.h5  
- haarcascade_frontalface_default.xml  

4. Run the project:

```bash
python test.py
```

5. Press **q** to exit  

---

## ⚠️ Limitations

- Limited to predefined emotion classes  
- Accuracy depends on lighting and face visibility  
- No confidence threshold filtering  
- Cannot detect complex emotions or sarcasm (humans struggle with that too)  

---

## 🧠 Key Takeaways

🔹 Real-time AI systems combine computer vision and deep learning  
🔹 Preprocessing is critical for accurate predictions  
🔹 CNN models can effectively capture facial features  
🔹 Even simple pipelines can deliver impactful applications  

---

## 🚀 Future Improvements

🔹 Add confidence score display  
🔹 Support multiple faces simultaneously  
🔹 Deploy using Streamlit or web app  
🔹 Improve model accuracy with better datasets  
🔹 Add emotion logging and analytics  

---

## 📊 Dataset

Model trained on facial expression datasets 

- Grayscale facial images  
- Emotion-labelled data  

---


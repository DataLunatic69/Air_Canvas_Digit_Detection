# **Emotion Classifier using DistilBERT**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)


## **Table of Contents**
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Training the Model](#training-the-model)
- [Model Performance](#model-performance)
- [License](#license)

---

## **Overview**

The Digit Recognition project uses a trained Convolutional Neural Network (CNN) model to recognize digits drawn by hand using webcam input. The application employs hand landmarks for real-time digit drawing and prediction, leveraging the MNIST dataset.


---

## **Features**
- Real-time digit drawing recognition using a webcam.
- Hand gesture detection for user interaction (drawing, clearing canvas).
- High accuracy digit prediction using a pre-trained CNN model.
- Simple GUI integrated with OpenCV for visual feedback.

---

## **Installation**

### **1. Clone the Repository**
```bash
git clone https://github.com/your-username/digit-recognition-hand-gestures.git
cd digit-recognition-hand-gestures
```
### **2. Install Dependencies**
```bash
pip install -r requirements.txt
```
### **3. Download Pretrained Models**
```bash
Ensure you have the trained model dense_model.h5 in the project directory or train it using the provided script.

```



## **Usage**

### **1.Run the Application**
```bash
python digit_recognition.py


```
### **2.Drawing and Predictions**
```bash
Use your index finger to draw digits on the canvas.
Raise your middle finger to stop drawing.
Raise all fingers to clear the canvas.
The predicted digit will be displayed on the screen.


```

## **Train the model**


```bash
python train_digit_classifier.py --epochs 5 --batch_size 32 --lr 1e-3



```

## **Model Performance**
```bash

Metric              Value
-----------------------------
Test Accuracy       98.2%



```



### **License**
```bash
This project is licensed under the MIT License. See the LICENSE file for more details.

```















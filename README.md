
# Fish Classifier App

# matsyan-the-innovators
# 🐟 Fish Classifier App

An AI-powered mobile application that identifies different species of fish from images using a Convolutional Neural Network (CNN) model deployed with TensorFlow Lite on Android.

---

## ❓ Problem Statement

Accurately identifying fish species is important for environmental monitoring, sustainable fishing, and educational purposes. Manual identification is often time-consuming and error-prone. This project aims to automate the classification process using computer vision and deep learning techniques, making it accessible via a simple mobile application.

---

## 🚀 Features

- Classifies fish images into multiple species using a trained CNN model
- Fast on-device inference using TensorFlow Lite
- Simple and intuitive Android interface
- Real-time prediction and result display

---

## 🛠️ Tech Stack Used

| Category            | Tools / Frameworks Used                         |
|---------------------|-------------------------------------------------|
| **Frontend**         | Android Studio, Java                           |
| **Backend (ML Model)**| TensorFlow, Keras, Python                      |
| **Model Deployment** | TensorFlow Lite                                |
| **Image Processing** | OpenCV, PIL                                    |
| **Version Control**  | Git, GitHub                                    |

---

## 📁 Project Structure

<pre> ``` FishClassifierApp/ ├── app/ # Android app source code │ ├── java/ │ │ └── com.example.fishclassifierapp/ │ │ ├── MainActivity.java │ │ └── FishClassifier.java │ └── res/ │ ├── layout/ │ └── drawable/ ├── model/ # Machine Learning model files │ ├── fish_model.tflite │ └── labels.txt ├── assets/ # Additional resources ├── README.md # Project documentation └── .gitignore ``` </pre>
---

## 📦 Installation & Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/fish-classifier-app.git
2. Open the project in Android Studio.

3. Place the trained model fish_model.tflite and labels.txt inside the assets/ folder.

4. Build and run the application on an Android device or emulator (API level 21+).
---

## ▶️ How to Run the Project
1. Launch the app on your Android device.

2. Capture or select an image of a fish.

3. The app will process the image and display the predicted species.

---

## 🌐 Live Deployment
Currently only available as an Android APK. Download APK

---
## Youtube Video Link
[Fish Classifier App Demo](https://youtu.be/tJTXbNDRkfg)

---
## 📊 Project Presentation

[Click here to view the PPT presentation](https://github.com/Glitchtrap991/matsyan-the-innovators/raw/main/FishClassifierPPT.pptx)

---
## 💡 Future Improvements
1. Expand dataset to include more fish species

2. Integrate camera real-time prediction

3. Add confidence scores and explainability

---
## 📄 License
This project is open-source and available under the MIT License.
---

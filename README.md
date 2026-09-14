# Deepfake Detection System

## 📌 Project Overview

Deepfake Detection System is a final-year project developed to identify manipulated or deepfake digital content using Artificial Intelligence and Machine Learning techniques.

The project focuses on detecting whether a given media input is **Real** or **Deepfake** and provides a mechanism for verifying the integrity and authenticity of the generated detection result.

## 🎯 Objectives

* Detect manipulated or deepfake content using AI/ML techniques.
* Process input data and extract relevant features for detection.
* Classify content as Real or Deepfake.
* Provide reliable detection results.
* Improve the trustworthiness of AI-generated detection results through cryptographic verification.

## 🛠️ Technologies Used

* Python
* Machine Learning
* Artificial Intelligence
* Computer Vision / Deep Learning
* NumPy
* Pandas
* OpenCV
* Scikit-learn
* Cryptography
* ECDSA
* Git & GitHub

## 🔄 Project Workflow

```text
Input Media
     ↓
Data Preprocessing
     ↓
Feature Extraction
     ↓
AI/ML Detection Model
     ↓
Real / Deepfake Classification
     ↓
Result Generation
     ↓
Cryptographic Verification
     ↓
Verified Detection Result
```

## 🔐 Cryptographic Verification

The system incorporates the **Elliptic Curve Digital Signature Algorithm (ECDSA)** to provide integrity and authenticity verification for detection results.

The cryptographic layer helps ensure that the generated result has not been modified after it has been produced.

## ✨ Key Features

* AI-based deepfake detection
* Data preprocessing and analysis
* Automated classification
* Detection result generation
* Cryptographic signature generation
* ECDSA-based verification
* Structured and reproducible workflow

## 📂 Project Structure

```text
DeepfakeDetection_FinalYrProject/
│
├── src/
│   ├── main.py
│   └── detection.py
│
├── models/
├── data/
├── outputs/
├── screenshots/
├── requirements.txt
├── .gitignore
└── README.md
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Saipoobbathy/DeepfakeDetection_FinalYrProject.git
```

Navigate to the project directory:

```bash
cd DeepfakeDetection_FinalYrProject
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ How to Run

Run the main application:

```bash
python src/main.py
```

Follow the instructions provided by the application to provide the required input and obtain the detection result.

## 📊 Results

The system analyzes the provided input and generates a classification result indicating whether the content is **Real** or **Deepfake**.

Add screenshots of the application and sample detection results in the `screenshots/` folder.

## 🚀 Future Enhancements

* Improve detection accuracy using larger and more diverse datasets.
* Support additional media formats.
* Implement real-time deepfake detection.
* Explore advanced deep learning architectures.
* Develop a web-based interface.
* Improve model robustness against emerging deepfake generation techniques.

## 👨‍💻 Author

**Sai Poobbathy M**

B.Tech Information Technology
Sri Manakula Vinayagar Engineering College, Puducherry

* GitHub: https://github.com/Saipoobbathy
* LinkedIn: https://www.linkedin.com/in/saipoobbathy

## 📜 License

This project is developed for academic and educational purposes.

# 🧠 Facial Recognition Module for Indoor Navigation System

This repository contains the **Facial Recognition** component of the larger project:  
[🔗 Computer Vision-Based Voice-Assisted Indoor Navigation System](https://github.com/yourusername/indoor-navigation](https://github.com/abhishekanand0811/Computer-Vision-Based-Voice-Assisted-Indoor-Navigation-System)

It is designed to identify users in real-time using facial recognition techniques and personalize the indoor navigation experience accordingly.

---

## 🔍 Features

- 👤 Real-time Face Detection using Haar Cascades
- 🧬 Face Recognition using FaceNet Embeddings
- 🧠 Embedding Generation & Management
- 🔐 Identity Verification and User Personalization
- 📦 Modular code that integrates seamlessly with the main navigation system

---

## 🛠️ Tech Stack

| Component         | Technology      |
|------------------|-----------------|
| Face Detection    | OpenCV (Haar Cascades) |
| Face Recognition  | FaceNet (TensorFlow/Keras) |
| Embedding Storage | Pickle / NumPy Arrays |
| Language          | Python          |
| Integration       | Main repo via inter-process communication or API call |

---

## 📁 Repository Structure

facial-recognition-module/src
├── face_trainer.py # Trains the model
├── face_recognizer.py # Loads embeddings and performs recognition
├── face_taker.py # For registering new users
├── __init__.py # Helper functions
├── embeddings/ # Stores facial data
├── requirements.txt
└── README.md

---

## ⚙️ Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/facial-recognition-module.git
   cd facial-recognition-module/src
   
2. **Install dependencies:**
   ```bash
    pip install -r requirements.txt

3. **Register a New User**
   ```bash
    python face_taker.py
     
4. **Train the model with the new faces:**
   ```bash
    python face_trainer.py

5. **Test the model**
   ```bash
     python face_recognizer

---


## 🔗 Integration with Main Project
This module is plug-and-play. Once a face is recognized, the user identity can be passed to the main system to:

- Load user-specific settings or preferences

- Adjust navigation flow

- Provide contextual voice guidance

---

## Main Project Repository:
🔗 Computer-Vision-Based-Voice-Assisted-Indoor-Navigation-System (https://github.com/abhishekanand0811/Computer-Vision-Based-Voice-Assisted-Indoor-Navigation-System)
Integrate Facial Recognition with this ☝️ project to achieve a complete Navigation System.
---

## 🧩 Future Enhancements
- Face mask detection

- Emotion detection for dynamic assistance

- Secure cloud-based face embedding storage

- GUI-based user registration interface

---

## 🤝 Contributing
Contributions are welcome! Please open issues for bugs or enhancement suggestions.

---

## 📜 License
MIT License
© 2025 Abhishek Anand & Team, Amrita Vishwa Vidyapeetham
---

Empowering navigation through intelligent recognition ✨

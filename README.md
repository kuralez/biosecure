# 🛡️ Biosecure Project

## 📖 Overview
Biosecure is a biometric authentication and interaction application utilizing facial and hand gesture recognition through Google’s Mediapipe framework. This project provides a secure, contactless solution for authentication and interaction in domains like secure access control and accessibility technologies.

## ✨ Features
- **🧑‍🦰 Facial Recognition**: Real-time facial landmark detection for secure identity verification.
- **✋ Hand Gesture Recognition**: Supports intuitive gestures like thumbs-up, open palm, and fist for contactless control.
- **🔒 Privacy-Focused**: Local data processing ensures no biometric data is stored, protecting user privacy.

## 🛠️ Technology Stack
- **📷 Mediapipe**: Powers facial and hand gesture recognition models.
- **🎥 OpenCV**: Manages video capture and preprocessing.
- **🐍 Python**: Primary language used to integrate Mediapipe, OpenCV, and application logic.
- **🔠 TensorFlow** (optional): Enables additional model adjustments if needed.

## 📲 Installation

1. **Download the APK**:
   - Download the latest APK file from the [Releases](https://github.com/kuralez/biosecure/releases) section in this repository.

2. **Install the APK**:
   - On your Android device, go to **Settings** > **Security** > enable **Unknown Sources** to allow the installation of apps from sources other than the Google Play Store.
   - Open the APK file and follow the on-screen instructions to install.

3. **Run the Application**:
   - Open the Biosecure app on your device and grant any necessary camera and storage permissions for optimal performance.

## 💻 Usage
1. **Facial Recognition**: Upon launch, the app will detect and verify your face in real-time.
2. **Gesture Control**: Use gestures (e.g., thumbs-up, open palm) for interaction without physical contact.

## 📂 Directory Structure
```plaintext
biosecure/
├── README.md              # Project Documentation
├── main.py                # Main application code
├── models/                # Model files for recognition
│   ├── face_model/
│   └── hand_model/
└── resources/
    ├── sample_images/     # Demo images for testing
    └── apk_files/         # Directory containing APK files

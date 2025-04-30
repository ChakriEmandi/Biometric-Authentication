# Biometric Authentication System

This is a comprehensive Biometric Authentication System that integrates multiple authentication methods such as **face recognition**, **voice recognition with a code word**, and **digital signature (gesture) verification**. The application allows users to securely register, authenticate, and manage their biometric credentials.

---

## Features

### User Registration
- Register using a unique **User ID**.
- Capture and store:
  - A photo for **face recognition**.
  - A voice-based **code word** for authentication.
  - A signature image for **gesture recognition**.

### User Authentication
- Verify registered credentials using:
  - Face Recognition.
  - Voice Code Word.
  - Gesture/Signature Recognition.
- Displays **success** or **failure** response based on verification results.

### User Management
- Add new users after registration.
- Delete user credentials from the system.

---

## Technologies Used

- **Backend:** Python with Flask Framework  
- **Face Recognition:** OpenCV  
- **Voice Recognition:** librosa, pyaudio  
- **Signature Verification:** Image processing techniques  
- **Frontend:** HTML, CSS, JavaScript

---

## Requirements

- Python 3.7 or above  
- A functioning camera and microphone  

### Required Python Libraries

- Flask  
- OpenCV  
- librosa  
- numpy  
- pyaudio  

Install them using:

```
pip install -r requirements.txt
```

---

## Installation and Setup

### 1. Clone the Repository

```
git clone <repository-url>
cd biometric-authentication-system
```

### 2. Install Dependencies

```
pip install -r requirements.txt
```

### 3. Run the Flask Application

```
python app.py
```

---

### Access the Application

Open your browser and go to:

```
http://127.0.0.1:5000
```

---

## Project Structure

```
biometric-authentication-system/
├── app.py                       # Main Flask application
├── requirements.txt             # Python dependencies
├── static/                      # CSS, JS, and image assets
├── templates/                   # HTML templates (e.g., index.html)
├── face_data/                   # Stored face images
├── voice_data/                  # Stored voice samples
├── signature_data/              # Stored signature images
├── utils/                       # Helper scripts for processing
└── README.md                    # Project documentation
```

---

## Additional Notes

- Multi-language support can be integrated into the frontend for accessibility.
- Ideal for high-security systems needing multi-factor biometric verification.



# Biometric Authentication System

This is a comprehensive Biometric Authentication System that integrates multiple authentication methods such as face recognition, voice recognition with a code word, and digital signature verification. The application allows users to securely register, authenticate, and manage their biometric credentials.

## Features
### User Registration:
Register using a unique user ID.

### Capture and store:
A photo for face recognition.
A voice-based code word for authentication.
A photo for gesture detection.

### User Authentication:
Verify registered credentials using:
Face recognition.
Voice-based code word.
Gesture Recognition.
Provide a success or failure response based on verification results.

### User Management:
Add new user after registration.
Delete user credentials from the system when deleted.

### Technologies Used:
Python (Flask framework)
OpenCV for face recognition.
Voice processing libraries (e.g., librosa, pyaudio).
Signature handling using image processing techniques.
HTML, CSS, and JavaScript for the frontend.

### Requirements
Python 3.7 or above
## Required Python Libraries:

### Common libraries include:
Flask
OpenCV
librosa
numpy
pyaudio
A camera and microphone for capturing biometrics.

## Installation and Setup
Clone the repository
Install dependencies
Run the Flask application python app.py

### Access the application:
Open your browser and navigate to http://127.0.0.1:5000.

## Project Structure
biometric-authentication/
├── app.py                   # Main application file
├── templates/               # HTML templates
│   ├── index.html           # Home page
│   ├── register.html        # Registration page
│   ├── login.html           # Login page
├── static/                  # Static files (CSS, JS, images)
│   ├── styles.css           # CSS styles
|   ├── script.js            # JS script
├── README.md                # Project documentation
├── database.db              # SQLite database

## Usage
### Register a New User:
Go to the Register page.
Enter a unique user ID.
Capture a photo, record a voice code word, and provide a signature.
Submit to save the data.
### Authenticate User:
Go to the Login page.
Provide the registered credentials.
The system will authenticate and display the result.

### Future Enhancements
Integration with cloud storage for biometric data.
Advanced noise filtering for voice recognition in noisy environments.
Support for additional biometric methods like fingerprint recognition.
Multi-language support for the UI.

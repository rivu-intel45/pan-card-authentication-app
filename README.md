# 🆔 PAN Card Detection

PAN Card Detection is a web application that analyzes uploaded PAN images, identifies tampering or inconsistencies, and flags suspicious regions. It helps automate KYC verification, reduce fraud, and ensure secure identity verification workflows.

## 📊 Overview

This Flask-based application uses computer vision techniques to:
- Detect and validate PAN card images
- Identify tampering, forgery, or quality issues
- Highlight suspicious regions in the card
- Assist in quick, reliable document verification for security and compliance

---

## 🎮 How to Use

1. **Upload a PAN Card Image**  
   Click the upload button and select a PAN card photo (JPG/PNG)

2. **View Detection Results**  
   The app analyzes the image and displays:
   - Original card image
   - Detected tampering regions (highlighted)
   - Confidence score
   - Verification status

3. **Review Findings**  
   Check authenticity indicators and decide whether to accept or reject the card

---

## ⚙️ Installation & Setup

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)

### Step 1: Clone the Repository
-git clone https://github.com/rivu-intel45/pan-card-authentication-app.git cd snake-game-turtle
### Step 2: Install Dependencies
-pip install -r requirements.txt
### Step 3: Run the Application

The app will start on `http://localhost:5000`

---

## 📦 Tech Stack

- **Flask** - Web framework
- **OpenCV** - Image processing & computer vision
- **NumPy** - Numerical computations
- **Pillow** - Image manipulation
- **Scikit-Image** - Advanced image analysis

---

## 📁 Project Structure

pan-card-detection/
├── app.py # Main Flask application
├── config.py # Configuration settings
├── pan_card_detection.py # Core detection logic
├── requirements.txt # Python dependencies
├── templates/ # HTML templates
├── static/ # CSS, JS, images
└── README.md # This file

---

## 🔒 Features

✅ **Image Upload & Validation**  
✅ **Tampering Detection**  
✅ **Region Highlighting**  
✅ **Confidence Scoring**  
✅ **Real-time Processing**  
✅ **User-friendly Interface**

---

## 🚀 Future Enhancements

- QR code verification integration
- PAN 2.0 database verification

## 💡 Contributing

Contributions are welcome! Feel free to fork, submit issues, or make pull requests.

---
Happy verifying! 🎉

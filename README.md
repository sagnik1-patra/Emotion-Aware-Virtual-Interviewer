#  Emotion-Aware Virtual Interviewer

![App Screenshot](Screenshot%202025-08-03%20095409.png)

## Project Overview

The Emotion-Aware Virtual Interviewer simulates an interactive interview session where:

- Questions are asked automatically via the microphone.
- Your responses are captured as **audio** and **video**.
- Real-time **facial emotion detection** is performed using your webcam.
- Your **voice tone and energy levels** are analyzed.
- All results are compiled into a **PDF report** and saved locally.

---

##  Features

-  Facial emotion detection using a CNN model.
-  Voice tone analysis with `librosa`.
-  Automated PDF generation of results.
-  Ideal for interview training and feedback.

---

##  How to Run

1. **Install dependencies** (if not already installed):

   ```bash
   pip install opencv-python keras tensorflow matplotlib librosa scikit-learn reportlab sounddevice scipy
Ensure you have the following files in your project:

emotion_model.h5: Pre-trained facial emotion recognition model.

The provided code script (with camera/mic access).

Place the output folder:

makefile
Copy
Edit
C:\Users\sagni\Downloads\Emotion Aware Virtual Interviewer
Run the script in an environment that allows camera and mic access (e.g., local Jupyter Notebook or terminal).

 Output
A PDF report will be saved in:

makefile
Copy
Edit
C:\Users\sagni\Downloads\Emotion Aware Virtual Interviewer
The PDF contains:

The questions asked

Detected facial emotion

Voice tone metrics

Timestamped analysis

 Screenshot

 Built With
Python

OpenCV

TensorFlow / Keras

Librosa

ReportLab

 Author
Sagnik Patra

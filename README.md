# OpenCV Face Recognition Project

## Overview
This project demonstrates real-time face recognition and image comparison using OpenCV and the `face_recognition` library in Python. It includes scripts for live webcam-based face detection, encoding known faces, and comparing images for facial similarity. The project reflects my journey in computer vision, practical AI, and hands-on experimentation with facial recognition technology.

## Features
- **Real-Time Face Recognition:** Detects and recognizes faces from a webcam feed using pre-encoded images.
- **Image Comparison:** Compares two images to determine if they contain the same person.
- **Modular Code:** Includes reusable classes and functions for encoding, detection, and comparison.
- **User-Friendly Visualization:** Draws bounding boxes and labels on detected faces in real time.

## How It Works
1. **Encoding Faces:**
   - The `SimpleFacerec` class loads and encodes known faces from an images folder.
2. **Live Recognition:**
   - `main_video.py` captures webcam frames, detects faces, and matches them against known encodings, displaying results live.
3. **Image Comparison:**
   - `image_comparison.py` loads two images, encodes the faces, and prints whether they match.

## My Learning Journey
Through this project, I learned:
- How to use OpenCV for image and video processing.
- The basics of face encoding and recognition with the `face_recognition` library.
- Real-time computer vision pipeline design and debugging.
- The importance of modular, reusable code for AI projects.

## Usage Instructions
1. **Install Dependencies:**
   - Required: `opencv-python`, `face_recognition`, `numpy`.
   - Install with: `pip install opencv-python face_recognition numpy`
2. **Prepare Images:**
   - Place known face images in the `images/` directory.
3. **Run Live Recognition:**
   - Execute `main_video.py` to start webcam-based face recognition.
4. **Compare Images:**
   - Use `image_comparison.py` to compare two images for facial similarity.

## File Structure
- `main_video.py`: Real-time face recognition from webcam.
- `simple_facerec.py`: Face encoding and recognition class.
- `image_comparison.py`: Script for comparing two images.
- `images/`: Folder for known face images.

---
*Created by Saud Ahmad – Computer Vision & AI Enthusiast*
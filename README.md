# 🦯 Assistive AI System for Visually Impaired People in Egypt

## 📌 Overview
Visually impaired people in Egypt face daily challenges related to safe mobility, reading printed text, and handling money independently. Existing assistive solutions are often expensive, not localized for Arabic users, or solve only part of the problem.

This project presents a **low-cost, AI-powered, Arabic-focused assistive system** that helps visually impaired users **navigate streets safely, recognize Egyptian currency, and read printed text** using a smartphone.

---
**Link of the Obstacles Notebook for all outputs you need:**
 🔗 [https://www.kaggle.com/code/haneenmohammed13/obstacls-detection-for-blind-people-yolov8]

---

## 🎯 Problem Statement
- Unsafe street navigation due to obstacles such as uncovered manholes, stairs, cars, dogs, and electric poles  
- Difficulty reading printed text such as labels, signs, and documents  
- High risk of financial fraud when handling cash  
- Limited access to affordable, Arabic-localized assistive technology in Egypt
- Blind Navigation Assistant - YOLOv8 Object Detection
Model

📋 Project Overview
This notebook trains a YOLOv8 object detection model to assist visually impaired individuals in navigating their environment safely. The model detects 11 types of obstacles and hazards in real-time.


🎯 Detected Objects
🚲 Bicycle
🚌 Bus
🚗 Car
🐕 Dog
⚡ Electric Pole
🏍️ Motorcycle
👤 Person
🚦 Traffic Signs
🌳 Tree
⚠️ Uncovered Manhole
🪜 Stairs

---

## 💡 Our Solution
We built a **mobile AI application** that:
- Detects common Egyptian street obstacles in real time  
- Recognizes Egyptian banknotes  
- Reads printed text and converts it into Arabic speech  
- Runs entirely on a smartphone using the camera  

---

## 🧠 What We Have Built (Working Prototype)

### ✅ Implemented Features
- **Obstacle Detection**
  - Trained a YOLOv8 model from scratch
  - Detects obstacles such as uncovered manholes, stairs, cars, dogs, and electric poles in real time
- **Currency Recognition**
  - Detects and announces Egyptian banknotes
- **OCR & Arabic Text-to-Speech**
  - Uses Google ML Kit to recognize printed text
  - Converts text into Arabic speech
- **Mobile Integration**
  - Camera-based interaction
  - Users switch between modes using simple swipe gestures

> All features listed above are **fully implemented and demo-ready**.

---

## 🛠️ Technologies & Tools Used
- **YOLOv8** – Object detection
- **Google ML Kit** – OCR and Text-to-Speech
- **Python**
- **Roboflow** – Dataset management
- **Mobile Application (Android)**

---

## 📂 Dataset
- Source: Roboflow  
### How to Use the Dataset
1. Download the dataset from Roboflow in **YOLOv8 format**.
2. Extract the dataset folder.
3. Place the folder inside the project root directory.
**Dataset link:**
🔗 [https://universe.roboflow.com/username/project-name](https://universe.roboflow.com/haneens-projects/assisting-visually-impaired-people/dataset/2)




---

## 🚀 Future Work
- Continuous real-time navigation while the user is walking  
- Adaptive vibration feedback for noisy street environments  
- Seamless integration of all features without mode switching  
- Enhanced Arabic Text-to-Speech optimized for Egyptian dialect  
- Support for new Egyptian banknotes  
- Training on larger datasets with more Egyptian street obstacles  
- Offline functionality for all core features  
- Face recognition and facial expression understanding  
- Document summarization using Large Language Models (online feature)  
- User testing, performance optimization, and data privacy enhancements  

---

## 📽️ Demo
A live or recorded demo demonstrates:
- Real-time obstacle detection
- Egyptian currency recognition
- OCR with Arabic speech output

---

## 👥 Team
This project was developed by a student team as part of **Samsung Innovation Campus**, focusing on applying AI for social impact and accessibility.

---

## 📜 License
This project is intended for educational and research purposes.

<div align="center">

# 🦯 AL Ru'ya — الرؤية
### Assistive AI System for Visually Impaired People in Egypt

*Low-cost · Arabic-focused · Mobile-first · AI-powered*

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFFF?style=flat-square&logo=yolo&logoColor=black)](https://ultralytics.com)
[![Google ML Kit](https://img.shields.io/badge/Google%20ML%20Kit-4285F4?style=flat-square&logo=google&logoColor=white)](https://developers.google.com/ml-kit)
[![Roboflow](https://img.shields.io/badge/Roboflow-purple?style=flat-square&logo=roboflow&logoColor=white)](https://roboflow.com)
[![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)](https://android.com)
[![Hackathon](https://img.shields.io/badge/AL%20Ru'ya%20Hackathon-🥉%203rd%20Place-CD7F32?style=flat-square)](#)
[![Samsung](https://img.shields.io/badge/Samsung%20Innovation%20Campus-1428A0?style=flat-square&logo=samsung&logoColor=white)](https://samsung.com)

[![Kaggle Notebook](https://img.shields.io/badge/📓%20Obstacle%20Detection%20Notebook-Kaggle-20BEFF?style=for-the-badge&logo=kaggle)](https://www.kaggle.com/code/haneenmohammed13/obstacls-detection-for-blind-people-yolov8)
[![Dataset](https://img.shields.io/badge/📦%20Roboflow%20Dataset-View-purple?style=for-the-badge)](https://universe.roboflow.com/haneens-projects/assisting-visually-impaired-people/dataset/2)

</div>

---

## 📌 Overview

Visually impaired people in Egypt face serious daily challenges — unsafe street navigation, inability to read printed text, and high risk of financial fraud when handling cash. Existing assistive solutions are either too expensive, not localized for Arabic users, or solve only one part of the problem.

**AL Ru'ya** (Arabic: الرؤية — *The Vision*) is a **low-cost, AI-powered, Arabic-focused assistive system** that runs entirely on a smartphone. It helps visually impaired users navigate streets safely, recognize Egyptian currency, and read printed text — all through real-time AI on a mobile camera.

> 🏆 This project was awarded **3rd Place at the AL Ru'ya Hackathon**, developed as part of **Samsung Innovation Campus — AI for Social Impact**.

---

## 🎯 Problem Statement

| Challenge | Description |
|---|---|
| 🚧 Unsafe navigation | Obstacles such as uncovered manholes, stairs, cars, dogs, and electric poles cause daily accidents |
| 📄 Inability to read | Signs, labels, and documents are inaccessible without sighted assistance |
| 💵 Financial fraud | Difficulty identifying banknote values leads to exploitation |
| 🌍 No local solution | Existing assistive tools are expensive and not adapted for Arabic or Egyptian context |

---

## 💡 Solution

A **mobile Android application** powered by AI that:

- 🚧 Detects real-time street obstacles and warns the user via voice
- 💵 Recognizes Egyptian banknotes and announces their value
- 🔤 Reads printed Arabic text aloud using OCR and Text-to-Speech
- 📱 Runs fully on-device via smartphone camera — no internet required for core features
- 👆 Simple swipe gestures to switch between detection modes

---

## ✅ Implemented Features

### 🚧 Obstacle Detection
- Trained a **custom YOLOv8 model from scratch** on an Egyptian street dataset
- Detects **11 obstacle classes** in real time:

| | | | |
|---|---|---|---|
| 🚲 Bicycle | 🚌 Bus | 🚗 Car | 🐕 Dog |
| ⚡ Electric Pole | 🏍️ Motorcycle | 👤 Person | 🚦 Traffic Signs |
| 🌳 Tree | ⚠️ Uncovered Manhole | 🪜 Stairs | |

### 💵 Currency Recognition
- Detects and announces the value of **Egyptian banknotes** in real time
- Provides financial independence for visually impaired users

### 🔤 OCR & Arabic Text-to-Speech
- Uses **Google ML Kit** to recognize printed text from signs, labels, and documents
- Converts recognized text into **Arabic speech** immediately

### 📱 Mobile Integration
- Camera-based interaction with simple **swipe gestures** to switch between modes
- All core features run **fully on-device** with low latency

> All features listed above are **fully implemented and demo-ready**.

---

## 🛠️ Technologies & Tools

| Component | Technology |
|---|---|
| Object Detection | YOLOv8 (Ultralytics) |
| OCR & Text-to-Speech | Google ML Kit |
| Dataset Management | Roboflow |
| Language | Python |
| Platform | Android Mobile Application |

---

## 📂 Dataset

- **Source:** Roboflow — custom dataset built for Egyptian street environments
- **Format:** YOLOv8-compatible
- **Classes:** 11 obstacle types

**How to use:**
1. Download the dataset from Roboflow in **YOLOv8 format**
2. Extract the dataset folder
3. Place it inside the project root directory

[![Dataset](https://img.shields.io/badge/📦%20Download%20Dataset-Roboflow-purple?style=flat-square)](https://universe.roboflow.com/haneens-projects/assisting-visually-impaired-people/dataset/2)

---

## 🚀 Future Work

- [ ] Continuous real-time navigation while walking (no mode switching)
- [ ] Adaptive vibration feedback for noisy street environments
- [ ] Enhanced Arabic TTS optimized for Egyptian dialect
- [ ] Support for newly issued Egyptian banknotes
- [ ] Training on larger, more diverse Egyptian street datasets
- [ ] Full offline functionality for all features
- [ ] Face recognition and facial expression understanding
- [ ] Document summarization using Large Language Models (online feature)
- [ ] User testing, performance optimization, and data privacy enhancements

---

## 👥 Team

Developed by a student team as part of **Samsung Innovation Campus**, applying AI for social impact and accessibility in Egypt.

---

## 📜 License

This project is intended for **educational and research purposes**.

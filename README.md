# 🦯 Assistive AI System for Visually Impaired People in Egypt

## 📌 Overview
Visually impaired people in Egypt face daily challenges related to safe mobility, reading printed text, and handling money independently. Existing assistive solutions are often expensive, not localized for Arabic users, or solve only part of the problem.

This project presents a **low-cost, AI-powered, Arabic-focused assistive system** that helps visually impaired users **navigate streets safely, recognize Egyptian currency, and read printed text** using a smartphone.

---

## 🎯 Problem Statement
- Unsafe street navigation due to obstacles such as uncovered manholes, stairs, cars, dogs, and electric poles  
- Difficulty reading printed text such as labels, signs, and documents  
- High risk of financial fraud when handling cash  
- Limited access to affordable, Arabic-localized assistive technology in Egypt  

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
- Size: ~603 MB  
- Structure:

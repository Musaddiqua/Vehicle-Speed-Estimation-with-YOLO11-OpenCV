<div align="center">

# 🚗💨 **Vehicle Speed Estimation using YOLO11 + ByteTrack + Perspective Transform**

A complete real-world vehicle speed estimation pipeline built using modern computer vision techniques.  
Designed for **OEM applications, telematics, smart transportation and intelligent CCTV analytics**.

---

### 📹 *Insert Sample Output Video Here*
*(Add GIF / MP4 preview in this space)*

---

</div>

## 🏁 Overview

This project demonstrates how highway CCTV footage can be transformed into accurate vehicle speed measurements using:

- **YOLO11** for vehicle detection  
- **ByteTrack** for stable object tracking  
- **OpenCV Perspective Transformation** for pixel-to-meter world mapping  
- **Motion-based speed estimation** in m/s and km/h  

This implementation is **fully reproducible**, modular, and optimized for Kaggle Notebook execution.

---

## ⭐ Why This Project Stands Out

✔ Converts angled CCTV footage into **true top-down world coordinates**  
✔ Reduces distortion using **homography & perspective transform**  
✔ Evaluates speed using **real-world displacement**  
✔ Provides **highway-grade accuracy** for OEM analytics  
✔ Clean visualization with annotated bounding boxes & speeds  

---

## 🔍 Key Features

- 🚘 **Real-time vehicle detection** (YOLO11)  
- 🔢 **Unique multi-object tracking** (ByteTrack)  
- 📐 **Perspective correction for distance accuracy**  
- 🚀 **Smooth speed estimation with noise filtering**  
- 📝 **Output labels with ID + Speed (km/h)**  
- 🎥 **Final annotated video generation**  
- 🎯 Ideal for OEMs like **Mahindra/TATA** for telematics

---

## 🧠 Technical Workflow

### **1️⃣ Detection – YOLO11**
Detects vehicles per frame with high accuracy, even in complex lighting or motion.

### **2️⃣ Tracking – ByteTrack**
Assigns **persistent IDs** to moving vehicles.  
Maintains continuity even in occlusions.

### **3️⃣ Perspective Transform**
The most essential step.

Camera perspective distorts distances.  
We correct that using a **homography matrix**:


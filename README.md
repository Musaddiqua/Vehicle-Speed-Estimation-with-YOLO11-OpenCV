<div align="center">

# 🚗💨 **Vehicle Speed Estimation using YOLO11 + ByteTrack + Perspective Transform**

A professional, industry-ready implementation for estimating **real-world vehicle speeds** from CCTV footage.  
Built for applications in **Smart Transportation, OEM Telematics (TATA/Mahindra), Traffic Analytics & Intelligent Surveillance**.

---

### 📹 **Output Preview**
*(Add your GIF/Video here)*

---

</div>

---

## 🔍 **Project Overview**

This project uses state-of-the-art vision models to detect, track, and calculate real-world vehicle speeds from angled CCTV highway footage.  
It performs:

- YOLO11-based vehicle detection  
- ByteTrack multi-object tracking  
- Perspective-to-world coordinate mapping  
- Real-world displacement → speed estimation (m/s → km/h)  
- Annotated video output  

All code is executed inside a **Kaggle Notebook**.

---

## 🧠 **How It Works**

### **1️⃣ YOLO11 Detection**
Detects vehicles per frame with high accuracy & real-time inference.

### **2️⃣ ByteTrack Tracking**
Assigns stable IDs, even during occlusions.

### **3️⃣ Perspective Transformation**
Raw footage is distorted; so we correct it using:


This maps pixel coordinates → actual road distances (meters).

### **4️⃣ Speed Estimation**

<div align="center">


</div>

We compute displacement using **Euclidean distance + Median Filtering** across frames.

---

## 🚀 **Key Features**

- High-accuracy YOLO11 vehicle detection  
- Smooth tracking using ByteTrack  
- True world-distance measurement via homography  
- Real-time speed overlay on video  
- Noise reduction using median smoothing  
- Works on any fixed CCTV angle  

---

## 🛠️ **Tech Stack (With Official Logos)**

<h3 align="left">Languages & Tools:</h3>
<p align="left">

<a href="https://www.python.org/" target="_blank">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="50" height="50" alt="Python"/>
</a>

<a href="https://opencv.org/" target="_blank">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/opencv/opencv-original.svg" width="50" height="50" alt="OpenCV"/>
</a>

<a href="https://numpy.org/" target="_blank">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/numpy/numpy-original.svg" width="50" height="50" alt="NumPy"/>
</a>

<a href="https://github.com/ifzhang/ByteTrack" target="_blank">
<img src="https://img.icons8.com/?size=512&id=GfDlQKkZSv2S&format=png" width="50" height="50" alt="ByteTrack"/>
</a>

<a href="https://ultralytics.com/" target="_blank">
<img src="https://raw.githubusercontent.com/ultralytics/assets/main/logo/ultralytics-logo.png" width="120" alt="YOLO11"/>
</a>

</p>

---

## ▶️ **How to Run (Kaggle Notebook)**

1. Upload your video  
2. Define perspective points  
3. Run YOLO11 detection  
4. Run ByteTrack tracker  
5. Execute speed estimation cell  
6. Download the annotated output video  

---

## 📊 Insights from the Experiment

- Vehicles moving toward camera appear faster due to angle compression  
- Opposite lane shows traffic build-up → lower speeds  
- Tracking stability determines accuracy  
- Homography gives near real-world precision  

---

## 🔮 Improvements & Future Scope

- ANPR (Number Plate Recognition)  
- Overspeed violation alerts  
- Vehicle classification (car/truck/bus)  
- Traffic flow & congestion analytics  
- Dashboard integration for OEM telematics  

---

## 📜 License

This project is covered under the **MIT License**.

---

## 👩‍💻 **Author**

**Musaddiqua Rajannavar**  
AIML Trainee | Technologics Global  
📧 your-musaddiquarajannavar@gmail.com  
🔗 GitHub: https://github.com/your-username

---

<div align="center">

⭐ *If this project helped you, please star the repository. It motivates further development.*

</div>


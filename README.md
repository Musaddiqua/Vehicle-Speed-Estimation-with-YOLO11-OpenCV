<div align="center">

# 🚗💨 **Vehicle Speed Estimation using YOLO11 + ByteTrack + Perspective Transform**

A professional, industry-ready pipeline for estimating **real-world vehicle speeds** from CCTV footage.  
Designed for **Smart Transportation, OEM Telematics (TATA/Mahindra), Traffic Analytics & Intelligent Surveillance**.

---

</div>

---

## 🔍 **Project Overview**

This project performs accurate vehicle speed estimation using modern Computer Vision techniques:

- YOLO11-based vehicle detection  
- ByteTrack multi-object tracking  
- Perspective transformation for mapping pixel → real-world distances  
- Speed estimation in km/h  
- Annotated final video output  

All implemented inside a **Kaggle Notebook** for easy reproducibility.

---

## 🧠 **How It Works**

### **1️⃣ YOLO11 Detection**
Accurate real-time vehicle detection on highway CCTV feeds.

### **2️⃣ ByteTrack Tracking**
Stable tracking IDs are assigned to each vehicle, even with partial occlusions.

### **3️⃣ Perspective Transformation**
Corrects camera angle distortions using:


### **4️⃣ Speed Estimation**

<div align="center">


</div>

Displacement is calculated using Euclidean distance + median filtering.

---

## 🛠️ **Tech Stack (Logos + Names)**

<h3 align="left">Tools & Libraries Used</h3>

<p align="left">

<a href="https://www.python.org/" target="_blank">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="55" height="55"/>
</a>  
<br><b>Python</b>

<br><br>

<a href="https://opencv.org/" target="_blank">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/opencv/opencv-original.svg" width="55" height="55"/>
</a>  
<br><b>OpenCV</b>

<br><br>

<a href="https://numpy.org/" target="_blank">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/numpy/numpy-original.svg" width="55" height="55"/>
</a>  
<br><b>NumPy</b>

<br><br>

<a href="https://github.com/ifzhang/ByteTrack" target="_blank">
<img src="https://img.icons8.com/?size=512&id=GfDlQKkZSv2S&format=png" width="55" height="55"/>
</a>  
<br><b>ByteTrack</b>

<br><br>

<a href="https://ultralytics.com/" target="_blank">
<img src="https://raw.githubusercontent.com/ultralytics/assets/main/logo/ultralytics-logo.png" width="140"/>
</a>  
<br><b>YOLO11</b>

</p>

---

## ▶️ **How to Run (Kaggle Notebook)**

1. Upload input CCTV video  
2. Set 4 perspective calibration points  
3. Run YOLO detection cells  
4. Run ByteTrack ID assignment  
5. Execute speed estimation block  
6. Download final annotated video  

---

## 📊 **Key Insights**

- Speed accuracy depends on calibration  
- Tracking stability improves results  
- Highway directional angle affects perceived motion  
- Homography significantly boosts real-world precision  

---

## 🔮 **Future Enhancements**

- ANPR (Automatic Number Plate Recognition)  
- Overspeed violation detection  
- Vehicle type classification  
- Telematics dashboard for OEMs  
- Real-time deployment with FastAPI  

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👩‍💻 **Author**

**Musaddiqua Rajannavar**  
AIML Trainee | Technologics Global  
📧 musaddiquarajannavar@gmail.com  
🔗 GitHub: https://github.com/musaddiqua 

---

<div align="center">

⭐ *Star the repo if this project helped you—your support motivates further development!*

</div>

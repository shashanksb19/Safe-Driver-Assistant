# 🚗 Safe Driver Assistant  
## Real-Time Driver Drowsiness Detection using Computer Vision and Embedded AI

**Tech Stack:** Python • OpenCV • Dlib • Raspberry Pi • Computer Vision • Embedded Systems • Real-Time AI

---

# 📌 Project Summary

Safe Driver Assistant is a **real-time embedded AI system** that detects driver drowsiness and fatigue using computer vision and facial landmark analysis.

The system runs on a **Raspberry Pi edge device**, processes live video streams, extracts facial features, and triggers **voice alerts when fatigue is detected**, helping prevent road accidents.

This project demonstrates **end-to-end Computer Vision pipeline development, edge deployment, and real-time inference.**

---

# 🎯 Why This Project Matters

Driver fatigue contributes to thousands of fatal accidents each year.

This system provides:

• Real-time fatigue monitoring  
• Automated driver alerting  
• Edge AI deployment  
• Safety-critical AI system design  

This is the same class of technology used in:

- Tesla Driver Monitoring
- NVIDIA Driver Monitoring System (DMS)
- Mobileye ADAS systems

---

# 🧠 Core AI Concepts Implemented

This project demonstrates practical application of:

- Facial Landmark Detection
- Feature Engineering
- Real-Time Video Processing
- Edge AI Deployment
- Human State Classification

---

# 🏗️ System Architecture


---

# 👁️ Drowsiness Detection Algorithm

The system uses **Eye Aspect Ratio (EAR)** to detect fatigue.

EAR formula:

```
EAR = (||p2−p6|| + ||p3−p5||) / (2 ||p1−p4||)
```

When EAR falls below threshold for consecutive frames → driver is drowsy.

This method is:

• Lightweight  
• Accurate  
• Real-time capable  
• Suitable for embedded deployment  

---

# 😮 Yawn Detection

Yawning is detected using lip landmark distance:

```
Lip Distance = Upper Lip − Lower Lip
```

If distance exceeds threshold → fatigue detected.

---

# 🧰 Tech Stack

## Programming

Python

---

## Computer Vision

OpenCV  
Dlib  
Imutils  

---

## Machine Learning Concepts

Facial Landmark Detection  
Feature Engineering  
Signal-based Classification  

---

## Embedded Systems

Raspberry Pi  
GPIO Integration  

---

## Supporting Libraries

NumPy  
SciPy  
Threading  

---

# ⚙️ Hardware Used

| Hardware | Purpose |
|--------|---------|
| Raspberry Pi 3 | Edge AI compute |
| Pi Camera | Video input |
| MQ-3 Alcohol Sensor | Intoxication detection |
| Buzzer | Alert system |

---

# 📊 Performance Characteristics

| Feature | Result |
|--------|--------|
| Detection Type | Real-time |
| Latency | <100 ms |
| Deployment | Edge device |
| Processing | Live video |

---

# 💻 Example Output

```
DROWSINESS ALERT!
EAR: 0.21
YAWN: 32.5
```

Voice alert:

```
"Wake up sir"
```

---

# 📂 Project Structure

```
safe-driver-assistant/

driver_monitor.py
shape_predictor_68_face_landmarks.dat
haarcascade_frontalface_default.xml
README.md
```

---

# ▶️ How to Run

## 1. Install dependencies

```
pip install opencv-python dlib imutils numpy scipy
```

---

## 2. Download facial landmark model

Download:

```
shape_predictor_68_face_landmarks.dat
```

---

## 3. Run system

```
python driver_monitor.py
```

---

# 🚀 Engineering Challenges Solved

This project required solving:

Real-time inference optimization  
Embedded hardware constraints  
Robust face detection  
Noise-tolerant fatigue detection  
Thread-safe alert system  

---

# 🎯 Real-World Applications

Driver Monitoring Systems (DMS)  
Autonomous Vehicles  
ADAS Systems  
Fleet Safety Monitoring  
Industrial Safety Systems  

---

# 🧠 Skills Demonstrated

This project demonstrates strong capability in:

Computer Vision  
Real-Time AI Systems  
Embedded AI  
Edge Deployment  
Feature Engineering  
Production-Level Python  

---

# 📈 Future Improvements

CNN-based fatigue detection  
Transformer-based monitoring  
Multi-person detection  
Cloud telemetry integration  

---

# 🧑‍💻 Author

**Shashank Bharadwaj**

AI Engineer  
Computer Vision • Embedded AI • Machine Learning

---

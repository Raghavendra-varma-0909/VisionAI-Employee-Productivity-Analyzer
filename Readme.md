# 🧠 VisionAI – Employee Productivity Analyzer

## 🚀 Overview

VisionAI is an AI-powered real-time employee activity monitoring system that uses deep learning (CNN) and computer vision to analyze user behavior from live video feeds.

The system classifies employee activity into four categories:

* 🟢 Active
* 🔴 Idle
* 🟡 Distracted
* ⚫ Absent

It provides real-time insights into productivity and logs activity data for further analysis.

---

## 🔥 Key Features

* 🎥 Real-time activity detection using webcam (OpenCV)
* 🧠 Deep learning model (CNN) trained on custom dataset
* 📊 Live activity logging (CSV-based tracking)
* ⚡ Lightweight and runs locally
* 🧩 Modular and scalable architecture

---

## 🧠 Tech Stack

| Category        | Tools              |
| --------------- | ------------------ |
| Programming     | Python             |
| Computer Vision | OpenCV             |
| Deep Learning   | TensorFlow / Keras |
| Data Handling   | NumPy, Pandas      |
| Logging         | CSV                |

---

## 🧠 Model Details

* Model Type: Convolutional Neural Network (CNN)
* Input Size: 224 × 224
* Classes: 4 (Active, Idle, Distracted, Absent)
* Accuracy: ~90% (custom dataset)

---

## 📂 Project Structure

```
VisionAI-Employee-Productivity-Analyzer/
│
├── data/                  # Dataset (not included in repo)
│   ├── active/
│   ├── idle/
│   ├── distracted/
│   └── absent/
│
├── detector.py            # Real-time detection script
├── train_model.py         # CNN training script
├── utils.py               # Helper functions
├── collect_data.py        # Dataset collection script
├── requirements.txt       # Dependencies
├── README.md
```

---

## ⚙️ Workflow

```
Camera Feed → Frame Processing → CNN Model → Activity Prediction → Logging
```

---

## 🚀 How to Run

### 1. Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/VisionAI-Employee-Productivity-Analyzer.git
cd VisionAI-Employee-Productivity-Analyzer
```

---

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 3. Train Model (Optional)

```bash
python train_model.py
```

---

### 4. Run Detector

```bash
python detector.py --employee_id E001
```

---

## ⚠️ Note

* Dataset and trained model are not included due to size constraints.
* You can generate your own dataset using `collect_data.py`.

---

## 💼 Use Cases

* Employee productivity monitoring
* Workplace analytics
* Smart office systems
* Behavioral analysis using AI

---

## 🚧 Future Improvements

* Add FastAPI backend for deployment
* Replace CSV with database (MongoDB/PostgreSQL)
* Add confidence score & alerts
* Deploy on cloud (AWS/GCP)

---

## 👨‍💻 Author

**Raghavendra Varma**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!

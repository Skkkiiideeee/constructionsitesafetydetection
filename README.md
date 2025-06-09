# 🦺 Construction Site Safety Detection

A **real-time object detection system** built with **YOLOv8** to identify safety equipment (e.g., helmets, vests) on construction sites. Achieved **90% accuracy**, optimized for **low-latency robotic vision systems** operating in **resource-constrained environments**.

---

## 🚀 Overview

This project leverages **YOLOv8** and **OpenCV** to detect construction safety gear in images and video streams. It is designed for **autonomous safety inspection** in robotics.
Check the latest code on constructionsitesafetydetection version 3

* **Accuracy:** 90%
* **Inference Time Reduced:** 18% via fine-tuning and optimized preprocessing

---

## 🔧 Features

* ✅ Real-time detection of helmets and vests using YOLOv8
* ⚙️ Optimized for embedded and low-power robotic applications
* 🤖 Scalable for integration with robotic platforms
* 📊 Preprocessing and visualization using OpenCV and Matplotlib

---

## 🛠️ Technologies Used

**Languages:** Python
**Libraries:** YOLOv8 (Ultralytics), OpenCV, NumPy, Matplotlib
**Tools:** Google Colab (T4 GPU), Jupyter Notebook, Git

---

## 📦 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/Skkkiiidecee/ConstructionSiteSafetyDetection.git
cd ConstructionSiteSafetyDetection
```

2. **Install dependencies:**

```bash
pip install ultralytics opencv-python numpy matplotlib
```

3. **Add model weights:**

Download the trained YOLOv8 model (`best.pt`) from \[Google Drive link or your specified path] and place it in the `/weights/` directory.

---

## ▶️ Usage

Run the detection script:

```bash
python detect.py --weights weights/best.pt --source data/sample_video.mp4
```

* Outputs will be saved in the `/runs/detect/` folder
* Use Matplotlib for custom visualization if needed

---

## 📂 Dataset

* **Source:** [Construction Site Safety Dataset (Roboflow/Kaggle)](https://www.kaggle.com/datasets/snehilsanyal/construction-site-safety-image-dataset-roboflow)
* **Images:** 2605 (including helmets, vests, etc.)
* You can customize for other datasets by updating `data.yaml`

---

## 👩‍💻 About Me

I’m a **third-year B.Tech CSE student** at **KIIT DU**, passionate about **AI, computer vision, and robotics**. This project reflects my hands-on learning in **YOLOv8, OpenCV**, and real-time vision for robotics.

* 💻 [Check out my other projects](https://github.com/Skkkiiideeee)
* 🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/sugyani-krishnadarsinee/)


Construction Site Safety Detection

A real-time object detection system using YOLOv8 to identify construction site safety equipment (e.g., helmets, vests), achieving 90% accuracy. Built for robotic vision to enable automated safety monitoring in resource-constrained environments.

Overview

This project leverages YOLOv8 and OpenCV to detect safety equipment in construction site images/videos, optimized for robotic integration. It achieves 90% accuracy and reduces inference time by 18% through fine-tuning and preprocessing, supporting autonomous safety inspections.

Features





Real-time detection of safety equipment using YOLOv8.



Optimized for low-latency performance in robotic applications.



Scalable design for integration with robotic platforms.



Data preprocessing and visualization with OpenCV and Matplotlib.

Technologies





Languages: Python



Libraries: YOLOv8 (Ultralytics), OpenCV, NumPy, Matplotlib



Tools: Google Colab (T4 GPU), Jupyter Notebook, Git

Installation





Clone the repository:

git clone https://github.com/Skkkiiidecee/ConstructionSiteSafetyDetection.git



Install dependencies:

pip install ultralytics opencv-python numpy matplotlib



Download the trained YOLOv8 model (best.pt) from [Google Drive link or specify path] and place it in /weights/.

Usage





Run the detection script:

python detect.py --weights weights/best.pt --source data/sample_video.mp4



View results in the output folder or visualize with Matplotlib.

Dataset

Trained on a construction site safety dataset (e.g., helmets, vests, 2605 images, as per Jupyter notebook progress bar). Update data.yaml for custom datasets.
Dataset: https://www.kaggle.com/datasets/snehilsanyal/construction-site-safety-image-dataset-roboflow

About Me

I’m a third-year B.Tech student passionate about AI, computer vision, and robotics. This self-learning project reflects my expertise in Python, YOLOv8, and OpenCV, with applications in robotic vision. Check out my other projects at GitHub or connect on LinkedIn.


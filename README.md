# miniproject01

Intelligent Movement Analysis for Assisted Physiotherapy: Real-Time Monitoring and Feedback


Overview:
This project introduces an intelligent physiotherapy assistant designed to ensure the accurate and safe execution of rehabilitation exercises. It bridges the gap between professional clinical supervision and unsupervised home-based practice by providing real-time guidance through computer vision.
  

Key Features:
Real-Time Pose Tracking: Utilizes a standard webcam to extract 33 skeletal keypoints (shoulders, elbows, knees, hips, etc.) using the MediaPipe framework.  
Joint-Angle Analysis: Automatically computes precise joint angles (e.g., elbow flexion, knee bending) to evaluate exercise quality against expert-defined models.  
Immediate Corrective Feedback: Delivers live on-screen textual instructions (e.g., "Straighten your back") to help users correct mistakes instantly.  
Performance Scoring: Assigns quantitative accuracy scores for each repetition based on joint conformity and movement smoothness.  
Progress Tracking: Maintains detailed logs and generates performance reports to track rehabilitation trends over time. 


Tech Stack:
Language: Python  
Computer Vision: OpenCV, MediaPipe  
Data Processing: NumPy  
Visualization: Matplotlib  


Project Objectives:
The system aims to reduce the risk of secondary injuries caused by incorrect posture, improve patient adherence to routines, and provide an affordable, scalable digital health solution for remote rehabilitation.  
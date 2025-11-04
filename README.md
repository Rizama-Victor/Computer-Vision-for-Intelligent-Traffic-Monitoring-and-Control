# Computer Vision 👁️ for Intelligent Traffic 🚦 Monitoring and Control
This repository contains the implementation of my research titled [_"Computer Vision for Intelligent Traffic Monitoring and Control"_](https://www.irejournals.com/paper-details/1706535), published in Iconic Research And Engineering Journals (2024) authored by [Rizama Victor](https://github.com/Rizama-Victor) and [Prince Abiamamela Obi-Obuoha](https://github.com/MelaObuoha) at the National Centre for Artificial Intelligence and Robotics (NCAIR), Nigeria.

---

## 🧭 Overview
Conventional traffic systems struggle to adapt to changing road conditions which continues to be a major issue due to the rising number of vehicles causing congestion and longer travel times amongst other limitations of the current traffic control systems. This project focuses on the development of an Intelligent Traffic Light Management System that uses computer vision to adjust signal timings in real time based on actual traffic density in a bid to reduce wait times and improve the overall traffic flow efficiency.

---

## 🎯 Research Objectives

-  To develop a computer vision model capable of accurately detecting and classifying vehicles across multiple traffic lanes in real-time.
-  To count the number of vehicles in each lane based on the real-time detection results.
-  To dynamically adjust signal timing by assigning shorter waiting periods and longer green light durations to lanes with higher traffic density.

---

## 🧰 Tools and Technologies Used

| Tool/Libraries | Purpose in the Project |
|--------------------|-----------------------|
| Python | Used as the main programming language for developing and training the computer vision model, and the algorithm. |
| OpenCV | Used for handling images, image processing, and video frame extraction. |
| YOLOv8 | Implemented for real-time vehicle detection and classification. |
| Ultralytics | Provided the implementation of YOLO used for both training and inferencing with the YOLO-based model for the real-time vehicle detection and classification. |
| Pytorch | Used for model training and performance evaluation. |
| TorchVision | Used for running the YOLO model and performing the inferencing process. |
| Gradio | Used for creating a Graphical User Interface (GUI) the model integration nad simulation of the CCTV surveillance. |
| Google Colab | Provided computational resources such as GPU support for running and training the model. |
| Roboflow | Used for hosting the dataset and performing data pre-processing. |
| Display | Used for displaying inferenced images, training results and test images in the program notebook. |
| Image | Used for creating python objects representing an image. |
| Shutil | Used for high-level image file operations. |
| CSV | Used for for reading and writing to .txt files. |
| Codecs | Used for manipulation of video data. |

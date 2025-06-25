#  Brain Tumor Detection & Segmentation using YOLOv11 & SAM2

This project is an advanced AI-based application that detects and segments brain tumors in MRI scans using a combination of **YOLOv11** for detection and **SAM2 (Segment Anything Model)** for pixel-precise segmentation. It blends **deep learning models** with practical medical imaging workflows.

---

## Youtube Link
https://youtu.be/jEt3EyGYu80?si=tEdlSTpeptmwPTTa


##  Features

-  Detects four types of brain conditions: `glioma`, `meningioma`, `pituitary`, and `no_tumor`
-  Automatically segments the detected tumor region using SAM2
-  Supports upload and testing of new MRI images
-  Visual training results: predictions, confusion matrix, accuracy plots
-  Easy-to-run via Google Colab or local Python environment

---

##  Technologies Used

- **Detection Model**: YOLOv11 (Ultralytics)
- **Segmentation Model**: SAM2 (Meta AI - Segment Anything Model)
- **Dataset**: [Roboflow MRI Brain Tumor Dataset](https://universe.roboflow.com/brain-tumor-detection-wsera/tumor-detection-ko5jp/dataset/8)
- **Annotation Format**: YOLO (bbox + class)
- **Training Framework**: Ultralytics library with PyTorch backend
- **Libraries & Dependencies**:  
  - `ultralytics`  
  - `torch`  
  - `opencv-python`  
  - `matplotlib`  
  - `PIL`  




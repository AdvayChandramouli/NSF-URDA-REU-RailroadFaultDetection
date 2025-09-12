# Deep Learning Approaches for Railroad Infrastructure Monitoring: Comparing YOLO and Vision Transformers for Defect Detection

This repository contains our work on applying **Computer Vision (CV)** and **Deep Learning (DL)** for automated detection of railroad tie defects.  
Our research compared two state-of-the-art object detection architectures, **YOLOv11-L** and **RT-DETR-L**, using annotated field-test footage.  

---
## Research Methodology
1. **Data Collection & Annotation**  
   - Collected field-test footage from abandoned railroad segments.  
   - Annotated three defect classes: *wood checks, wood decay, and wood ties*.  

2. **Model Training**  
   - Implemented **5-fold cross-validation**.  
   - Fixed hyperparameters (epochs, batch sizes and optimizer configurations) for both YOLOv11 and RT-DETR.  

3. **Evaluation Metrics**  
   - Compared models based on **F1 Score, Precision, Recall, and mAP (IoU 0.5–0.95)**.  
   - Analyzed confusion matrices for per-class performance.  

---

## Project Artifacts
- Includes Final Presentation, Final Conference Paper
---

## Program Acknowledgement
This research was part of the National Science Foundation (NSF) Research Experiences for Undergraduates (REU) program in Data Analytics, at Marshall University, under the guidance of Dr. Husnu Narman. 
We thank the NSF for facilitating this work and providing valuable exposure to intelligent transportation systems. We also thank Dr. Haroon Malik and Dr. Yousef Fazea for their guidance and feedback.


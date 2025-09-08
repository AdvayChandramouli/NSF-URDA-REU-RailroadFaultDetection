# Railroad Tie Defect Detection with Deep Learning

This repository contains our work on applying **Computer Vision (CV)** and **Deep Learning (DL)** for automated detection of railroad tie defects.  
Our research compared two state-of-the-art object detection architectures, **YOLOv11-L** and **RT-DETR-L**, using annotated field-test footage.  

---

## Research Process
1. **Data Collection & Annotation**  
   - Collected field-test footage from abandoned railroad segments.  
   - Annotated three defect classes: *wood checks, wood decay, and wood ties*.  

2. **Model Training**  
   - Implemented **5-fold cross-validation**.  
   - Optimized hyperparameters for both YOLOv11 and RT-DETR.  

3. **Evaluation Metrics**  
   - Compared models based on **F1 Score, Precision, Recall, and mAP (IoU 0.5–0.95)**.  
   - Analyzed confusion matrices for per-class performance.  

4. **Key Findings**  
   - **YOLOv11** achieved superior performance across most metrics, particularly in Precision and mAP, making it more deployment-ready for real-world inspection.  
   - **RT-DETR** showed a slight edge in Recall but at the cost of more false positives.  

---

## Program Acknowledgement
This research was conducted as part of the **NSF Undergraduate Research in Data Analytics (URDA) REU**  
at **Marshall University** in Summer 2025.  

- Pictures/Collages to be added soon.
  
---

## Final Deliverables
- 📑 [Final Conference Paper](#)  
- 🎤 [Final Presentation Slides](#)  

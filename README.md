# Enhanced Plant Disease Detection Using Drone Imagery and Automated Learning Optimization

## 📄 Research Overview  
This repository contains the research paper **"Enhanced Plant Disease Detection Using Drone Imagery and Automated Learning Optimization."**  
It explores the use of drone-captured imagery combined with deep learning models to identify plant diseases and stress factors in cashew orchards.

## 📑 Abstract  
This paper explores the use of drone-captured imagery combined with deep learning models to identify diseases and stress factors in cashew orchards.  
Our research focuses on three primary stressors: **insect damage, biotic stress from pathogens, and abiotic factors.**  

To address **dataset imbalance**, we employed **advanced data augmentation techniques** to enhance model training.  
Additionally, we introduced an **orchestrated training function** that dynamically adjusts the learning rate for optimal performance.  

We evaluated two state-of-the-art object detection models:  
- **YOLOv9:** Achieved an overall **mAP50 of 0.601**, excelling in **insect detection** (mAP50: **0.777**) but struggled with abiotic stress (mAP50: **0.513**) and disease detection (mAP50: **0.512**).  
- **YOLOv10:** Achieved an overall **mAP50 of 0.554**, with a strong insect detection score of **0.713** but lower performance in abiotic stress (**0.468**) and disease detection (**0.481**).  

### **Findings:**  
- Deep learning models showed strong **potential** in detecting **insect-related damage**.  
- Challenges remain in accurately identifying **abiotic stress and diseases**, particularly in complex environments.  
- **Future work** will explore **multispectral imaging** and **real-time detection systems** to improve precision agriculture.  

**Keywords:** Crop Disease Detection, YOLOv10, YOLOv9, Object Detection  

---


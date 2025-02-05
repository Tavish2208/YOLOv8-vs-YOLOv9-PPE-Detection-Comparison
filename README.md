# Comparative Analysis of YOLOv8 and YOLOv9 for PPE Detection

## Overview
This project presents a comparative analysis of two versions of the YOLO architecture, **YOLOv8** and **YOLOv9**, for detecting **Personal Protective Equipment (PPE)** on construction sites. The study evaluates the models in terms of **accuracy, speed, and robustness**, providing insights into their strengths and limitations in real-world applications.

## Objectives
- Evaluate the performance of **YOLOv8** and **YOLOv9** in PPE detection.
- Analyze detection accuracy, speed, and computational efficiency.
- Assess how architectural improvements in YOLOv9 impact PPE detection compared to YOLOv8.
- Provide recommendations for adopting the best-suited model for workplace safety enhancement.

## Technologies Used
- **Deep Learning Framework:** PyTorch
- **Object Detection Models:** YOLOv8, YOLOv9
- **Dataset:** Construction site imagery with PPE annotations
- **Evaluation Metrics:** mAP (Mean Average Precision), FPS (Frames Per Second), Precision-Recall
- **Hardware:** NVIDIA GPU (for accelerated model training and inference)

## Methodology
1. **Data Preprocessing**
   - Collected and annotated construction site images with PPE labels.
   - Augmented data to improve model generalization.
   
2. **Model Training**
   - Trained YOLOv8 and YOLOv9 models on the same dataset.
   - Tuned hyperparameters for optimal performance.

3. **Evaluation & Comparison**
   - Compared **detection accuracy, speed, and computational requirements**.
   - Tested both models under various lighting and environmental conditions.

## Results & Findings
- **YOLOv8**:
  - Achieves state-of-the-art results with spatial pyramid pooling (SPP) and Path Aggregation Network (PAN).
  - Faster inference time compared to older YOLO versions.
  
- **YOLOv9**:
  - Introduces dynamic scaling and context aggregation for improved accuracy.
  - Better performance in complex environments but requires higher computational resources.
  
## Output Screenshots
Below are sample detection outputs from both models:

![YOLOv8 Detection](images/yolov8_detection.png)
![YOLOv9 Detection](images/yolov9_detection.png)

## Future Enhancements
- Deploying models on edge devices for real-time PPE monitoring.
- Exploring hybrid models combining strengths of both YOLOv8 and YOLOv9.
- Improving dataset diversity for better generalization.

## Conclusion
The comparison highlights the trade-offs between **speed and accuracy** in YOLOv8 and YOLOv9. The findings contribute to ongoing safety efforts in construction industries through advanced deep learning techniques.

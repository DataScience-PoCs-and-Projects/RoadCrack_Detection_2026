\# RoadCrack\_Detection\_2026



Road Crack Detection using Instance Segmentation Methods



\# Road Crack Detection – Proposed Method



\## Overview



This project presents a deep learning-based road pavement defect detection and structural assessment system using \*\*YOLO26s, custom Strip-Convolution (STRIP) blocks, Grad-CAM explainability, and Vision-Language Model (VLM) integration\*\*.



The approach aims to detect different types of road pavement defects, explain the model's predictions, and provide an understandable assessment of the detected damage.



\## Proposed Methodology



The system consists of four major components:



\### 1. YOLO26s with STRIP



\- Uses YOLO26s as the base object detection architecture.

\- Integrates custom Strip-Convolution blocks to capture elongated and directional crack features.

\- Uses the custom NeckStrip module for enhanced feature extraction.

\- Detects four categories of road pavement defects:

&#x20; - Longitudinal Crack

&#x20; - Transverse Crack

&#x20; - Alligator Crack

&#x20; - Pothole



\### 2. Grad-CAM Explainability



\- Applies Grad-CAM / HiResCAM techniques to visualize the important image regions influencing model predictions.

\- Generates heatmaps to highlight detected crack-related features.

\- Helps understand how the model identifies pavement defects.



\### 3. Vision-Language Model (VLM)



\- Integrates Qwen2-VL for multimodal analysis of road pavement images.

\- Provides descriptions of visible damage patterns and their distribution.

\- Assesses structural severity as Low, Medium, or High.

\- Suggests suitable maintenance and repair actions.



\### 4. Structural Assessment



Combines detection results and visual analysis to provide:



\- Defect identification.

\- Damage description.

\- Severity assessment.

\- Recommended repair actions.



\## Technologies Used



\- Python

\- PyTorch

\- Ultralytics YOLO26s

\- Custom Strip-Convolution Modules

\- Grad-CAM / HiResCAM

\- Qwen2-VL

\- OpenCV



\## Objective



To develop an explainable and intelligent road pavement defect detection system that combines object detection, visual explanation, and vision-language-based structural assessment to support road condition monitoring and maintenance.


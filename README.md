# Detection of Anomalous Candidate Actions in Examination Settings Using YOLOv11

The rapid pace of technology development and the complexity of candidates' cheating actions or methods have prompted the need to improve and uphold institutions' integrity and trustworthiness. Furthermore, traditional techniques, such as manual supervision by examiners and CCTV video cameras, are frequently incapable of recognising discreet subtle, or unsanctioned violations of a candidate’s actions (Riaz et al., 2021). Due to such shortcomings in this era, examination processes lose their fairness and credibility. 

# Method Overview
The model assessed in this scholarly research is YOLOv11, the newest in the YOLO family – famous for its incredible speed and accuracy. In addition, it employs network architectures, including transformer-based networks, advanced convolutional layers, and advanced loss functions to identify many objects and actions in one frame (Khanam and Hussain, 2024). The benefits of this new architecture are rapid processing and accuracy and the capability to operate in very dynamic environments (Khan and Jensen, 2024). 

# YOLOv11 Architecture 

Fundamentally, the YOLOv11 architecture has three basic components, as illustrated in Figure 3-1. The first essential component in the design is — one backbone, which is said to be the main feature extractor that transforms raw image data into multi-scale feature maps through convolutional neural networks. The neck functions as an intermediate processing step and utilises special layers for feature aggregations and enhancements across various scales. Thirdly, the head component executes the prediction mechanism, delivering the final outputs for object localisation and classification from the refined feature maps (Khan and Jensen, 2024; Khanam and Hussain, 2024).

<image src="./images/Architecture.png">

# Dataset

The datasets were collected using a camera. All the images captured illustrate distinct cheating anomalous actions exhibited by candidates in exam settings or not.  Furthermore, 362 images were captured, and the dataset consisted of 315 (87%) training images, 17 (5%) testing images, and 30 (8%) for model validation ([KAttal, 2022](https://universe.roboflow.com/kattal/exam-cheating)).

# Confusion Matrix
<image src="./images/confusion_matrix.png">

# Confusion Matrix Normalized 
<image src="./images/confusion_matrix_normalized.png">

# Labels
<image src="./images/labels.jpg">

# Validation Label
<image src="./images/val_batch0_labels.jpg">

# Validation Predications
<image src="./images/val_batch0_pred.jpg">

# References
- Riaz, H., Uzair, M., Ullah, H., and Ullah, M. (2021) Anomalous Human Action Detection Using a Cascade of Deep Learning Models. 2021 9th European Workshop on Visual Information Processing (EUVIP), [Online] pp. 1-5. Available from: https://ieeexplore.ieee.org/document/. [Accessed 8 December 2024]. 
- KAttal (2022) Exam cheating dataset. Roboflow Universe, [Online]. Available from: https://universe.roboflow.com/kattal/exam-cheating.  [Accessed 9 December 2024].
- Khan, A., T. and Jensen, S., M. (2024) LEAF-Net: A Unified Framework for Leaf Extraction and Analysis in Multi-Crop Phenotyping Using YOLOv11.  [Online] PREPRINT (Version 1). Available from: https://www.researchsquare.com/article/. [Accessed 9 December 2024]. 
- Khanam, R. and Hussain, M. (2024) YOLOv11: An Overview of the Key Architectural Enhancements. [Online]. Available from: https://arxiv.org/. [Accessed 10 December 2024]. 

# Week 4 – Training & Evaluating an Object Detection Model

## Learning Goals
- Train an object detection model end-to-end
- Understand how object detection models are evaluated
- Learn to interpret metrics like Precision, Recall, IoU, and mAP
- Analyze model predictions and failure cases

---

## What This Week Is About
This week focuses on **training and evaluation**, not architectural theory.

You will:
- Prepare a dataset for training
- Train a YOLO-based object detection model
- Evaluate performance using standard detection metrics
- Visually inspect predictions and understand model failures

The goal is **understanding model behavior**, not maximizing accuracy.

---

## Model Choice
- **Week 3:** YOLOv3 was used for architectural clarity
- **Week 4:** YOLOv8 is used for training due to:
  - Stable implementation
  - Minimal boilerplate
  - Industry adoption
  - Clean evaluation outputs

Concepts remain the same across YOLO versions.

---

## Core Topics & Resources

---

### 1. Object Detection – Training Overview

📘 **Article**
- How Object Detection Works (PyImageSearch)  
  https://pyimagesearch.com/2018/11/12/yolo-object-detection-with-opencv/

📘 **Article**
- Object Detection Explained  
  https://machinelearningmastery.com/object-recognition-with-deep-learning/

---

### 2. Bounding Boxes & IoU

📘 **Official Explanation**
- Intersection over Union (IoU)  
  https://www.analyticsvidhya.com/blog/2019/08/what-is-intersection-over-union-iou/

📘 **Visual Explanation**
- IoU Explained Clearly  
  https://www.v7labs.com/blog/intersection-over-union-guide

---

### 3. Precision, Recall & mAP (Detection Context)

📘 **mAP Explained**
- Mean Average Precision (mAP)  
  https://blog.roboflow.com/mean-average-precision/

📘 **Precision–Recall in Object Detection**
- https://www.v7labs.com/blog/precision-recall-object-detection

📘 **Why Accuracy Is Not Used**
- https://towardsdatascience.com/accuracy-is-not-enough-59b1b1e87a4c

---

### 4. YOLOv8 Training & Evaluation

📘 **Official Documentation**
- Ultralytics YOLO Docs  
  https://docs.ultralytics.com

📘 **Training Guide**
- YOLOv8 Training Walkthrough  
  https://docs.ultralytics.com/modes/train/

📘 **Evaluation & Metrics**
- YOLOv8 Validation  
  https://docs.ultralytics.com/modes/val/

---

### 5. Failure Modes in Object Detection

📘 **Common Detection Errors**
- https://blog.roboflow.com/failure-modes-object-detection/

📘 **Small Objects & Bias**
- https://www.v7labs.com/blog/object-detection-challenges

** Suggestion to find YT videos relating to the topic that help you out.**
---

## Tasks
- Prepare dataset in YOLO format
- Train a YOLOv8 object detection model
- Evaluate using IoU, Precision, Recall, and mAP
- Visualize predictions
- Perform qualitative error analysis

---

## Submission Checklist
- Trained model weights
- Evaluation metrics
- Prediction visualizations
- Short reflection on:
  - What worked
  - What failed
  - Why those failures occur

---

## Key Takeaway
Training a model is mechanical.  
Understanding **why it fails** is the real skill.

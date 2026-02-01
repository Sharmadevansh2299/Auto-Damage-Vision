# Week 5 – Vehicle Damage Severity Classification

## Objective
This week completes the problem statement by classifying the **severity of detected vehicle damage**.

Instead of modifying the detector, we follow a modular CV pipeline:
- YOLOv8 detects damage regions
- A CNN classifies severity from cropped regions

This mirrors real-world deployment systems.

---

## Learning Goals
- Understand severity as a semantic concept
- Build datasets from YOLOv8 outputs
- Train a CNN-based severity classifier
- Integrate detection and classification
- Analyze system failures

---

## Severity Classes
We define three levels:
- Minor: scratches, small dents
- Moderate: visible deformation
- Severe: broken or detached parts

Severity is not determined by bounding box size alone.

---

## Notebooks
- `week5_crop_from_yolo.ipynb`: Crop damage regions using YOLOv8 outputs
- `week5_severity_classifier.ipynb`: Train CNN classifier
- `week5_full_pipeline.ipynb`: End-to-end inference

---

## Submission
- All notebooks
- Trained severity model
- Reflection on model behavior and limitations

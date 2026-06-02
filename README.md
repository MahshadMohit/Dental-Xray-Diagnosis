# Multi-Class Dental Abnormality and Structure Detection in Panoramic Radiographs

This repository contains an end-to-end computer vision pipeline designed to automate the detection and classification of dental pathologies, restorations, and anatomical structures from panoramic dental X-rays (orthopantomograms). Powered by the YOLO object detection framework, the system provides clinical-grade visual overlays paired with a clean, dynamic side-panel legend for structured diagnostics.

## Features

* **31 Clinical Classes Supported**: Robustly detects various pathologies, dental history, and standard anatomical structures.
* **Optimized Color Masking**: Implements a dedicated 31-color palette (`PALETTE`) engineered to maintain distinct contrast between bounding boxes even in highly crowded dental arches.
* **Side-by-Side Legend Generation**: Automatically computes aspect ratios and appends a dynamic, clean visual chart alongside the X-ray canvas for straightforward diagnosis review.
* **Adaptive Text Rendering**: Gracefully handles cross-platform font rendering by checking system defaults before applying custom scale factors.

## Supported Clinical Categories

The model categorizes and bounds features into three major operational groups:

* **Pathologies & Conditions**: Caries, Periapical Lesion, Cyst, Bone Loss, Bone Defect, Root Resorption, Fractured Teeth, Impacted Tooth, Attrition, Malaligned, Supra Eruption.
* **Restorations & Orthodontics**: Crown, Filling, Implant, Root Canal Treatment, Post-core, Plating, Wire, Orthodontic Brackets, Permanent Retainer, Metal Band, Gingival Former, Abutment.
* **Anatomical Landmarks**: Mandibular Canal, Maxillary Sinus, Retained Root, Root Piece, Permanent Teeth, Primary Teeth, TAD (Temporary Anchorage Device).

<img width="1570" height="650" alt="output" src="https://github.com/user-attachments/assets/4ea9645c-22fa-4795-9d8a-e88ae49bbc34" />


## Note
This project also has a mini version of segmentation of carries masks, I'd be happy if you check that :)
https://github.com/MahshadMohit/Dental-X-Rays-Caries-Segmentation

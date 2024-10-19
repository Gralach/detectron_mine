# Illegal Mine Detection in Indonesia Using Detectron2
## 📑 Project Overview

This project focuses on detecting illegal mines in Indonesia through object detection and instance segmentation techniques. Using Mask R-CNN from the Detectron2 library, the model is trained to identify and classify images into two classes: Illegal and Legal.

---

## ⚙️ **Installation**

1. **Clone the repository:**

2. **Create a virtual environment:**
   
3. **Install the dependencies:**
   
4. **Install Detectron2:**
   Follow the official Detectron2 [installation guide](https://detectron2.readthedocs.io/tutorials/install.html) based on your system.

5. **Download the maskRCNN COCO model:**
   Download the mask_rcnn_coco.h5 (https://github.com/matterport/Mask_RCNN/releases/tag/v2.0)

---

## 🗂️ **Dataset**

The dataset used in this project contains images labeled into two categories:
1. **Illegal**: Images showing illegal mining activities.
2. **Legal**: Images showing legal activities or no mining.

---

## 📊 **Results**

The model's performance is evaluated using **COCO metrics** for **bounding box detection** and **segmentation**. Below are the results on the test set:

| **Metric**   | **Value** |
|--------------|-----------|
| AP (Overall) | 55.64%    |
| AP50         | 89.96%    |
| AP75         | 47.72%    |
| AP_Large     | 60.41%    |

---

## 🗺️ **Challenges in Illegal Mine Detection**

Illegal mining poses significant environmental threats and is difficult to monitor manually. This project aims to leverage computer vision to help authorities automatically detect illegal activities and take action more efficiently.

---

## 📄 **Acknowledgements**

- **Detectron2:** A flexible object detection framework by Facebook AI Research.
- **COCO Dataset Format:** Used for annotations and model evaluation.

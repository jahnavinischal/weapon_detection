# Weapon Detection

It is a weapon detection project trained with YOLO. The notebook demonstrates building a detection pipeline that trains/evaluates a model and runs inference on images from surveillance videos to identify weapons (guns, knives, etc.). 

---

## Features

* Data loading and preprocessing (image resizing, augmentation, annotation parsing)
* Model training pipeline (backbone / object detector used inside the notebook)
* Evaluation metrics and visualizations (precision, recall, mAP where available)
* Inference on images and video (annotated output saving)

---

## Folder / File overview

* `weapon_detection.ipynb` — The main notebook with data prep, training, evaluation and inference cells.


---

## Requirements

Install mecessary with pip command.


---

## Dataset

The dataset is taken from ![https://www.kaggle.com/datasets/snehilsanyal/weapon-detection-test/data]Kaggle.


---

## How to run

1. Clone the repository:

```bash
git clone https://github.com/jahnavinischal/weapon_detection.git
cd weapon_detection
```

2. Create and activate your virtual environment and install dependencies.

## Result: 
One of the output is as shown in the figure:
![WhatsApp Image 2025-09-18 at 16 15 39_8c3fc1cc](https://github.com/user-attachments/assets/9ad0fdf5-ca3e-4a7a-86b2-d94179734159)

---


## Improvements & Next steps

If you want to improve the project, consider:

* Using a modern, high-performance detection architecture (YOLOv5/YOLOv8, Detectron2, EfficientDet, etc.).
* Expanding and diversifying the dataset to reduce bias and improve generalization.
* Converting the notebook pipeline into modular scripts or a Python package for easier reuse.
* Using live video surveilance

---


